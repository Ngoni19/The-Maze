# The-Maze
The Maze is a 3D Maze game that uses ray casting to render a 2D map into a 3D navigable world! The C language as used in addition with SDL2 library.
Deveploment was performed using Ubuntu 14.04 LTS - gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4

### About SDL2 

SDL, or Simple DirectMedia Layer, is a software library that was created to offer developers access to the low-level functionalities of audio, keyboard, mouse, joystick, and graphics hardware on multiple platforms through OpenGL and Direct3D. It has been implemented in various applications including emulators, video playback software, and popular games such as the ones available in Valve's impressive collection and numerous Humble Bundle games.

## Installation 
Clone this repo:

```sh
$ git clone https://github.com/Ngoni19/The-Maze.git
```

### Linux: 
```bash
sudo apt-get install libsdl2-dev
```
### MacOS:
Install hombebrew for mac-> https://brew.sh/
MacOS -> brew install sdl2
SDL website: https://www.libsdl.org/download-2.0.php
Ensure sdl is installed. Then run the following command:

```bash
make mac
```
---
## Compilation
```sh
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;
$ ./maze
```


## Controls

```W``` - forward

```S``` - backward

```A``` - Look left

```D``` - Look right

```Mouse move left/right``` - look left or right

```M``` - Turn off map visibility.

```N``` - Turn on map visibility.

# Directories

[`src`](https://github.com/Ngoni19/The-Maze/tree/main/src)

All C source code found here.

[`header`](https://github.com/Ngoni19/The-Maze/tree/main/header)

Contains all the C header files.

[`mapping`](https://github.com/Ngoni19/The-Maze/tree/main/mapping)

Contains map data files to be used by the program to output the map layout.

[`images`]()

Contains image files.

### Sources
1. [`SDL Wiki:`] (https://wiki.libsdl.org/)

2. [`Lazy Foo' Productions:`] (https://lazyfoo.net/tutorials/SDL/index.php)

3. [`Game Development Envato Tuts+:`] (https://gamedevelopment.tutsplus.com/categories/sdl)

4. [`GameFromScratch:`] (https://www.gamefromscratch.com/tag/sdl/)

5. [`SDL Development Community:`] (https://discourse.libsdl.org/)


### Authors
Ngoni19 <a href = "https://wa.me/+263776264077"><img src="https://img.icons8.com/fluent/48/000000/whatsapp.png"></a>