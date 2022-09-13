cmake_minimum_required(VERSION 3.23)
project(CmakeProjectClion)

set(CMAKE_CXX_STANDARD 14)

add_executable(CmakeProjectClion main.cpp)
target_link_libraries (CmakeProjectClion -lopengl32 -lfreeglut -lglu32)