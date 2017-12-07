# CG-Project

Instructions to run code: 
  1. Unzip CG.zip
  2. Open CG.pro in Qt Creator and simply build debug/release mode
  3. Build Step in Qt Creator is: qmake CG.pro -spec macx-clang CONFIG+=x86_64
  4. To run code on other Linux Systems, you may need:
    (1). Qt Framework, GCC
    (2). change CG.pro to use OpenGL and Glut 

Instructions to run executable:
  1. Unzip Release.zip
  2. Run shell scripts in command line (note you need to quit the display windows to continue processing, in mac Command+q)
    (1). bash bear.sh (run on bear dataset)
    (2). bash hand.sh (run on hand dataset)
    (3). bash train.sh, bash test.sh (run on human dataset)

Relevant Information:
  1. OS: macOS High Sierra version 10.13.1
  2. IDE: Qt Creator 4.3.1 based on Qt 5.9.1 (Clang 7.0 (Apple), 64 bit)
  3. Frameworks used: OpenGL, Glut
  4. Libraries used: 
    (1). Eigen for Solving Linear Equations
    (2). Spectra for Eigen Decomposition
    (3). Ranger for Random Forest Regression

 Screenshots:
  1. Top left: User defined feature points on 3D shapes
  2. Top right: Heat Geodesic Field computed from feature points
  3. Bottom left: SIHKS of 3D shapes
  4. Bottom right: Localization of features using predicted distances
