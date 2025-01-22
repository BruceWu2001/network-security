# c-project-structure

Project description

Project image/gif

## Requirements

Requirements 
- use linux
- make installed

## Installation

`make`
make will result in c files being built into .o, .i and .s being object files preprocessed source files and the assembly code respectively
they will be placed in build/
it is also further compiled into a binary bin/run.exe

## Usage

`bin/run`
use linux
to run just ./bin/run 

## Example

`bin/run`

## Documentation

Location of Documentation

## Directory structure
```
|-- Makefile           <- Project makefile
|-- README             <- Project README
|-- bin                <- Compiled binaries
|   `-- run            <- Project main executable
|-- build              <- Static objects and intermediate files
|-- data               <- Project data
|   |-- raw            <- Raw data
|   |-- interim        <- Interm data
|   |-- input          <- Input data
|   |-- output         <- Output data
|-- docs               <- Documentation
|-- include            <- Header files
|-- lib                <- Dynamic objects
|-- src                <- Source files
`-- tests              <- Unit tests
```


useful commands
make clean - remove the build directory
