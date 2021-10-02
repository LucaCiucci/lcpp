#[[ LCPP_NOTICE_BEGIN
LCPP_NOTICE_END ]]

################################################################
#                           INFO
################################################################
#[[

Apps folder, see ./README.md for info

]]

################################################################
#                    basic configurations
################################################################

################################################################
#                         App Project
################################################################

project("tmp_test" LANGUAGES CXX)

message("configuring ${PROJECT_NAME} project")

add_executable(${PROJECT_NAME})

target_sources(${PROJECT_NAME} PRIVATE
	"./main.cpp"
)