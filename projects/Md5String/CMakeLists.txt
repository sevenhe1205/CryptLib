SET( MODULE_NAME Md5String )

add_executable( ${MODULE_NAME}
    Md5String.c )
target_link_libraries( ${MODULE_NAME}
    CryptLib )

install(TARGETS ${MODULE_NAME} DESTINATION .)
