cmake_minimum_required(VERSION 2.8)

#PROJECT([name][TYPE])- project with 'name' and TYPE C/CXX etc (case sensitive)
project(HELLO)

#add_subdirectory(source_dir [binary_dir]
#                 [EXCLUDE_FROM_ALL])
# add sub directory to the build which contains source CMakeLists.txt and source code.
# EXCLUDE_FROM_ALL targets in the subdirectory will not be included in the ALL target of the parent directory by default, and will be excluded from IDE project files
add_subdirectory(Hello)
add_subdirectory(Test)
