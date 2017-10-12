# Basic Video Player
Video player written in C, based on ffmpeg library.

## Installation
1) Guide for ffmpeg library installation for Ubuntu:
https://trac.ffmpeg.org/wiki/CompilationGuide/Ubuntu

2) Compilation
```
gcc -o main main.c -lavutil -lavformat -lavcodec -lz -lavutil -lm
