# 'glfw' library target
add_subdirectory(glfw/)

# 'glad' library target
# needs python-jinja installed
add_subdirectory(glad/cmake/)
glad_add_library(glad REPRODUCIBLE API gl:core=3.3)
