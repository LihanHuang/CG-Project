# CG-Project

Instructions to run code: 
  1. Unzip CG.zip
  2. Open CG.pro in Qt Creator and simply build debug/release mode
  3. Build Steps in Qt Creator is: qmake CG.pro -spec macx-clang CONFIG+=x86_64
  4. To run code on other Linux Systems, you may need:
            Qt Framework, GCC
            change CG.pro to use OpenGL and Glut
  
Instructions to run executable:
  1. Unzip Release.zip
  2. Run shell scripts in command line
            bash bear.sh (run on bear dataset)
            bash hand.sh (run on hand dataset)
            bash train.sh, bash test.sh (run on human dataset)

Relevant Information:
  1. OS: macOS High Sierra version 10.13.1
  2. IDE: Qt Creator 4.3.1 based on Qt 5.9.1 (Clang 7.0 (Apple), 64 bit)
  3. Frameworks used: OpenGL, Glut
  4. Libraries used: 
            Eigen for Solving Linear Equations
            Spectra for Eigen Decomposition
            Ranger for Random Forest Regression
