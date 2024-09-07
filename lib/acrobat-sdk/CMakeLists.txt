add_library(acrobat-sdk STATIC ${CMAKE_CURRENT_SOURCE_DIR}/Headers/API/PIMain.c)
target_include_directories(acrobat-sdk
    PUBLIC
    ${CMAKE_CURRENT_SOURCE_DIR}/Headers/API
    ${CMAKE_CURRENT_SOURCE_DIR}/Headers/SDK
)
