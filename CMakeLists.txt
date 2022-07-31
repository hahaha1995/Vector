cmake_minimum_required(VERSION 3.20)
project(Vector)

set(CMAKE_CXX_STANDARD 20)

add_executable(Vector main.cpp cmake-build-debug/Vector.cpp cmake-build-debug/Vector.h)
