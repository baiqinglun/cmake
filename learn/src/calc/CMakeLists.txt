# 使用指定的源文件将库添加到项目中。
add_library(addition STATIC add.cpp)
add_library(sub SHARED sub.cpp)

install(TARGETS addition DESTINATION lib)
install(FILES add.h DESTINATION include)