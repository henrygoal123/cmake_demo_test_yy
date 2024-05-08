cmake_minimum_required(VERSION 3.0.0)
project(demo_test)
set(CMAKE_CXX_STANDARD 11)


set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${PROJECT_SOURCE_DIR}/bin)

set(Process_Dir ${CMAKE_SOURCE_DIR}/src/process)
set(Map_Dir ${CMAKE_SOURCE_DIR}/src/map)
add_subdirectory(src)