cmake_minimum_required(VERSION 3.12)
project(gfx_foundation)

set(CMAKE_CXX_STANDARD 14)

find_package(OpenGL REQUIRED)

add_subdirectory(libraries/glfw-3.3.9)
include_directories(libraries/glfw-3.3.9/include)

add_executable(gfx_foundation main.cpp)

target_link_libraries(gfx_foundation glfw ${GLFW_LIBRARIES})
