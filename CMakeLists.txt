cmake_minimum_required(VERSION 3.10)

project(Chatlab VERSION 0.0.1 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_subdirectory(app)
add_subdirectory(engine)
