## Configure .pro File in QCreator for VTK project on Windows
----

**Example**:

Note than "LIBS" Folder must inclue the .lib and .dll files

```
#-------------------------------------------------
#
# Project created by QtCreator 2015-07-22T17:17:08
#
#-------------------------------------------------

QT       += core gui

greaterThan(QT_MAJOR_VERSION, 4): QT += widgets

TARGET = qView
TEMPLATE = app

SOURCES += main.cpp\
        mainwindow.cpp

HEADERS  += mainwindow.h
FORMS    += mainwindow.ui


INCLUDEPATH += "E:\\Library\\VTK\\include\\vtk-6.2\\"
LIBS += -LE:\\Library\\VTK\\lib

LIBS += -lvtkCommonCore-6.2
LIBS += -lvtkCommonExecutionModel-6.2
LIBS += -lvtksys-6.2
LIBS += -lQVTKWidgetPlugin                 # QT RELATED
LIBS += -lvtkChartsCore-6.2
LIBS += -lvtkViewsQt-6.2                   # QT Related
LIBS += -lvtkInteractionWidgets-6.2
LIBS += -lvtkInfovisCore-6.2
LIBS += -lvtkRenderingCore-6.2
LIBS += -lvtkRenderingOpenGL-6.2
LIBS += -lvtkImagingCore-6.2
LIBS += -lvtklibxml2-6.2
LIBS += -lvtkDICOMParser-6.2
LIBS += -lvtkpng-6.2
LIBS += -lvtktiff-6.2
LIBS += -lvtkzlib-6.2
LIBS += -lvtkjpeg-6.2
LIBS += -lvtkalglib-6.2
LIBS += -lvtkexpat-6.2
LIBS += -lvtkverdict-6.2
LIBS += -lvtkmetaio-6.2
LIBS += -lvtkNetCDF-6.2
LIBS += -lvtksqlite-6.2
LIBS += -lvtkexoIIc-6.2
LIBS += -lvtkftgl-6.2
LIBS += -lvtkfreetype-6.2
LIBS += -lvtkFiltersSources-6.2
LIBS += -lvtkGUISupportQt-6.2             #QT related

LIBS += -lvtkalglib-6.2
LIBS += -lvtkChartsCore-6.2
LIBS += -lvtkCommonColor-6.2
LIBS += -lvtkCommonComputationalGeometry-6.2
LIBS += -lvtkCommonCore-6.2
LIBS += -lvtkCommonDataModel-6.2
LIBS += -lvtkCommonExecutionModel-6.2
LIBS += -lvtkCommonMath-6.2
LIBS += -lvtkCommonMisc-6.2
LIBS += -lvtkCommonSystem-6.2
LIBS += -lvtkCommonTransforms-6.2
LIBS += -lvtkDICOMParser-6.2
LIBS += -lvtkDomainsChemistry-6.2
LIBS += -lvtkexoIIc-6.2
LIBS += -lvtkexpat-6.2
LIBS += -lvtkFiltersAMR-6.2
LIBS += -lvtkFiltersCore-6.2
LIBS += -lvtkFiltersExtraction-6.2
LIBS += -lvtkFiltersFlowPaths-6.2
LIBS += -lvtkFiltersGeneral-6.2
LIBS += -lvtkFiltersGeneric-6.2
LIBS += -lvtkFiltersGeometry-6.2
LIBS += -lvtkFiltersHybrid-6.2
LIBS += -lvtkFiltersHyperTree-6.2
LIBS += -lvtkFiltersImaging-6.2
LIBS += -lvtkFiltersModeling-6.2
LIBS += -lvtkFiltersParallel-6.2
LIBS += -lvtkFiltersParallelImaging-6.2
LIBS += -lvtkFiltersProgrammable-6.2
LIBS += -lvtkFiltersSelection-6.2
LIBS += -lvtkFiltersSMP-6.2
LIBS += -lvtkFiltersSources-6.2
LIBS += -lvtkFiltersStatistics-6.2
LIBS += -lvtkFiltersTexture-6.2
LIBS += -lvtkFiltersVerdict-6.2
LIBS += -lvtkfreetype-6.2
LIBS += -lvtkftgl-6.2
LIBS += -lvtkGeovisCore-6.2
LIBS += -lvtkgl2ps-6.2
LIBS += -lvtkGUISupportQt-6.2
LIBS += -lvtkGUISupportQtOpenGL-6.2           #qt related
LIBS += -lvtkGUISupportQtSQL-6.2              #qt related
LIBS += -lvtkGUISupportQtWebkit-6.2           #qt related
LIBS += -lvtkhdf5_hl-6.2
LIBS += -lvtkhdf5-6.2
LIBS += -lvtkImagingColor-6.2
LIBS += -lvtkImagingCore-6.2
LIBS += -lvtkImagingFourier-6.2
LIBS += -lvtkImagingGeneral-6.2
LIBS += -lvtkImagingHybrid-6.2
LIBS += -lvtkImagingMath-6.2
LIBS += -lvtkImagingMorphological-6.2
LIBS += -lvtkImagingSources-6.2
LIBS += -lvtkImagingStatistics-6.2
LIBS += -lvtkImagingStencil-6.2
LIBS += -lvtkInfovisCore-6.2
LIBS += -lvtkInfovisLayout-6.2
LIBS += -lvtkInteractionImage-6.2
LIBS += -lvtkInteractionStyle-6.2
LIBS += -lvtkInteractionWidgets-6.2
LIBS += -lvtkIOAMR-6.2
LIBS += -lvtkIOCore-6.2
LIBS += -lvtkIOEnSight-6.2
LIBS += -lvtkIOExodus-6.2
LIBS += -lvtkIOExport-6.2
LIBS += -lvtkIOGeometry-6.2
LIBS += -lvtkIOImage-6.2
LIBS += -lvtkIOImport-6.2
LIBS += -lvtkIOInfovis-6.2
LIBS += -lvtkIOLegacy-6.2
LIBS += -lvtkIOLSDyna-6.2
LIBS += -lvtkIOMINC-6.2
LIBS += -lvtkIOMovie-6.2
LIBS += -lvtkIONetCDF-6.2
LIBS += -lvtkIOParallel-6.2
LIBS += -lvtkIOPLY-6.2
LIBS += -lvtkIOSQL-6.2
LIBS += -lvtkIOVideo-6.2
LIBS += -lvtkIOXML-6.2
LIBS += -lvtkIOXMLParser-6.2
LIBS += -lvtkjpeg-6.2
LIBS += -lvtkjsoncpp-6.2
LIBS += -lvtklibxml2-6.2
#LIBS += -lvtkLocalExample-6.2
LIBS += -lvtkmetaio-6.2
LIBS += -lvtkNetCDF_cxx-6.2
LIBS += -lvtkNetCDF-6.2
LIBS += -lvtkoggtheora-6.2
LIBS += -lvtkParallelCore-6.2
LIBS += -lvtkpng-6.2
LIBS += -lvtkproj4-6.2
LIBS += -lvtkRenderingAnnotation-6.2
LIBS += -lvtkRenderingContext2D-6.2
LIBS += -lvtkRenderingCore-6.2
LIBS += -lvtkRenderingFreeType-6.2
LIBS += -lvtkRenderingFreeTypeOpenGL-6.2
LIBS += -lvtkRenderingGL2PS-6.2
LIBS += -lvtkRenderingImage-6.2
LIBS += -lvtkRenderingLabel-6.2
LIBS += -lvtkRenderingLIC-6.2
LIBS += -lvtkRenderingLOD-6.2
LIBS += -lvtkRenderingOpenGL-6.2
LIBS += -lvtkRenderingQt-6.2                   #qt related
LIBS += -lvtkRenderingVolume-6.2
#LIBS += -lvtkRenderingVolumeAMR-6.2
LIBS += -lvtkRenderingVolumeOpenGL-6.2
LIBS += -lvtksqlite-6.2
LIBS += -lvtksys-6.2
#LIBS += -lvtkTestingRendering-6.2
LIBS += -lvtktiff-6.2
LIBS += -lvtkverdict-6.2
LIBS += -lvtkViewsContext2D-6.2
LIBS += -lvtkViewsCore-6.2
#LIBS += -lvtkViewsGeovis-6.2
LIBS += -lvtkViewsInfovis-6.2
LIBS += -lvtkViewsQt-6.2                   #QT Related
LIBS += -lvtkzlib-6.2

```


#### References

-------
http://stackoverflow.com/questions/30752232/unresolve-external-symbol-error-when-using-qvtkwidgetvtk-6-2-0-in-qt5-4-2