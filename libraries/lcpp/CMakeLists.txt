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

message("configuring ${CMAKE_PROJECT_NAME} library project")
add_library(CMAKE_PROJECT_NAME)