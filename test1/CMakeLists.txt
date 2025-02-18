cmake_minimum_required(VERSION 3.10)
project(CALCTEST)
aux_source_directory(./ SRC)
include_directories(${HEAD_PATH})
link_directories(${LIB_PATH})
link_libraries(${CALC_LIB})
set(EXECUTABLE_OUTPUT_PATH ${BIN_PATH}) # 设置可执行文件输出路径
add_executable(${EXE_NAME_1} ${SRC})
