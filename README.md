## Overview

![structure](https://github.com/chanioxaris/Multithreaded-MirrorServer/blob/master/img/structure.png)

## Multithreading

### Shared Queue

### Mirror threads

### Worker threads

## Compile

`./makefile`

## Usage

`./ContentServer -p [port] -d [directory to share]`

`./MirrorServer -p [port] -m [directory to save files] -w [number of workers threads]`

`./MirrorInitiator -m [name of MirrorServer] -p [port of MirrorServer] -s [info for files to transfer]`
