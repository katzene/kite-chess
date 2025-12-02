[![Kite](https://github.com/saifs27/kite-chess/actions/workflows/kite.yml/badge.svg)](https://github.com/saifs27/kite-chess/actions/workflows/kite.yml)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)



# Kite Chess Engine

## About
Kite is a work in progress UCI chess engine which analyzes and outputs the best moves.

## Build Instructions

Kite requires a C++20 compatible compiler and CMake 3.31. Run these commands to build:

```
cmake -S . -B build
cmake --build build --config Release
```
