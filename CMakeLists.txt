
file(GLOB app_sources "src/*.c")


idf_component_register(SRCS ${app_sources} INCLUDE_DIRS "src/")

component_compile_options(-Wno-error=misleading-indentation)
