# AudioFilePlayerPlugin
The original source code is [here](https://github.com/jonathonracz/AudioFilePlayerPlugin), 
this repositorie just update JUCE to 6.0 and add CMake building.
# How to Build
1. download [JUCE](https://github.com/juce-framework/JUCE)
2. build with cmake
```cmake
cmake -S . -B build -DJUCE_SOURCE_DIR_PATH="/path/to/juce"
cmake --build build -- -j 10
```