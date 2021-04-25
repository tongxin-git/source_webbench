cmake_minimum_required(VERSION 3.10)
project(webbench_1_5 C)

set(CMAKE_C_STANDARD 11)

add_executable(webbench_1_5
        socket.c
        webbench.c)
