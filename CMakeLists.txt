cmake_minimum_required(VERSION 3.28)
project(NetflixOrYoutube)

set(CMAKE_CXX_STANDARD 23)

add_executable(NetflixOrYoutube main.cpp
        Classes/User.cpp
        Classes/User.h
        Classes/Video.cpp
        Classes/Video.h
        Classes/Comment.cpp
        Classes/Comment.h
        Classes/Review.cpp
        Classes/Review.h
        Classes/Playlist.cpp
        Classes/Playlist.h)
