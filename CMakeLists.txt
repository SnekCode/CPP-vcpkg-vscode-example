cmake_minimum_required(VERSION 3.10)

project(TESTVCPKG LANGUAGES CXX)

add_executable(HelloWorld main.cpp)

find_package(fmt CONFIG REQUIRED)
target_link_libraries(HelloWorld PRIVATE fmt::fmt)

find_package(CURL REQUIRED)
target_link_libraries(HelloWorld PRIVATE CURL::libcurl)