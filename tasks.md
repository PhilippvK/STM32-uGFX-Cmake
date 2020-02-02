# Tasks

List of ideas I collected to improve the ESPL toolchain over the next few months.

## Task Manager Setup

For easier handing of TODO items, you may want to use https://github.com/benjaminoakes/markdo which you can install simply by running `gem install markdo`.

Then run
```
export MARKDO_ROOT=.
export MARKDO_INBOX=tasks.md
```

in this directory.

## By Categories

# Actual Toolchain

- [ ] Link math library by default/optional
- [ ] Include UGFX files for drawing images/fonts
- [ ] FreeRTOS: provide option fo change the used heap
- [ ] Generate project files for Eclipse, VSCode,...
- [x] 100% Ubuntu support @alxhoff
- [ ] 100% MacOS support @philippvk @wip
- [ ] C++ support (Discuss with @alxhoff)
- [ ] Incremental builds?
- [ ] Program before debug required?
- [ ] `build/` directory or at least `libs/` for Downloads
- [ ] Fix `make clean`
- [ ] Support: `SET(FREERTOS_HEAP_IMPL 4)` (See https://github.com/ObKo/stm32-cmake/blob/master/README.md)

# Demo Project

- [ ] Rework FrameSwapper task
- [ ] Do not guarantee frame timing
- [ ] Try to make use of the STM32F4 Flash/EEPROM for non-volatile memory
- [ ] Increase UART baudrate
- [ ] Implement UART with interrups/DMA
- [ ] Cleanup `gfxconf.h` and `FreeRTOSConfig.h`

# Documentation

- [ ] Provide Instructions for using Images/Fonts
- [ ] Add to manual how install `st-flash`,... (for MacOS, WSL/MinGW)
- [ ] Links to useful ressources (API, Wiki, UGFX examples,...)
- [ ] Upload Example Debug Configurarion for Eclipse

# Lecture/Exercises

- [ ] Edit incomprehensible task description
- [ ] Create "Sample Solution"
- [ ] Chapter about debugging / OpenOCD / GDB
- [ ] Git Tutorial: target CMake version

# Hardware/Lab related

- [ ] @due(2020-03-31) Buy new USB cables for UART (Multiplayer) @wip
- [ ] @due(2020-02-14) Lock cupboard with key @philippvk
- [ ] Allow programming individual board with 2 USB cables (See https://www.bergzand.net/programming-with-multiple-st-link-programmers.html)
- [ ] Experiment with sound
- [ ] Test using cmake version on lab PCs

# TEST

- [ ] TEST @defer(2016-10-01)
- [ ] LOCATION @downtown
- [ ] STAR @star
- [ ] NEXT @next
- [ ] 123