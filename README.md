# Sim-Arduboy
Arduboy board implementation using simavr

Follow the instruction for your operating system's _Dependencies setup_ section and then jump to the _Build_ section.

## Dependencies setup

### OSX

Install homebrew by running:

``` ShellSession
> /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Then install SDL2 and ELF libraries:

```
> brew install sdl2 libelf
```

### Windows (TBD)
### Linux (TBD)

## Build

### Command line

Clone repository:

``` ShellSession
> git clone --recursive https://github.com/dxxb/sim-arduboy.git
```

Build:

``` ShellSession
> cd sim-arduboy
> make
```

Run your .hex file:

``` ShellSession
> ./sim_arduboy filename.hex
```

### CMake (tested only on OSX)

Create XCode project files:

``` ShellSession
> cd sim-arduboy
> cmake ./cmake
```

Then open with XCode and build.