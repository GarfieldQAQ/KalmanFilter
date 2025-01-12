cmake_minimum_required(VERSION 3.10)

# 工程名称和版本
project(KalmanFilter VERSION 1.0)

# 设置 C++ 标准
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# 指定源文件
add_executable(MyProject src/main.cpp)
