cmake_minimum_required(VERSION "3.21.3")

project(FUN VERSION 1.0.0)

set(CMAKE_CXX_STANDARD 17)
file(GLOB SOURCE_FILES src/*.cpp)

add_executable(fun ${SOURCE_FILES})
