cmake_minimum_required(VERSION 2.6)

PROJECT (cpu)

include_directories(
	${PROJECT_SOURCE_DIR}/../common/
	${PROJECT_SOURCE_DIR}/../externals/gl3w/include	
)

add_library(cpu klt_cpu.cpp)