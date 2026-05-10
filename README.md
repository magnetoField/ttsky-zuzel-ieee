![](../../workflows/gds/badge.svg) ![](../../workflows/docs/badge.svg) ![](../../workflows/test/badge.svg) ![](../../workflows/fpga/badge.svg)

# Zuzel game harden in silicon by Krzysztof Kluczek 
Original repository here: [https://github.com/Krzysiek-K](https://github.com/Krzysiek-K)
![gds render](KK-vga.png)

## Inspired by Piotr Kamiński game created in 1994
[Watch game play of original game here](https://www.youtube.com/watch?v=TAxoQyd6Lxc)
Custom CPU architecture was designed to fit complete project on a small area of silicon (100 um x 160 um).

## How it works

A motor track racing game for up to 4 players.
Each player controls his/her bike using a single input pin: 0 - straight+accelerate, 1 - turn left+brake.
Outpace your opponents and don't fall out of the track!

![image](Screenshot.png)

## How to test

Connect to VGA. Use Input pins 0..3 to control motobikes and Input pin 4 to reset gameplay.

## External hardware

- VGA output PMOD
- Gameplay reset signal on Input[4]
- 4 input signals from player controls (active 1) on Input[3:0]
