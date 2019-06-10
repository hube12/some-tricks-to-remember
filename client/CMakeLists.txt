include_directories(${CMAKE_SOURCE_DIR}/Common/) # so you can use the headers files inside common folder

add_executable(main main.cpp)
target_link_libraries(main util)