#[[ LCPP_NOTICE_BEGIN
LCPP_NOTICE_END ]]

################################################################
#                           INFO
################################################################
#[[

Top level CMake project, see README.md for info

]]

################################################################
#                    basic configurations
################################################################

cmake_minimum_required (VERSION 3.20)

################################################################
#                        MAIN PROJECT
################################################################
# main project definition

project("lcpp" VERSION 0.0
    DESCRIPTION "A set of tools aimed to simplify C++ scripting and scientific programming"
    LANGUAGES CXX
)
message("configuring top level ${CMAKE_PROJECT_NAME} project")

# add_subdirectory("cmake")

################################
#     SUBPROJECTS / SUBDIRS
################################

add_subdirectory("libraries")
add_subdirectory("apps")