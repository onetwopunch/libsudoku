cmake_minimum_required (VERSION 2.8.12)

project (Sudoku)

include_directories(inc)
file(GLOB SOURCES "src/*.c" "test/*.c")

add_executable(test test/test.c)
