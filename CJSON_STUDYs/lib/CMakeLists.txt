set(LIBHELLO_SRC cJSON.c)
add_library(CJSON SHARED ${LIBHELLO_SRC})
#install(FILES cJSON.h DESTINATION ${workspaceFolder}/build/lib)
