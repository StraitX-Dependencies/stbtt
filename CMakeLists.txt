cmake_minimum_required(VERSION 3.10)

project(stbtt)

add_library(stbtt STATIC 
	"./sources/tt.c"
)

target_include_directories(stbtt 
	PUBLIC "./include"
)
