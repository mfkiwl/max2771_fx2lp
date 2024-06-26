## MAX2771 for FX2LP

### Objective: multi-MAX2771 GNSS receiver 

... for
* multiband acquisition and processing if a power combiner (MiniCircuits ZAPD-2DC+)
is used to feed both chips with the signal coming from a single multiband antenna
* CRPA (Controlled Radiation Pattern Antenna) if each chip is fed from a different
antenna for spatial diversity

<img src="HW/IMG_20240629_113625_461small.jpg">

Assembled daughter board: the missing 24 MHz oscillator is replaced with the 
24 MHz output from one of the resonator pins fitted on the FX2LP board.

### TODO:

* use opensource tools for programming the FX2LP (https://github.com/topics/fx2lp 
using ``sdcc``)
