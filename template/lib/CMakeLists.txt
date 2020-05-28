set(LIBHELLO_SRC cJSON.c)
add_library(CJSON SHARED ${LIBHELLO_SRC})
#install(FILES cJSON.h DESTINATION ${workspaceFolder}/build/lib)
#install(TARGETS CJSON LIBRARY DESTINATION build/src) #安装没有用，只能将.dll文件复制到exe文档一起去
