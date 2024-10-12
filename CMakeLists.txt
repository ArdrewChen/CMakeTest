cmake_minimum_required(VERSION 3.10)
project(CmakeTest)

set(LIB_PATH ${CMAKE_CURRENT_SOURCE_DIR}/lib)
set(BIN_PATH ${CMAKE_CURRENT_SOURCE_DIR}/bin)
set(HEAD_PATH ${CMAKE_CURRENT_SOURCE_DIR}/include)

set(CALC_LIB calc)
set(SORT_LIB sort)

set(EXE_NAME_1 test1)
set(EXE_NAME_2 test2)

# 添加子目录
add_subdirectory(calc)
add_subdirectory(sort)
add_subdirectory(test1)
add_subdirectory(test2)
