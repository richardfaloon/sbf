add_subdirectory (replier)
add_subdirectory (requester)

if(NOT WIN32)
	add_subdirectory (connector)
endif()
add_subdirectory (publisher)
add_subdirectory (subscriber)
add_subdirectory (queue)
