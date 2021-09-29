#[[ LCPP_NOTICE_BEGIN
LCPP_NOTICE_END ]]

################################################################
#                           INFO
################################################################
#[[

lcpp library folder, see ./README.md for info

]]

################################################################
#                    basic configurations
################################################################

################################################################
#                          PROJECT
################################################################

project("lcpp" VERSION 0.0
    DESCRIPTION "lcpp main library project"
    LANGUAGES CXX
)

message("configuring ${PROJECT_NAME} library project")

add_library(${PROJECT_NAME} SHARED)

target_sources(${PROJECT_NAME} PRIVATE "src/tmp.cpp")