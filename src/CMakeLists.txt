add_executable(soemdspexe Main.cpp)

target_link_libraries(soemdspexe PRIVATE soemdsp)

set_property(TARGET soemdspexe PROPERTY FOLDER "Apps")
