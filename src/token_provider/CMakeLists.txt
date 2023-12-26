cmake_minimum_required(VERSION 3.10)

project(trustauthority_token_provider)

add_library(${PROJECT_NAME}
    token_provider.c
)

target_include_directories(${PROJECT_NAME} PRIVATE
    ../../include
    ../log
)
