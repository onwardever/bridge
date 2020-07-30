cmake_minimum_required(VERSION 3.13)
project(bridge)

set(CMAKE_CXX_STANDARD 11)

add_executable(bridge main.cpp ann/src/test.h dsa/src/test.h)