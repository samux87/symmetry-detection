set(ENTRYPOINT ${SRC_DIRECTORY}/main.cpp)
add_executable(symmetry ${ENTRYPOINT} signature.cpp transformation.cpp)
target_link_libraries(symmetry igl::core igl::core igl::opengl_glfw ms-clustering flann_cpp)
