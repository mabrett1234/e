cmake_minimum_required(VERSION 4.1)
project(e C)

set(CMAKE_C_STANDARD 11)

include_directories(Inc)
include_directories(Src)

add_executable(e Inc/e.h Src/e.c main.c)
