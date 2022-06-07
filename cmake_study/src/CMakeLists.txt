add_executable(
hello_world
hello.c
main.c
)

target_include_directories(hello_world PUBLIC ${CMAKE_SOURCE_DIR}/include)

target_link_libraries(hello_world PUBLIC lib_hello_world)
