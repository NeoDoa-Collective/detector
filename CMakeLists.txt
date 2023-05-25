cmake_minimum_required(VERSION 3.26.4)

project(detector)

add_library(detector INTERFACE)
target_sources(detector PRIVATE
	"detector.hpp"
)
target_include_directories(detector INTERFACE .)