cmake_minimum_required(VERSION 3.10.0)

project(cmaketest)

add_executable(gawad main.cpp)

include_directories(${PROJECT_SOURCE_DIR}/includes)
add_subdirectory(src)

target_link_libraries(gawad PRIVATE yaya)
#link_libraries