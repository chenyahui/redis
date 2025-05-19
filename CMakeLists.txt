cmake_minimum_required(VERSION 3.10)
project(redis C)

include_directories(src)

file(GLOB SOURCES "src/*.c")

add_executable(redis ${SOURCES})

