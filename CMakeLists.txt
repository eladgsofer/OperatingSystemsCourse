cmake_minimum_required(VERSION 3.17.3)
project(OperatingSystems C)

set(CMAKE_C_STANDARD 11)
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -pthread")
add_executable(OperatingSystems
        main.c)
