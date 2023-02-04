cmake_minimum_required(VERSION 3.0)
project(hello)

set(CMAKE_CXX_STANDARD 17)

include_directories(.)

add_executable(hello main.cpp)
target_link_libraries(hello "-lpthread")