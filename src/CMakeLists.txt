cmake_minimum_required (VERSION 3.19)
find_package(libsoundio CONFIG REQUIRED)
find_package(Vulkan REQUIRED)

add_executable (main "main/main.cpp")

target_link_libraries(main PRIVATE libsoundio::libsoundio libsoundio::libsoundio_shared)