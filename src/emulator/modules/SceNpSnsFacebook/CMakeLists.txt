add_library(SceNpSnsFacebook STATIC include/SceNpSnsFacebook/exports.h src/SceNpSnsFacebook.cpp)
target_include_directories(SceNpSnsFacebook PUBLIC include)
target_link_libraries(SceNpSnsFacebook PRIVATE module)
