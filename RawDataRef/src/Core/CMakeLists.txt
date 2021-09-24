project(Core)

set(CMAKE_AUTOMOC ON)

add_subdirectory(GetDataComponent)

list(APPEND components "GetDataComponent")

message("Found the following components:")
foreach(component ${components})
  message("  ${component}")
endforeach()


