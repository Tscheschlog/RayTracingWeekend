cmake_minimum_required(VERSION 3.0)

# Set the project name
project(code-raytrace)

# Set the C++ standard to C++11
set(CMAKE_CXX_STANDARD 17)

# Add the executable and specify the source files
add_executable(code-raytrace main.cpp vec3.h color.h hittable.h sphere.h hittable_list.h rtweekend.h camera.h material.h)
