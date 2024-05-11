cmake_minimum_required(VERSION 3.10)

# 定义静态库
add_library(kernel_list INTERFACE)

# 添加头文件搜索路径
target_include_directories(kernel_list INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})
