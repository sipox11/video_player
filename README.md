# Basic Video Player
Video player written in C, based on ffmpeg library.

## Installation
1) Get the dependencies
```
sudo apt-get update
sudo apt-get -y install autoconf automake build-essential libass-dev libfreetype6-dev \
  libsdl2-dev libtheora-dev libtool libva-dev libvdpau-dev libvorbis-dev libxcb1-dev libxcb-shm0-dev \
  libxcb-xfixes0-dev pkg-config texinfo wget zlib1g-dev
```

2) Compilation
```
gcc -o main main.c -lavutil -lavformat -lavcodec -lz -lavutil -lm
