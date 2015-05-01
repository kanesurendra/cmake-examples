cmake_minimum_required(VERSION 2.8.12)

#PROJECT([name][TYPE])- project with 'name' and TYPE C/CXX etc (case sensitive)
PROJECT(hello)

#ADD_EXECUTABLE([bin][src1 src2 ..])
ADD_EXECUTABLE(hello.o helloworld.c)
