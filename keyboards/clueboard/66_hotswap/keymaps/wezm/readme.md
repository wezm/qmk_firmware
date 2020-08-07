wezm's Clueboard Layout
=======================

    make clueboard/66_hotswap/gen1:wezm
    sudo make clueboard/66_hotswap/gen1:wezm:dfu-util

Arch avr-gcc seems to be too new so use Docker instead:

    ./util/docker_build.sh clueboard/66_hotswap/gen1:wezm
    sleep 5; ./util/docker_build.sh clueboard/66_hotswap/gen1:wezm:dfu-util
    Fn+S+R (to enter DFU)
