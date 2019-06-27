cmake_minimum_required(VERSION 3.13)
project(rbtree)

add_executable(rbtree main.c rb-tree.c rb-tree.h unit.c unit.h config_header.h rb-tree-test.h)