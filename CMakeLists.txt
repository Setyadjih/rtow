cmake_minimum_required(VERSION 3.10.0)
project(main)

set(CMAKE_CXX_STANDARD 11)

# Set C++ version and output directory
set(CMAKE_ARCHIVE_OUTPUT_DIRECTORY "${CMAKE_SOURCE_DIR}/bin/static libs")
set(CMAKE_LIBRARY_OUTPUT_DIRECTORY "${CMAKE_SOURCE_DIR}/bin")
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY "${CMAKE_SOURCE_DIR}/bin")

add_executable(${PROJECT_NAME} src/main.cpp)
