cmake_minimum_required(VERSION 3.5)

project(ela LANGUAGES C)

set(SOURCES src/ela.c src/ela_libevent.c)

add_library(ela
    ${SOURCES}
    )

target_include_directories(ela PUBLIC include)