cmake_minimum_required(VERSION 3.15)
project(graph)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
link_directories("/usr/local/lib")
link_libraries(sea_block)
link_libraries(block_word)


add_library(graph SHARED
        graph_data.c
        graph.h graph.c version.h graph_data.h)
