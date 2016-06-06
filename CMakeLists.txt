cmake_minimum_required(VERSION 3.5)
project(word2vec)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES trunk/compute-accuracy.c trunk/word2phrase.c trunk/word-analogy.c trunk/word2vec.c trunk/distance.c)
add_executable(word2vec ${SOURCE_FILES})