cmake_minimum_required(VERSION 3.25)
project(LearnMPI C)

set(CMAKE_C_STANDARD 11)

include_directories("C:\\Program Files (x86)\\Microsoft SDKs\\MPI\\Include")
link_directories("C:\\Program Files (x86)\\Microsoft SDKs\\MPI\\Lib\\x64")

add_executable(LearnMPI main.c)
target_link_libraries(LearnMPI msmpi)