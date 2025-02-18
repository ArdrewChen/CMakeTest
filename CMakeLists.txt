cmake_minimum_required(VERSION 3.10)
project(CmakeTest)

# 设置项目全局存储目录
set(LIB_PATH ${CMAKE_CURRENT_SOURCE_DIR}/bin)       # 库存储目录
set(BIN_PATH ${CMAKE_CURRENT_SOURCE_DIR}/bin)       # 可执行文件存储目录
set(HEAD_PATH ${CMAKE_CURRENT_SOURCE_DIR}/include)  # 头文件存储目录

# 设置库名称
set(CALC_LIB calc)
set(SORT_LIB sort)

# 设置可执行文件名称
set(EXE_NAME_1 test1)
set(EXE_NAME_2 test2)

# 添加子目录
add_subdirectory(calc)
add_subdirectory(sort)
add_subdirectory(test1)
add_subdirectory(test2)
