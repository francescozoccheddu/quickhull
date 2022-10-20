cmake_minimum_required (VERSION 3.8)

add_executable (quickhull-tests 
	"QuickHullTests.cpp"
	"main.cpp"
)
set_property (TARGET quickhull-tests PROPERTY CXX_STANDARD 11)
target_link_libraries (quickhull-tests PUBLIC quickhull)
