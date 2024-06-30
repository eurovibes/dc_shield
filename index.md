# Welcome to the **dc_shield** project

## Documentation
The IFX9201SG is a general purpose 6 A H-Bridge, designed for the control of
DC motors or other inductive loads. The outputs can be pulse width modulated
at frequencies up to 20kHz. The IFX9201SG has the capability to report status
informations over SPI.

The **dc_shield** project use the IFX9201SG to build a two channel DC motor
shield with Arduino Uno R3 headers. This header is widly spread on eval boards
like the ST Nucleo-64, Nucleo-144 or Altera Atlas board.

### Arduino Uno R3 used pins
**dc_shield** use the following header pins:

#### Analog
All pins are unused.

#### Digital

| Pin |  Signal  |
|-----|----------|
| D1  | unused   |
| D2  | unused   |
| D3  | DIR1     |
| D4  | DIS1     |
| D5  | PWM1     |
| D6  | DIR2     |
| D7  | unused   |
| D8  | DIS2     |
| D9  | PWM2     |
| D10 | SPI nCS  |
| D11 | SPI MOSI |
| D12 | SPI MiSO |
| D13 | SPI SCK  |
| D18 | I2C SDA  |
| D19 | I2C SCL  |

#### Power
Vin is used to feed the board with +12V. +3V3 and +5V are powerd by the board
and used on the shield.

### Schematic
Link to the [Schematic](https://eurovibes.github.io/dc_shield/Fabrication/dc_shield-schematic_0.1.pdf).

### Layout

#### Top
![Bottom Layer](https://eurovibes.github.io/dc_shield/Fabrication/PCB/blue/dc_shield-top_.jpg)

#### Bottom
![Bottom Layer](https://eurovibes.github.io/dc_shield/Fabrication/PCB/blue/dc_shield-bottom_.jpg)

### BoM
**dc_shield** provides am [interactive BoM](https://eurovibes.github.io/dc_shield/Fabrication/BoM/dc_shield-ibom_.html).

## Fabrication
**dc_shield** provides generic gerber files and fabrication data for JLCPCB
and Seeed Fusion PCB.

### Gerber
Gerber files can be downloaded [here](https://eurovibes.github.io/dc_shield/Fabrication/gerber.zip).

### JLCPCB
Fabrication files for [JLCPCB](https://eurovibes.github.io/dc_shield/Fabrication/JLCPCB/dc_shield-JLCPCB_.zip).

### Seeed Fusion PCB
Fabrication files for [Seeed Fusion PCB](https://eurovibes.github.io/dc_shield/Fabrication/FusionPCB/dc_shield-FusionPCB_.zip).

## License rules

**dc_shield** is provided under the terms of the CERN-OHL-S license version 2
as provided in the LICENSES/CERN-OHL-S-2.0 file.

Instead of adding license boilerplates to the individual files, **dc_shield**
uses SPDX license identifiers, which are machine parseable and considered
legaly equivalent.

The SPDX license identifier in **dc_shield** shall be added at the first
possible line in a file which can contain a comment. This is normally the
first line except for scripts. Scripts require the #!PATH_TO_INTERPRETER tag
in the first line; place the SPDX identifier into the second line.

The SPDX license identifier is added in form of a comment.

## Copyright and License
> Copyright Benedikt Spranger 2024.
> This source describes Open Hardware and is licensed under the CERNOHL-S v2.
> You may redistribute and modify this source and make products using it
> under the terms of the [CERN-OHL-S v2](https://ohwr.org/cern_ohl_s_v2.txt).
> This source is distributed WITHOUT ANY EXPRESS OR IMPLIED
> WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY
> QUALITY AND FITNESS FOR A PARTICULAR PURPOSE. Please see
> the CERN-OHL-S v2 for applicable conditions.
> Source location: (https://github.com/eurovibes/dc_shield)
> As per CERN-OHL-S v2 section 4, should You produce hardware based on this
> source, You must where practicable maintain the Source Location visible on
> the external case of the **dc_shield** or other products you make
> using this source.
