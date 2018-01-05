# minimake
A simple makefile for auto-building a cpp (or c) project

# Abstract
1) Searches _src_ dir and creates _obj_ dir hierarchy based on src
2) Generates make rules _(.d files)_ by using `cpp -MM`
3) Generates object files based on _.d_ make rules
4) Creates the final executable

# Usage
1) Place the source code in `src` dir
2) Change exec filename (see `MAIN = ...` in _Makefile_)
3) Run `make`
