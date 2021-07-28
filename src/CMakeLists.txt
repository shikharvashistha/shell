cmake_minimum_required(VERSION 3.20.0)

project (shell)

add_executable(a shell.cpp) 

enable_testing()

add_test(test a) 