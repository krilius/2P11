#Defined executable
add_executable(
	2P11
	./main.cpp
)

#Find all libraries
find_package(SFML 2.2 COMPONENTS system window graphics audio REQUIRED)


#Include "Includes" and "Libraries"
include_directories(${SFML_INCLUDE_DIR})
target_link_libraries(2P11 ${SFML_LIBRARIES})

message("${SFML_LIBRARIES}")
