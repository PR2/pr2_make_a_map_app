cmake_minimum_required(VERSION 2.8.3)
project(pr2_make_a_map_app)
find_package(catkin REQUIRED COMPONENTS pr2_position_scripts gmapping tf topic_tools map_store)

catkin_package(
    DEPENDS pr2_position_scripts gmapping tf  topic_tools map_store
    CATKIN_DEPENDS # TODO
    INCLUDE_DIRS # TODO include
    LIBRARIES # TODO
)
