cmake_minimum_required(VERSION 2.8)
project( FindContours )
find_package( OpenCV REQUIRED )
add_executable( FindContours FindContours.cpp )
target_link_libraries( FindContours ${OpenCV_LIBS} )
