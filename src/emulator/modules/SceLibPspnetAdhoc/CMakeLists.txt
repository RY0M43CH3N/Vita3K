add_library(SceLibPspnetAdhoc STATIC include/SceLibPspnetAdhoc/exports.h src/ScePspnetAdhoc.cpp)
target_include_directories(SceLibPspnetAdhoc PUBLIC include)
target_link_libraries(SceLibPspnetAdhoc PRIVATE module)
