# Toontown Infinite Builder

This repository contains the instructions for building aston and panda3d to run this version of Toontown-Infinite.

## Building
Building will build the astrond executable, and the panda3d library for your operating system, and place them in the correct directories

### Linux and Mac (Only tested on linux)

`./build.sh`

### Windows

`build.bat`

Windows doesn't build astron.exe and just uses the already provided repository version.

If you dont trust this, you will have to follow the build instructions and build your own.

## Executing

### Sever

Easiest way is to execute `python src/ToontownClusterManager.py`

Otherwise manually run the files under `src/astron/<your os>/`

### Client

To run a client execute the desired launcher under `src/<your os>/`
