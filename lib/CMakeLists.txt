cmake_minimum_required(VERSION 3.2)

# Create a static library named libsay.a from say.c and say.h
add_library(say STATIC say.c)
target_include_directories(say PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
