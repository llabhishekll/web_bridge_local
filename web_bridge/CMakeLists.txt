cmake_minimum_required(VERSION 2.8.3)
project(web_bridge)

find_package(catkin REQUIRED COMPONENTS
  genmsg
  geometry_msgs
  nav_msgs
  rospy
  std_msgs
  actionlib_msgs
  actionlib
)

add_action_files(
    DIRECTORY
    action
    FILES
    ExampleAction.action
    WaypointAction.action
)

generate_messages(
    DEPENDENCIES
    actionlib_msgs
    geometry_msgs
)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES web_bridge
#  CATKIN_DEPENDS geometry_msgs nav_msgs rospy std_msgs
#  DEPENDS system_lib
)

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)