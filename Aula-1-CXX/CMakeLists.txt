cmake_minimum_required(VERSION 3.5)

project(Aula1)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(${PROJECT_NAME} WIN32 MACOSX_BUNDLE main.cxx)
set_target_properties(${PROJECT_NAME} PROPERTIES FOLDER "Aula-1-CXX")
