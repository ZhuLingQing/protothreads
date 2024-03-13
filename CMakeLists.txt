project(protothreads)

add_library(${PROJECT_NAME} INTERFACE)

target_include_directories(${PROJECT_NAME} INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})

add_library(protothreads::protothreads ALIAS ${PROJECT_NAME}) 
