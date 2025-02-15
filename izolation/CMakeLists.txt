cmake_minimum_required(VERSION 3.20)

add_executable(izolation izolation.c)

target_link_libraries(izolation glad glfw stb)
