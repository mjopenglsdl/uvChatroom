set(CORE_SOURCE base.cpp user.h message.h)

add_library(chatCore ${CORE_SOURCE})

target_include_directories(chatCore PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})