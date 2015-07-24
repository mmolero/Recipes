##VTK Compilation CMAKE & Visual Studio

VTK Version: 6.2
QT Version: 5.4 VisualStudio 2013

---

Edit:

VTK_Group_Qt: BOOL=ON
CMAKE_INSTALL_PREFIX: PATH = E:/Library/VTK

Add Entry:

QT_QMAKE_EXECUTABLE: FILEPATH = C:\Qt\Qt5.4.2\5.4\msvc2013_64_opengl\bin\qmake.exe
VTK_QT_VERSION: STRING = 5 
CMAKE_PREFIX_PATH: PATH = C:/Qt/Qt5.4.2/5.4/msvc2013_64_opengl: PATH = C:\Qt\Qt5.4.2\5.4\msvc2013_64_opengl

---

References:

http://www.vtk.org/Wiki/VTK/Configure_and_Build
https://sites.google.com/a/realworldrobotics.com/programming/platforms-frameworks/vtk/compiling-vtk-using-cmake-and-visual-studio