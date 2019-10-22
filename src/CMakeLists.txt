set(nje_c_SRCS
)

set(nje_h_SRCS
)

include_directories(${PROJECT_SOURCE_DIR}/src)
include_directories(
#	${fmt_INCLUDE_DIRS}
)

add_executable(nje ${nje_c_SRCS} ${nje_h_SRCS})
target_link_libraries(nje
)
