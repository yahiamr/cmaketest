add_library(yaya STATIC 
yaya.cpp
)
target_include_directories(yaya PRIVATE ${CMAKE_CURRENT_SOURCE_DIR}/../includes)
