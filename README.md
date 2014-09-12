# Simple OpenGL Example

This shows you how to get started using OpenGL using a simple example.
Currently instructions are Mac OS X specific only.

## Installation

On Mac OSX:

``` sh
$ brew install homebrew/versions/glfw3
```

## Building

On Mac OSX:

``` sh
$ cc `pkg-config --cflags glfw3` -o simple simple.c `pkg-config --static --libs glfw3`
```

## Running

On Mac OSX:

``` sh
$ ./simple
```
