cmake_minimum_required(VERSION 3.11)
project(printing_hello_world)

add_executable(printing_hello_world main.cpp)

target_link_libraries(printing_hello_world PRIVATE utils)
