# For more information about using CMake with Android Studio, read the
# documentation: https://d.android.com/studio/projects/add-native-code.html

# Sets the minimum version of CMake required to build the native library.

cmake_minimum_required(VERSION 3.4.1)



ADD_SUBDIRECTORY(${PROJECT_SOURCE_DIR}/helloopencv)

ADD_SUBDIRECTORY(${PROJECT_SOURCE_DIR}/floodfill)

ADD_SUBDIRECTORY(${PROJECT_SOURCE_DIR}/blindmark)

ADD_SUBDIRECTORY(${PROJECT_SOURCE_DIR}/yuv)