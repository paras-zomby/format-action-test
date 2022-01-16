cmake_minimum_required(VERSION 3.20)

project(Action_Test)

set(CMAKE_CXX_STANDARD 17)

#find_package(OpenCV REQUIRED)
#
#include_directories(${OpenCV_INCLUDE_DIRS})
#link_libraries(${OpenCV_LIBS})

add_executable(action main.cpp)
