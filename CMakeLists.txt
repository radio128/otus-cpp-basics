cmake_minimum_required(VERSION 3.5)

project(01.otus_cpp_basics)

add_executable(otus_cpp_basics
    hello_world.cpp
    example.cpp
    example.h
        move_me_out.h move_me_out.cpp)

set_target_properties(otus_cpp_basics PROPERTIES
    CXX_STANDARD 17
    CXX_STANDARD_REQUIRED ON
)