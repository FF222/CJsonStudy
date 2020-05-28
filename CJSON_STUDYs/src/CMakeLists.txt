cmake_minimum_required(VERSION 3.5)

include_directories(${workspaceFolder}/build/lib)
# include_directories(${workspaceFolder}/lib)

add_executable(main main.cpp)

target_link_libraries(main CJSON) # 使用libCJSON.so需要加入地址