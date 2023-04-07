# The-Maze
The Maze is a 3D Maze game that uses ray casting to render a 2D map into a 3D navigable world! The C language was used in addition with SDL2 library.
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

## Directories

[`src`](https://github.com/Ngoni19/The-Maze/tree/main/src) - All C source code found here.

[`header`](https://github.com/Ngoni19/The-Maze/tree/main/header)  - Contains all the C header files.

[`mapping`](https://github.com/Ngoni19/The-Maze/tree/main/mapping)  - Contains map data files to be used by the program to output the map layout.

[`images`]() - Contains image files.

### Sources
1. *[SDL Wiki](https://wiki.libsdl.org)*

2. *Lazy Foo' Productions](https://lazyfoo.net/tutorials/SDL/index.php)*

3. *[Game Development Envato Tuts+](https://gamedevelopment.tutsplus.com/categories/sdl)*

4. *[GameFromScratch](https://www.gamefromscratch.com/tag/sdl/)*

5. *[SDL Development Community](https://discourse.libsdl.org/)*

## Contributing

- Read the source files in ```src``` folder and the header files in ```include``` folder.
- Clone the repo and make a new branch: $ git checkout https://github.com/Ngoni19/The-Maze -b [name_of_new_branch].
- Add a feature, fix a bug, or refactor some code :)
- Write/update tests for the changes you made, if necessary.
- Update README.md if necessary.
- Open a Pull Request with a comprehensive description of changes.

## My Story
The experience gained during my ALX software Engineering program (@Holberton School) I have developed a passion for software backend development, and I strive to create innovative solutions that exceed expectations.😎

This portfolio project is a journey on how i implemented C programing skills and project management to deploy a playable 3D maze game.  

I am always eager to learn new skills and take on new challenges, and I am excited about the potential to work with like-mindedprofessionals who share my passion for excellence.

I have always been fascinated by the intricate details that go into creating video games. I believe that games can be a powerful tool for storytelling, education, and entertainment, and I have always been intrigued by the technical challenges thatdevelopers face in bringing those virtual worlds to life.

For me, SDL game development in C represents the perfect intersection of art and science, where I can utilize my programming skills to create engaging and immersive experiences for players. I find the process of designing game mechanics, developing game engines, and optimizing performance to be both challenging and rewarding.

Ultimately, my goal in pursuing SDL game development in C for my portfolio project is to showcase my skills and creativity as adeveloper while also providing a fun and engaging experience for players. I am excited about the potential to learn and grow as a developer through this project, and I hope to inspire others to explore the exciting world of game development as well.

## Related

*[The Maze](https://alx-intranet.hbtn.io/concepts/133)* - ALX Project Page

## License
**BSD**

### Authors
Ngoni19 <a href = "https://github.com/Ngoni19"><img src="https://img.icons8.com/fluent/48/000000/github.png"></a> <a href = "www.linkedin.com/in/ngonidzashe-brandon-towindo-53647411b/"><img src="https://img.icons8.com/fluent/48/000000/linkedin.png"></a>
