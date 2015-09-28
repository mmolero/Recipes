

####Theano

Pre-built packages

http://www.lfd.uci.edu/~gohlke/pythonlibs/


### Graphviz

If you have installed graphviz and pydot, theano might complain that it cannot find the executable.
Just add this to the registry:

    [HKEY_LOCAL_MACHINE\SOFTWARE\ATT\Graphviz]
    "InstallPath"="C:\\Program Files (x86)\\Graphviz2.38"