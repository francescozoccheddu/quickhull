cmake_minimum_required (VERSION 3.8)

project ("quickhull")

add_library (quickhull INTERFACE)
set_property (TARGET quickhull PROPERTY CXX_STANDARD 11)
target_include_directories (quickhull INTERFACE "include")

add_subdirectory ("tests")