cmake_minimum_required(VERSION 3.2)
project(create_window)
link_directories(../00.common/lib)
include_directories(../00.common/include)

add_executable(create_window application.cpp)
target_link_libraries(create_window glfw3)