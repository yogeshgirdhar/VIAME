
###
# add all plugin subdirectories below

add_subdirectory( core )

if( VIAME_ENABLE_OPENCV )
  add_subdirectory( opencv )
endif()

if( VIAME_ENABLE_SCALLOP_TK )
  add_subdirectory( scallop_tk )
endif()

if( VIAME_ENABLE_FASTER_RCNN )
  add_subdirectory( faster_rcnn )
endif()

if( VIAME_ENABLE_MATLAB )
  add_subdirectory( matlab_ex )
endif()
