cmake_minimum_required(VERSION 3.15)
project(time)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)


add_library(sea_block SHARED
        public.h
        sea_block.c
        sea_block.h
        sea_block_data.c
        sea_block_data.h
        sea_block_index.c
        sea_block_index.h
        sea_block_offset.c
        sea_block_offset.h
        sea_block_record.c
        sea_block_record.h
        utils.c
        utils.h)

# add_executable(test
 #       block/test.c)