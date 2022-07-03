cmake_minimum_required(VERSION 3.8)

project(glad C)

add_library(${PROJECT_NAME} STATIC  ${CMAKE_CURRENT_SOURCE_DIR}/src/glad.c)

target_include_directories(${PROJECT_NAME} PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include)