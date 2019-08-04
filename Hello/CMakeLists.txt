cmake_minimum_required(VERSION 2.4)
include_directories(include)
project(Hello)

add_executable(app src/main.c include/helloworld.h)
