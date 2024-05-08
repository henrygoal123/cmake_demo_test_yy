project(main_test)


add_subdirectory(process)
add_subdirectory(map)

add_executable(${PROJECT_NAME} main.cpp)

target_include_directories(${PROJECT_NAME} PUBLIC ${Process_Dir})
target_link_libraries(${PROJECT_NAME} PUBLIC process)

