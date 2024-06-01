# audiorw
Windows version of audiorw: https://github.com/sportdeath/audiorw

In the folder modules, there is a file called FindFFMPEG.cmake. In that file you need to update the directories of the ffmpeg libraries so they can be found.
## Installation

To install the library, clone it, build it with ```cmake```, then install it:

    git clone https://github.com/deleonerick1808/audiorw_windows
    mkdir audiorw_windows\build
    cd audiorw_windows\build
    cmake ..
    cmake --build . --config Release
    cmake --install .

