cmake_minimum_required(VERSION 3.25.0)
project(CppPrimer VERSION 1.0)

# specify the C++ standard
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)
# set output executable file directory
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)

include_directories("${PROJECT_SOURCE_DIR}/includes/")
include_directories("${PROJECT_SOURCE_DIR}/src/")

add_executable(CppPrimer "./src/chapter02/p42_01.cpp")
