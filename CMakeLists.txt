cmake_minimum_required(VERSION 3.12)
project(pendu C)
find_package(SDL2 REQUIRED)
include_directories(${SDL2_INCLUDE_DIRS})
set(CMAKE_C_STANDARD 99)

add_executable(pendu main.c)
target_link_libraries(SDL2Test ${SDL2_LIBRARIES})
