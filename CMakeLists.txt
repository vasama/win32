cmake_minimum_required(VERSION 3.16)

project(win32)

add_library(win32 INTERFACE)
target_include_directories(win32
	INTERFACE
		include
)
