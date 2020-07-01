# step 1
# 指定cmake的版本
cmake_minimum_required(VERSION 3.10)

# 设置项目名称
project(Turtorial)

# 添加可执行文件
add_executable(Tutorial tutorial.cxx)
# 其中 tutorial.cxx 为计算一个数值的平方根源码