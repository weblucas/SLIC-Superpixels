
include_directories(${CMAKE_CURRENT_SOURCE_DIR})

add_executable(test_sic
slic.cpp
test_slic.cpp
)



find_package(OpenCV REQUIRED)
target_link_libraries(test_sic ${OpenCV_LIBS})

