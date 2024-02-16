cmake_minimum_required(VERSION 3.16)
project(off_highway_sensor_drivers_examples)

# Dependencies
find_package(ament_cmake REQUIRED)

# Resources
install(
  DIRECTORY config launch
  DESTINATION share/${PROJECT_NAME}/
)

if(BUILD_TESTING)
  find_package(ament_lint_auto REQUIRED)
  ament_lint_auto_find_test_dependencies()
endif()

ament_package()
