add_library(lib_hello_world
STATIC
lib_hello.c)

target_include_directories(lib_hello_world PUBLIC ${CMAKE_SOURCE_DIR}/include)

target_compile_options(lib_hello_world PRIVATE -Wall)

