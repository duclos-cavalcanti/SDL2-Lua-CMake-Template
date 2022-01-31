# SDL2 Lua CMake Template

# 1. Introduction

# 2. Dependencies
1. `CMake`
2. `Lua` and its development headers
3. `SDL2`

## 2.1 Debian
```sh
sudo apt-get install build-essential libsdl2-ttf-dev libsdl2-mixer-dev libsdl2-image-dev libsdl2-gfx-dev libsdl2-dev
# TODO
```

## 2.2 Arch
```sh
sudo pacman -S cmake lua sdl2 sdl2_gfx sdl2_image sdl2_mixer sdl2_ttf
```

# 3. Getting Started
1. Build
```sh
cd build
cmake ..
make
```

2. Run
```sh
make run
```
