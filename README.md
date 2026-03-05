[![Version: 1.0 Release](https://img.shields.io/badge/Version-1.0%20Release-green.svg)](https://github.com/0x007e/tpd) ![Build](https://github.com/0x007e/tpd/actions/workflows/release.yml/badge.svg) [![License CC By-NC-SA](https://img.shields.io/badge/Hardware-CC--BY--NC--SA--4.0-lightgrey)](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode)

# `TPD` - Touchpad

The `TPD` is a board with six singled pads that are connected to a [AT42QT1070](#additional-information) touch sensor. The touch sensor can be connected to any microntroller over `TWI`. The board itself can be driven with a voltage from `1V8-5V` and controlled over the [AT42QTXXXX driver library](https://github.com/0x007E/drivers-touch-at42qtxxxx).

| Experience  | Level                                                                               |
|:------------|:-----------------------------------------------------------------------------------:|
| Soldering   | ![?%](https://progress-bar.xyz/30?progress_color=00ff00&suffix=%20Medium&width=120) |

# Downloads

| Type      | File                                                                                                                                                 | Description     |
|:---------:|:----------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------|
| Schematic | [pdf](https://github.com/0x007E/tpd/releases/latest/download/schematic.pdf) / [cadlab](https://cadlab.io/project/30134/main/files)                   | Schematic files |
| Board     | [pdf](https://github.com/0x007E/tpd/releases/latest/download/pcb.pdf) / [cadlab](https://cadlab.io/project/30134/main/files)                         | Board file      |
| Drill     | [pdf](https://github.com/0x007E/tpd/releases/latest/download/drill.pdf)                                                                              | Drill file      |
| PCB       | [zip](https://github.com/0x007E/tpd/releases/latest/download/kicad.zip) / [tar](https://github.com/0x007E/tpd/releases/latest/download/kicad.tar.gz) | KiCAD/Gerber/BoM/Drill files |

# Hardware

The pcb is created with `KiCAD`. All files are built with `github actions` so that they are ready for a production environment.

## PCB

The circuit board is populated on one side (Top). The best way for soldering the `SMD` components is within a vapor phase soldering system and a standard soldering system. After placing and soldering the top parts.

### Top Layer

![Top Layer](https://github.com/0x007E/tpd/releases/latest/download/top.kicad.png)

### Bottom Layer

![Bottom Layer](https://github.com/0x007E/tpd/releases/latest/download/bottom.kicad.png)

# Additional Information

| Type       | Link                                                                                                      | Description                                        |
|:----------:|:---------------------------------------------------------------------------------------------------------:|:---------------------------------------------------|
| AT42QT1070   | [pdf](https://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-9596-AT42-QTouch-BSW-AT42QT1070_Datasheet.pdf) | Seven-channel QTouch® Touch Sensor IC |

---

R. GAECHTER
