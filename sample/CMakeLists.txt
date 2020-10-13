add_executable(sample main.cpp)

target_include_directories(sample PRIVATE "${CMAKE_CURRENT_SOURCE_DIR}/sdk/include")

find_library(helloLib hello "${CMAKE_CURRENT_SOURCE_DIR}/sdk/lib")
target_link_libraries(sample ${helloLib})