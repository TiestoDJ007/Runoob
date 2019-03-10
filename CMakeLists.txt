cmake_minimum_required(VERSION 3.13)
project(Runoob)

set(CMAKE_CXX_STANDARD 14)

add_executable(Runoob main.cpp Decorating.cpp)

add_executable(Decorating Decorating.cpp)