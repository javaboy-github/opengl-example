# CMakeのバージョンを設定
cmake_minimum_required(VERSION 2.8)
# プロジェクト名と使用する言語を設定
project(opengl-example CXX)
# a.outという実行ファイルをmain.cppとhello.cppから作成
add_executable(a.out src/main.cpp)