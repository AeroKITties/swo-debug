
cmake_minimum_required(VERSION 3.22)

# Create a library from the sources
add_library(swo-debug STATIC
    debug.cpp
    debug.hpp
    swo.cpp
    swo.hpp
)

# Optionally, add include directories
target_include_directories(swo-debug PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})