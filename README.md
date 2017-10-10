# opencv
Playground for my opencv experiments.

# install opencv libraries on mac
- install via homebrew
  - tell formula to do java as well by editing formula via ```brew edit opencv```
  - turn support for java on ```-DBUILD_opencv_java=ON```
  - install ```brew install --build-from-source opencv```
  
# install opencv libraries on windows
- get package from here ```https://opencv.org/releases.html```
  
# working with eclipse projects
- git clone
- import into workspace
- add opencv jar to build path
- add dylib to java.library.path as VM argument: ```-Djava.library.path=lib```
  - if on windows add dll to project lib path first