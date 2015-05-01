cmake_minimum_required(VERSION 2.8)

#includes the directories specified
include_directories(${HELLO_SOURCE_DIR}/Hello)

#ADD_EXECUTABLE([bin][src1 src2 ..])
add_executable(helloworld test)

#Specify libraries / flags to use when linking a given target
#target_link_libraries(<target> [item1 item2 ..])
target_link_libraries(helloworld Hello)
