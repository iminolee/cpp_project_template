cmake_minimum_required(VERSION 3.11)
project(cpp_hello_world)

add_library(utils STATIC 
    include/utils/utils.hpp 
    src/utils.cpp
)

target_include_directories(utils PUBLIC include)

