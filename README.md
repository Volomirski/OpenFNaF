# OpenFNaF
A (WiP) Open-Source Reimplementation of Scott Cawthon's Five Nights at Freddys. Written in C. Licensed under MIT.

# In It's Current State
Part of the first [Five Night's at Freddy's](https://store.steampowered.com/app/319510/Five_Nights_at_Freddys/) title has been implemented, then OpenFNaF engine can interact with game code (game_fnaf1.c) and Animas can move to designated locations. At this time there is no renderer, but an OpenGL Window (provided by freeglut) will open.

# Building
OpenFNaF requires the following additional libraries to build:
* [freeglut3-dev](http://freeglut.sourceforge.net/) (MIT)

Simply run `make`, if provided all additional libraries, OpenFNaF should build without issue. Object files will be stored in the created `build` directory, an executable will be located in the root directory of the project.

OpenFNaF also supports `make clean`.

# Running
## Command Line Arguments
At this time, OpenFNaF supports the following arguments on launch:
* `-no-render`: Disable Window and Renderer.

# Regarding Copyright
Under no circumstances will licensed assets be provided on this GitHub repository. This includes, but is not limited to, sounds and graphics. The Five Nights at Freddy's IP belongs to it's rightholders, Clickteam LLC and Scott Cawthon.