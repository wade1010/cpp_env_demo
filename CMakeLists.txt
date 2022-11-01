#规定cmake的最低版本要求
cmake_minimum_required (VERSION 3.10)
#设置c++编译器
set(CMAKE_CXX_COMPILER "g++")
#项目的名称，可以和文件夹名称（HELLO）不同
project(MYSWAP)
#设置可执行文件输出路径
set(EXECUTABLE_OUTPUT_PATH  ${PROJECT_SOURCE_DIR}/bin)
add_executable(my_cmake_swap main.cpp swap.cpp)