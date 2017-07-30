cmake_minimum_required(VERSION 3.7)
project(at_home)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        String.cpp
        String.h
        w9_home.cpp)

add_executable(at_home ${SOURCE_FILES})