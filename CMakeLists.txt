cmake_minimum_required (VERSION 3.11)
project(OpenGL_Demo2)

set(OUT_LIB "lib")
set(OUT_INCLUDE "include")

include_directories(${OUT_INCLUDE})
link_directories(${OUT_LIB})
LINK_LIBRARIES(glfw3)

# aux_source_directory(src ALL_SRCS)
# add_executable(demo2 ${ALL_SRCS})
# target_link_libraries(demo2 glfw3)

set(demo2_01_src "src/demo_01.cpp"
               "src/glad.c")
add_executable(demo2_01 ${demo2_01_src})


set(demo2_02_src "src/demo_02.cpp"
               "src/glad.c")
add_executable(demo2_02 ${demo2_02_src})


set(demo2_03_src "src/demo_03.cpp"
               "src/glad.c")
add_executable(demo2_03 ${demo2_03_src})

set(demo2_04_src "src/demo_04.cpp"
               "src/glad.c")
add_executable(demo2_04 ${demo2_04_src})

set(demo2_05_src "src/demo_05.cpp"
               "src/glad.c")
add_executable(demo2_05 ${demo2_05_src})


set(demo2_06_src "src/demo_06.cpp"
               "src/glad.c")
add_executable(demo2_06 ${demo2_06_src})


set(demo2_07_src "src/demo_07.cpp"
               "src/glad.c"
               "src/shader.h"
               "src/shader.cpp")
add_executable(demo2_07 ${demo2_07_src})



set(demo2_08_src "src/demo_08.cpp"
               "src/glad.c"
               "src/shader.h"
               "src/shader.cpp")
add_executable(demo2_08 ${demo2_08_src})


set(demo2_09_src "src/demo_09.cpp"
               "src/glad.c"
               "src/shader.h"
               "src/shader.cpp")
add_executable(demo2_09 ${demo2_09_src})


set(demo2_10_src "src/demo_10.cpp"
               "src/glad.c"
               "src/shader.h"
               "src/shader.cpp")
add_executable(demo2_10 ${demo2_10_src})


set(demo2_11_src "src/demo_11.cpp"
               "src/glad.c"
               "src/shader.h"
               "src/shader.cpp")
add_executable(demo2_11 ${demo2_11_src})

set(demo2_12_src "src/demo_12.cpp"
               "src/glad.c"
               "src/shader.h"
               "src/shader.cpp")
add_executable(demo2_12 ${demo2_12_src})


set(demo2_13_src "src/demo_13.cpp"
               "src/glad.c"
               "src/shader.h"
               "src/shader.cpp")
add_executable(demo2_13 ${demo2_13_src})

set(demo2_14_src "src/demo_14.cpp"
               "src/glad.c"
               "src/shader.h"
               "src/shader.cpp")
add_executable(demo2_14 ${demo2_14_src})


set(demo2_15_src "src/demo_15.cpp"
               "src/glad.c"
               "src/shader.h"
               "src/shader.cpp")
add_executable(demo2_15 ${demo2_15_src})


set(demo2_16_src "src/demo_16.cpp"
               "src/glad.c"
               "src/shader.h"
               "src/shader.cpp")
add_executable(demo2_16 ${demo2_16_src})


set(demo2_17_src "src/demo_17.cpp"
               "src/glad.c"
               "src/shader.h"
               "src/shader.cpp")
add_executable(demo2_17 ${demo2_17_src})

set(demo2_18_src "src/demo_18.cpp"
               "src/glad.c"
               "src/shader.h"
               "src/shader.cpp")
add_executable(demo2_18 ${demo2_18_src})

set(demo2_19_src "src/demo_19.cpp"
               "src/glad.c"
               "src/shader.h"
               "src/shader.cpp")
add_executable(demo2_19 ${demo2_19_src})

set(demo2_20_src "src/demo_20.cpp"
               "src/glad.c"
               "src/shader.h"
               "src/shader.cpp")
add_executable(demo2_20 ${demo2_20_src})

set(demo2_21_src "src/demo_21.cpp"
               "src/glad.c"
               "src/shader.h"
               "src/shader.cpp")
add_executable(demo2_21 ${demo2_21_src})

set(demo2_22_src "src/demo_22.cpp"
               "src/glad.c"
               "src/shader.h"
               "src/shader.cpp")
add_executable(demo2_22 ${demo2_22_src})


set(demo2_23_src "src/demo_23.cpp"
               "src/glad.c"
               "src/shader.h"
               "src/shader.cpp")
add_executable(demo2_23 ${demo2_23_src})

set(demo2_24_src "src/demo_24.cpp"
               "src/glad.c"
               "src/shader.h"
               "src/shader.cpp")
add_executable(demo2_24 ${demo2_24_src})

set(demo2_25_src "src/demo_25.cpp"
               "src/glad.c"
               "src/shader.h"
               "src/shader.cpp")
add_executable(demo2_25 ${demo2_25_src})

set(demo2_26_src "src/demo_26.cpp"
               "src/glad.c"
               "src/shader.h"
               "src/shader.cpp")
add_executable(demo2_26 ${demo2_26_src})


set(demo2_27_src "src/demo_27.cpp"
               "src/glad.c"
               "src/shader.h"
               "src/shader.cpp")
add_executable(demo2_27 ${demo2_27_src})

set(demo2_28_src "src/demo_28.cpp"
               "src/glad.c"
               "src/shader.h"
               "src/shader.cpp")
add_executable(demo2_28 ${demo2_28_src})