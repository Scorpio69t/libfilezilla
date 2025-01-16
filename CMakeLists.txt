cmake_minimum_required(VERSION 3.18)
project(libfilezilla)

set(CMAKE_CXX_STANDARD 17)

include_directories(include)

add_library(filezilla SHARED library.cpp)
