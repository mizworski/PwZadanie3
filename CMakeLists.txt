cmake_minimum_required(VERSION 3.1)
project(PwZadanie3)

set(CMAKE_C_STANDARD 99)

set(CMAKE_C_FLAGS "-Werror -Wall -ansi -pedantic")

set(SOURCE_FILES err.c err.h)
add_executable(PwZadanie3 ${SOURCE_FILES} circuit.c circuit.h)