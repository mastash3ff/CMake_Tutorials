
# CMake Tutorial


Source tutorial: https://cmake.org/cmake-tutorial/

## Step 0 - Barebones

Two files:  CMakeLists.txt and tutorial.cxx

```bash
cmake . #generate cmake build files
make    #generate binary called TUTORIAL
./TUTORIAL 4   #run it
```

##  Step 1 - Adding a Version Number and Configured Header File

Cmake allows us to add more flexability to our project without modifying source code.  This example adds a version number.

```bash
cmake .
make
./TUTORIAL 4
```

