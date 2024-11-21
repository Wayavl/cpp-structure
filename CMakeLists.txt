cmake_minimum_required(VERSION 3.11)
project(testing)

# Set
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Encuentra Librerias


# Ejecutable
add_executable(main src/Main.cpp src/Class1/Class1.cpp)

# include folder
target_include_directories(main PRIVATE ${CMAKE_SOURCE_DIR}/include)


# Link de librerias

