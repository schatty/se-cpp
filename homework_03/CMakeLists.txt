cmake_minimum_required(VERSION 3.5)

project(03.guess_the_number)

add_executable(guess_the_number
	main.cpp
	argparse.h
	argparse.cpp
	guess_the_number.h
	guess_the_number.cpp
	records.h
	records.cpp
	agent.h
	tests.h
	tests.cpp
)

set_target_properties(guess_the_number PROPERTIES
    CXX_STANDARD 17
    CXX_STANDARD_REQUIRED ON
)
