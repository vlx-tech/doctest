cmake_minimum_required(VERSION 3.0)

fips_begin_lib(doctest)

    include_directories(../doctest)
    fips_files(empty.cpp)
    fips_dir(../doctest GROUP .)
    fips_files(doctest.h)

fips_end_lib()
