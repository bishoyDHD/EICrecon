cmake_minimum_required(VERSION 3.16)

add_subdirectory(interfaces)
add_subdirectory(calorimetry)
add_subdirectory(tracking)
add_subdirectory(pid)
add_subdirectory(pid_lut)
add_subdirectory(digi)
add_subdirectory(reco)
add_subdirectory(fardetectors)

if(USE_ONNX)
  add_subdirectory(onnx)
endif()
