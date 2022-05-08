cmake_minimum_required(VERSION 3.22)
project(xv)

set(CMAKE_CXX_STANDARD 14)

include_directories(algorithm/graph)

add_library(xv
        src/algorithm/graph/edge.cpp
        src/algorithm/graph/edge.h)
