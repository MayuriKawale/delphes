include_directories(${CMAKE_SOURCE_DIR}/external)

file(GLOB sources *.cc)

add_library(TrackCovariance OBJECT ${sources})
