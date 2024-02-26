cmake_minimum_required(VERSION 3.27)
project(lzw_hash C)

set(CMAKE_C_STANDARD 11)

add_executable(lzw_hash main.c
        gtbitio.c
        gtbitio.h
        utypes.h
)
