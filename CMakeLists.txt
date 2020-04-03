cmake_minimum_required(VERSION 3.16)

project(sdl-cat LANGUAGES C)

find_package(SDL2 CONFIG REQUIRED)

add_executable(cat cat.c)
target_link_libraries(cat SDL2::SDL2)
