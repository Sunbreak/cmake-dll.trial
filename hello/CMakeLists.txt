add_library(hello SHARED hello.cpp)

target_include_directories(hello
                           INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}
                           )