project(dobra-espacial)
add_executable(${PROJECT_NAME} camera.cpp main.cpp model.cpp openglwindow.cpp
                               trackball.cpp)
enable_abcg(${PROJECT_NAME})
