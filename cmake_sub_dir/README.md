CMake example with sub directories

To create a out-of-source build either in current dir or a another location:

mkdir build
cd build
cmake '/complete/path/to/source/'
make

#do not include CMakeLists.txt in the path above, point to the src directory
