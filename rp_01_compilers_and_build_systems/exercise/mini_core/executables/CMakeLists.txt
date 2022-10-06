# TODO compile executable that will be run  
add_executable(many_object_in_stack_example many_object_in_stack_example.cpp)     #step 3:add source files in this directory

#step 8: link
target_link_libraries(many_object_in_stack_example
core_library)