cmake_minimum_required(VERSION 3.5)
file(GLOB_RECURSE SOURCES "src/*.cpp")
add_library(ExampleLibrary SHARED ${SOURCES})