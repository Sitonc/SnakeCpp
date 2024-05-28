cmake_minimum_required(VERSION 3.28)
project(SnakeCpp)

set(CMAKE_CXX_STANDARD 20)

add_executable(SnakeCpp src/main.cpp
        src/GameField.h
        src/GameField.cpp)
