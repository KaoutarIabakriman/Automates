cmake_minimum_required(VERSION 3.27)
project(automate C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(automate
        main.c)
