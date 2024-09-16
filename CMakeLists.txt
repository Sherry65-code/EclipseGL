cmake_minimum_required(VERSION 3.3)

project(EclipseGL)

add_subdirectory(imports/glfw)

include_directories(imports/glfw/include)

add_executable(EclipseGL src/test.c)
