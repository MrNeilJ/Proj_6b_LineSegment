cmake_minimum_required(VERSION 3.6)
project(LineSegment)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp LineSegment.cpp LineSegment.hpp)
add_executable(LineSegment ${SOURCE_FILES})