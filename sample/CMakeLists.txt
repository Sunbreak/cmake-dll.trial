include_directories("${CMAKE_CURRENT_SOURCE_DIR}/../hello")

link_directories("${CMAKE_CURRENT_BINARY_DIR}/../hello/Debug")

add_executable(sample main.cpp)

target_link_libraries(sample hello)