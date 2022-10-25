cmake_minimum_required(VERSION 3.15.0)
project(main)
set(CMAKE_CXX_STANDARD 17)

file(GLOB SOURCE src/*.cpp main.cpp)

add_executable(${CMAKE_PROJECT_NAME} ${SOURCE})

include_directories(include)

