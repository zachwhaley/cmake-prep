cmake_minimum_required(VERSION 3.2)

# Create an executable named hello from hello.c
# The hello executable needs to link against the static library say
add_executable(hello hello.c)
target_link_libraries(hello say)
