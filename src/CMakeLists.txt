file(GLOB_RECURSE SOURCES "*.cpp")

add_library(acrobat-plugin-cmake-template SHARED ${SOURCES})
set_target_properties(acrobat-plugin-cmake-template PROPERTIES
    OUTPUT_NAME "acrobat-plugin-cmake-template"
    PREFIX      ""
    SUFFIX      ".api"
)
target_link_libraries(acrobat-plugin-cmake-template PRIVATE acrobat-sdk)