set(LIB_NAME segger_rtt_lib)
message(STATUS "Build: ${LIB_NAME}")
include_directories("src/inc")
file(GLOB_RECURSE LIB_SOURCES "src/*.*")
add_library(${LIB_NAME} STATIC ${LIB_SOURCES})