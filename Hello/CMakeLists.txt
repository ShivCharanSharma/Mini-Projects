cmake_minimum_required(VERSION 2.4)
project(Hello)

#Bring the headers, such as Student.h into the project
include_directories(include)
 
# file(GLOB...) allows for wildcard additions:
file(GLOB SOURCES "src/*.c")
 
add_executable(app ${SOURCES})
