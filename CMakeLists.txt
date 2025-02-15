cmake_minimum_required(VERSION 3.20)

project(izolation)

add_subdirectory(thirdparty/glfw)
add_subdirectory(thirdparty/glad)
# add_subdirectory(thirdparty/glm)
add_subdirectory(thirdparty/stb)
add_subdirectory(izolation)

target_include_directories(izolation PUBLIC $(CMAKE_CURRENT_SOURCE_DIR)/thirdparty/glfw/include)
target_include_directories(izolation PUBLIC $(CMAKE_CURRENT_SOURCE_DIR)/thirdparty/glad/include)
# # target_include_directories(izolation PUBLIC $(CMAKE_CURRENT_SOURCE_DIR)/thirdparty/glm/glm)
target_include_directories(izolation PUBLIC $(CMAKE_CURRENT_SOURCE_DIR)/thirdparty/stb/include)
