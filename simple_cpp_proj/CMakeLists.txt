cmake_minimum_required(VERSION 3.2.0)
project(myproject_dir)

#header path
include_directories(include)

file(GLOB SOURCES "src/*.cpp")

add_executable( mainrun ${SOURCES})
