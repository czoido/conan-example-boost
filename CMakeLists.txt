cmake_minimum_required(VERSION 3.15)
project(example)

find_package(Boost REQUIRED)

add_executable(${PROJECT_NAME} src/main.cpp)
target_link_libraries(${PROJECT_NAME} Boost::boost)
