cmake_minimum_required(VERSION 3.26)
project(Ing1_2023_2024_5_8 C)

set(CMAKE_C_STANDARD 11)

add_executable(Ing1_2023_2024_5_8
        main.c
        "Game Management/Timer.h"
        "Game Management/Timer.c"
        "Game Management/Score.h"
        "Game Management/Score.c"
        Player/Player.h
        Player/Player.c)

target_link_libraries(Ing1_2023_2024_5_8 -lmingw32 -lalleg44)