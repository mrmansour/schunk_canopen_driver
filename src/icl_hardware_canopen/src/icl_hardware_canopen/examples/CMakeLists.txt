ICMAKER_SET("icl_hardware_canopen_example") # IDE_FOLDER ${ICL_HARDWARE_IDE_FOLDER})

ICMAKER_ADD_SOURCES(
  simple_example.cpp
)

ICMAKER_DEPENDENCIES(
  icl_core
  icl_hardware_canopen
  Boost_FILESYSTEM
  Boost_SYSTEM
  Boost_THREAD
)

ICMAKER_BUILD_PROGRAM()


ICMAKER_SET("icl_hardware_canopen_minimal_example") # IDE_FOLDER ${ICL_HARDWARE_IDE_FOLDER})

ICMAKER_ADD_SOURCES(
  minimal_example.cpp
)

ICMAKER_DEPENDENCIES(
  icl_core
  icl_hardware_canopen
  Boost_FILESYSTEM
  Boost_SYSTEM
  Boost_Thread
)

ICMAKER_BUILD_PROGRAM()


ICMAKER_SET("icl_hardware_canopen_pg70_example") # IDE_FOLDER ${ICL_HARDWARE_IDE_FOLDER})

ICMAKER_ADD_SOURCES(
  pg70_example.cpp
)

ICMAKER_DEPENDENCIES(
  icl_core
  icl_hardware_canopen
  Boost_THREAD
  Boost_SYSTEM
  Boost_FILESYSTEM
)

ICMAKER_BUILD_PROGRAM()
