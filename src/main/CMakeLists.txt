include_directories(${FOO_INCLUDE_DIR}/include)

add_executable(bar c++/main.cpp)
link_target_libraries(bar foo)

install(TARGETS bar
    DESTINATION bin
)
