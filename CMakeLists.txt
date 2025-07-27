cmake_minimum_required(VERSION 3.24)
project(easing_functions)

set(CMAKE_CXX_STANDARD 17)

add_library(${PROJECT_NAME} SHARED easing.cpp)