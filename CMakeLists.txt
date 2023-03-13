cmake_minimum_required(VERSION 3.24)
project(clox)

set(CMAKE_CXX_STANDARD 17)

add_executable(clox main.cpp common.h chunk.h chunk.cpp memory.h memory.cpp debug.h debug.cpp value.h value.cpp)
