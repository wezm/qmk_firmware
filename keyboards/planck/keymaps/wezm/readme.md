# wezm's Planck Layout

Derived from rev4 default layout.

## Changes and Additions

* Swap Esc and Tab
* Tab is layer tap key: Tab when tapped, Function layer when held
* Enter is shift key: Enter when tapped, Shift when held
* Move left Ctrl to outer edge
* Add right Ctrl in bottom right
* Add Function layer
  * Macros
  * Arrow keys on HJKL where they belong
  * Del on Backspace
* Add gaming layer
  * Move WASD down a row and add number keys across the top row

## Building and Programming

Build:

    make planck-rev4-wezm

Program (Linux):

Enter the bootloader (Raise Lower Q), then run:

    sudo make planck-rev4-wezm-dfu
