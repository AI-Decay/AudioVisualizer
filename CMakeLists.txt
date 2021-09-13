# CMakeList.txt : Top-level CMake project file, do global configuration
# and include sub-projects here.
#
cmake_minimum_required (VERSION 3.19)
set (CMAKE_CXX_STANDARD 17)

list(APPEND CMAKE_PREFIX_PATH "D:/vcpkg/packages")
list(APPEND CMAKE_PREFIX_PATH "C:/VulkanSDK/1.2.189.1")

project ("AudioVisualizer")

# Include sub-projects.
add_subdirectory ("src")
