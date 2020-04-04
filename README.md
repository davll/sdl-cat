# SDL2: Cat Demo

It is nothing but showing the picture of a cat. I made the demo to test [Sway](https://github.com/swaywm/sway).

The demo is forked from [xyproto's sdl2-examples](https://github.com/xyproto/sdl2-examples) and added event loops to allow user interaction.

## Build (Linux + Wayland)

1. `cmake -S . -B build`
2. `make -C build`
3. `SDL_VIDEODRIVER=wayland ./build/cat`

## Usage

- SPACE key: toggle repainting
- ESCAPE key: quit the demo

