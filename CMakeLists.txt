include_directories(lib)
add_executable(test-remotery sample/sample.c lib/Remotery.c)
target_link_libraries(test-remotery m pthread)
