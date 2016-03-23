# ev3programs

These programs can operate LEGO ev3 by using ev3dev c++ API.
To compile these source code, you need a ev3dev c++ API build environment.
Please refer the following links for more details about ev3dev c++ API.

https://github.com/ddemidov/ev3dev-lang-cpp

When you get ev3dev c++ API compiled, you can just put these c++ source code
to API's demos folder, add a new line in demos' CMakeLists.txt file like follows.

====  CMakeLists.txt ====
...
add_ev3_executable(robot_arm          robot_arm.cpp)

Then you can run the following command in build folder.
#cmake ..
#make

At last, put the binary to you ev3 device, have a fun.
