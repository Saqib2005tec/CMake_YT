cmake_minimum_required(VERSION 3.10)
project(HelloApp
    VERSION 0.0.1
    DESCRIPTION "My First CMake App"
    LANGUAGES C CXX)   
add_executable(hello_app_bin main.cpp)
target_compile_features(hello_app_bin PRIVATE cxx_std_20)
 