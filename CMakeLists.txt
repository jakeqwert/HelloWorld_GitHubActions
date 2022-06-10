cmake_minimum_required(VERSION 3.21)
project(HelloWorld_GitHubActions)

set(CMAKE_CXX_STANDARD 14)

add_executable(HelloWorld_GitHubActions main.cpp)

install(TARGETS HelloWorld_GitHubActions)

enable_testing()
add_test(NAME HelloWorld_GitHubActions COMMAND HelloWorld_GitHubActions)
