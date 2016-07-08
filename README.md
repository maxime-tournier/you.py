`you.py` is a simple python package that does some of what
[QGLViewer](http://libqglviewer.com/) does, but in pure python. It
provides a QGLWidget with basic viewing features.

The goal is to have something easy to hack from for trying stuff out.

## DONE

- viewport/projection matrix
- rotation trackball (left click)
- translation (right click)
- zoom (mouse wheel)
- axis clamping (double click)
- animation control (on/off/fps)
- spin/slide when rotating/translating fast
- basic lighting
- axis display

## TODO

- picking
- set pivot point
- text overlay
- easy/pythonic keybindings
- grid
- PyQt/PySide 4/5 compatible


## Usage

Install dependencies, *e.g.* on Debian/Ubuntu:

`sudo apt-get install python3-numpy python3-pyside python3-opengl`

then start one of the examples:

`$  python3 robot.py`




