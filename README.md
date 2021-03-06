Sprycle
=======

A sprite animation cycle utility.

<p align="center">
  <img src="https://raw.githubusercontent.com/wiki/GoranM/sprycle/images/explosion.gif" alt="explosion gif"/>
</p>

Cycle playback data can be generated with `sprycle.blend`, using the spryclegen add-on. By default, this data is both exported (for more general use) and also stored (in its pickled form) as an internal text within the .blend, ready to be linked in other .blend files, and ultimately consumed by a compatible BGE playback system. 

The sprycle python module (`sprycle.py`) is one such system, and it is included in this project.

Usage
-----

Read [the wiki](https://github.com/GoranM/sprycle/wiki).

Watch the [video tutorial](https://www.youtube.com/watch?v=LuWnDRlysV8).

Install
-------

_It is assumed that you already have a modern version of Blender installed (2.71 was used to create this project). If not, you'll need to address that first, of course._

Simply clone the repo with git, or [download the project zip](https://github.com/GoranM/sprycle/archive/master.zip).

Install the spryclegen add-on ([relevant info](https://github.com/GoranM/sprycle/wiki/Generating-cycle-data#addon-installation)).

When done, you should be able to open `sprycle.blend` with Blender, and use the utility.
