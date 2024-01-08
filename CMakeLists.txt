cmake_minimum_required(VERSION 3.12)
project(gfx_foundation)

set(CMAKE_CXX_STANDARD 14)

add_executable(gfx_foundation src/main.cpp)

include_directories(dependencies/include)

add_library(glad dependencies/lib/glad.c)
add_library(glfw STATIC IMPORTED)
set_target_properties(glfw PROPERTIES IMPORTED_LOCATION "${CMAKE_CURRENT_SOURCE_DIR}/dependencies/lib/libglfw3.a")

target_link_libraries(gfx_foundation glad glfw)
