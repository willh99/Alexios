cmake_minimum_required(VERSION 3.23)

project(alexios VERSION 0.0.1 DESCRIPTION "Local Speech Recognition")

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)

add_executable(main src/main.cpp)