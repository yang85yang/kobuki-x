cmake_minimum_required(VERSION 2.8.3)
project(waiterbot_rapps)

find_package(catkin REQUIRED COMPONENTS)

catkin_package()

install(DIRECTORY rapps
        DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)

install(DIRECTORY media 
        DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
