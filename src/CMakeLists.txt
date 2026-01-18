add_executable(thing)

target_compile_features(thing
    PRIVATE
    cxx_std_23
)

target_sources(thing
    PRIVATE
    main.cpp
)

target_link_libraries(thing
    PRIVATE
    glfw
    OpenGL::GL
)
