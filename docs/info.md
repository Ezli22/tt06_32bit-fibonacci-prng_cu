<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections..

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

probador de 7 segmentos

A schematic of the circuit may be found at:

https://wokwi.com/projects/395347427728226305

The circuit has 10 inputs:

| Input    | Setting                     |
| -------- | -------                     |
| CLK      | Not Used                       |
| RST_N    | Not Used                    |
| 01       | en1                    |
| 02       | en2       |
| 03       | en3               |
| 04       | en4                    |
| 05       | Not Used                    |
| 06       | Not Used                    |
| 07       | Not Used                    |
| 08       | Not Used                    |

todas las entradas son referencias que funcionan como un sistema binario para verificar el funcionamiento de los 7 segmentos. 

| Output   | Value io para dein    |
| -------- | -------     |
| 01       | s0 |
| 02       | s1 |
| 03       | s2 |
| 04       | s3 |
| 05       | s4 |
| 06       | s5 |
| 07       | s6 |
| 08       | Not Used |

## How to test

Las saidas son la recepacion de los bits, envia dos por las entradas que se puede visualizar el el display de 7 segmentos. 



A python implementation of the 32-bit Fibonacci LFSR can be found at the link below. It may be used for testing the hardware for sequences longer than the initial 100 values.

https://github.com/icarislab/tt06_32bit-fibonacci-prng_cu/main/docs/32-bit-fibonacci-prng_pythong_simulation.py

## External hardware

No external hardware is required.
