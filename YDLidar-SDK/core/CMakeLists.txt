cmake_minimum_required(VERSION 2.8)
include_directories(.)
include_directories( ${CMAKE_CURRENT_SOURCE_DIR})
subdirlist(SUBDIRS ${CMAKE_CURRENT_SOURCE_DIR})
foreach(subdir ${SUBDIRS})
    include_directories( ${CMAKE_CURRENT_SOURCE_DIR}/${subdir} )
    add_subdirectory(${subdir})
endforeach()
