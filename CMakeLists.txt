cmake_minimum_required(VERSION 2.8)
project(hw1)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++14 -Wall -Wextra -Wconversion -pedantic")

set(SRC_LIST main.cpp)

add_executable(main ${SRC_LIST})
