cmake_minimum_required(VERSION 2.8.3)
project(asv_bringup)

find_package(catkin REQUIRED 
	asv_navigation
)

catkin_package(
	CATKIN_DEPENDS asv_navigation
)