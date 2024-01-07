cmake_minimum_required(VERSION 3.11-3.18)


project(encrypt)

add_library(encrypt
    src/encrypt.cpp
    src/base64.cpp
    src/vigenere.cpp
)

target_include_directories(${PROJECT_NAME}
    PUBLIC ${PROJECT_SOURCE_DIR}/include)
