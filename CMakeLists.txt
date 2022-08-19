cmake_minimum_required(VERSION 3.16)

project(private_example C)

add_executable(example src/main.c src/public.c src/private.c)
target_include_directories(example PUBLIC include src)
