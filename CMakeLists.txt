cmake_minimum_required(VERSION 4.0)

project(learnopengl)

find_package(OpenGL REQUIRED)

add_subdirectory(external/glfw)

add_subdirectory(src/)
