# Generated by ModuleTarget.py
# Remove a "#" from the line below to stop generating this file every time you call CoreWorkspace generate
## TARGET MODULE proximity

PROJECT( proximity )
CMAKE_MINIMUM_REQUIRED(VERSION 2.8)

FIND_PACKAGE( CORE_BUILD CONFIG REQUIRED )

INCLUDE ( CoreTarget NO_POLICY_SCOPE )
SET( PROJECT_INCLUDE_DIRECTORIES
)

SET( PROJECT_SOURCES
  main.cpp
)

core_target_module(
  MODULE proximity
  OS_VERSION CHIBIOS_3
  PACKAGES
    sonar_publisher
    sensor_msgs
)
