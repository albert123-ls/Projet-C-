cmake_minimum_required(VERSION 3.0)

# set the project name
project(find_motive)

# add the lib
#add_library(mysource SHARED sources.cpp)

# add the executable
add_executable(main main.cpp find_motive.cpp)

# do not forget to link
#target_link_libraries(main mysource)

#target_link_libraries(main mysource_2)
