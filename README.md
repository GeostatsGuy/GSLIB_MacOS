# GSLIB_MacOS
Executables for GSLIB on Mac OS X

GSLIB, Geostatistical Library  (Deutsch and Journel, 1998) is a set of open source code in Fortran, including many of the fundamental geostatistical methods.  The code is very well tested and has been widely used.  The GeostatsPy functions run these executables to build geostatistical workflows in Python.  

Appreciation to Prof. Clayton Deutsch for providing this open source to benefit the community.  Yet, while executables are available in Windows, Linux and SunOS (GSLIB.com) there are no executables available online for Mac OS. This has been an obstacle to my undergraduate students using Mac.  The original Fortran source was compiled for use on the Mac OS by Wendi Liu (one of my PhD students here at the University of Texas).  Since static compiles are not possible on the Mac you may have to first install a Fortran compiler on your machine to get the required DLL (dynamically linked libraries) for runtime use.  See the attached PPTX file for instructions on installing a Fortran compiler if you get missing DDL errors at runtime.  
