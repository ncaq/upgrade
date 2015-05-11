cmake_minimum_required(VERSION 2.8)

project(upgrade)

install(PROGRAMS src/git-pull-all    DESTINATION bin)
install(PROGRAMS src/upgrade         DESTINATION bin)
install(PROGRAMS src/upgrade-by-root DESTINATION bin)
