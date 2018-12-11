cmake_minimum_required(VERSION 3.12)

add_executable(hello hello.cpp)
target_compile_features(hello PRIVATE cxx_std_11)
