cmake_minimum_required(VERSION 3.20)
project(my_tiny_renderer)

set(CMAKE_CXX_STANDARD 11)

add_executable(my_tiny_renderer main.cpp tgaimage.cpp model.cpp)
