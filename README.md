
Ship
Fleet
Alien

US01: Move the ship and fire

Install pygame

pip3 install Pygame

MichaeldeMacBook-Pro-2:crash myang$ python3
Python 3.6.0 (v3.6.0:41df79263a11, Dec 22 2016, 17:23:13)
[GCC 4.2.1 (Apple Inc. build 5666) (dot 3)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> import pygame
>>> help(pygame)

Help on package pygame:

NAME
    pygame

DESCRIPTION
    Pygame is a set of Python modules designed for writing games.
    It is written on top of the excellent SDL library. This allows you
    to create fully featured games and multimedia programs in the python
    language. The package is highly portable, with games running on
    Windows, MacOS, OS X, BeOS, FreeBSD, IRIX, and Linux.

SDL: Simple DirectMedia Layer

Simple DirectMedia Layer (SDL) is a cross-platform software development library designed to provide a hardware abstraction layer to computer multimedia hardware components.

SDL是一个跨平台的软件开发包，为计算机多媒体硬件提供一个抽象的硬件层。

http://www.libsdl.org/
 Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games.



help> pygame.display.set_mode

Help on built-in function set_mode in pygame.display:

pygame.display.set_mode = set_mode(...)
    set_mode(resolution=(0,0), flags=0, depth=0) -> Surface
    Initialize a window or screen for display



pygame是一个pakcage

Help on package pygame:

NAME
    pygame

DESCRIPTION
    Pygame is a set of Python modules designed for writing games.
    It is written on top of the excellent SDL library. This allows you
    to create fully featured games and multimedia programs in the python
    language. The package is highly portable, with games running on
    Windows, MacOS, OS X, BeOS, FreeBSD, IRIX, and Linux.

PACKAGE CONTENTS
    _camera_opencv_highgui
    _camera_vidcapture
    _dummybackend
    _freetype
    _numpysndarray
    _numpysurfarray
    base
    bufferproxy
    camera
    cdrom
    color

    Help on module pygame.color in pygame:

NAME
    pygame.color - color module for pygame

FUNCTIONS
    correct_gamma(...)
        correct_gamma (gamma) -> Color
        Applies a certain gamma value to the Color.

    normalize(...)
        normalize() -> tuple
        Returns the normalized RGBA values of the Color.

    set_length(...)
        set_length(len) -> None
        Set the number of elements in the Color to 1,2,3, or 4.

DATA
    THECOLORS = {'aliceblue': (240, 248, 255, 255), 'antiquewhite': (250, ...

FILE
    /Library/Frameworks/Python.framework/Versions/3.6/lib/python3.6/site-packages/pygame/color.cpython-36m-darwin.so


    Help on module pygame.sprite in pygame:

NAME
    pygame.sprite - pygame module with basic game object classes

DESCRIPTION
    This module contains several simple classes to be used within games. There
    are the main Sprite class and several Group classes that contain Sprites.
    The use of these classes is entirely optional when using Pygame. The classes
    are fairly lightweight and only provide a starting place for the code
    that is common to most games.


Help on class Group in pygame.sprite:

pygame.sprite.Group = class Group(AbstractGroup)
 |  container class for many Sprites
 |
 |  pygame.sprite.Group(*sprites): return Group
 |
 |  A simple container for Sprite objects. This class can be subclassed to
 |  create containers with more specific behaviors. The constructor takes any
 |  number of Sprite arguments to add to the Group. The group supports the
 |  following standard Python operations:



 |  draw(self, surface)
 |      draw all sprites onto the surface
 |
 |      Group.draw(surface): return None
 |
 |      Draws all of the member sprites onto the given surface.