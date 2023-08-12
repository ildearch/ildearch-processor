# Processor EICMC

### E*xtented*
### I*CMC*
### C*omputing*
### M*a*C*hine*

This is an attempt at an updated version of building a microprocessor following a similar architecture as
the [Processador-ICMC](https://github.com/simoesusp/Processador-ICMC).

This project aims to:
- extend the original architecture;
- use non editor specific HDL;
- add testbenches for most of the complex components (probably using the ModelSim simulation tools,
but the testbench code will be in VHDL)
- add schematics for each component (atleast for the microprocessor)
- create a VHDL package for the microprocessor;
- create/recreate hardware components like:
  - video card (VGA video card following some of these [timings](http://www.tinyvga.com/vga-timing) and based on
  [this Ben Eater's video](https://www.youtube.com/watch?v=AHYNxpqKqwo))
  - serial interface (again, based on [this Ben Eater's video](https://www.youtube.com/watch?v=7aXbh9VUB3U))
  - PS/2 interface (guess what, based on [this other Ben Eater's video](https://www.youtube.com/watch?v=l7rce6IQDWs))
  - sound card ([maybe?](https://en.wikipedia.org/wiki/Sound_card), some FPGAs do have audio jacks...)
- create non FPGA specific macro components (micropocessor, video card, serial interface, ...) that can then be
choosen to be added on the top-level entity.

## Currently Implemented

Nothing ;)
