cmake_minimum_required(VERSION 3.24)
project(learning_opengl)

set(CMAKE_CXX_STANDARD 20)


include_directories(./include)

add_executable(learning_opengl src/main.cpp)

target_link_libraries(learning_opengl -lglfw -lGL -lX11)
