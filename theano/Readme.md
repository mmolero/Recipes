

####Theano

Pre-built packages

http://www.lfd.uci.edu/~gohlke/pythonlibs/


### Graphviz

If you have installed graphviz and pydot, theano might complain that it cannot find the executable.
Just add this to the registry:

    [HKEY_LOCAL_MACHINE\SOFTWARE\ATT\Graphviz]
    "InstallPath"="C:\\Program Files (x86)\\Graphviz2.38"
    
    
### Anaconda Distribution

- CUDA Toolkit 7.5
- conda install mingw libpython
- Edit theanorc.txt in $USERPROFILE$:

    ```
    [global]
    floatX = float32
    device = gpu

    [nvcc]
    fastmath = True
    flags=-LC:\Users\Miguel\Anaconda\libs
    compiler_bindir=C:\Program Files (x86)\Microsoft Visual Studio 12.0\VC\bin
    
    ```
    
