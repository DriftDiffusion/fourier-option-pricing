# CMakeList.txt : CMake project for Fourier-Option-Pricing, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (Fourier-Option-Pricing "Fourier-Option-Pricing.cpp" "Fourier-Option-Pricing.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET Fourier-Option-Pricing PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
