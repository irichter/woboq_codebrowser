cmake_minimum_required(VERSION 3.1)

include(GNUInstallDirs)

add_subdirectory(generator)
add_subdirectory(indexgenerator)

install(DIRECTORY data
    DESTINATION ${CMAKE_INSTALL_DATADIR}/woboq
)
