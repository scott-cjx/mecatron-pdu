# Mectron Power Distribution Unit

This is a power distribution unit designed for @NTU-Mecatron.

@NTU-Mecatron is an autonomous underwater vehicle (enter desc)


## Overview
This power distribution unit boasts dual power supply inputs. They are for:

1. Propulsion & Actuators (or anything that moves)
2. Controllers & Low Voltage


## Progression
As simple as a power distribution unit may seem, theres maybe potential features that can be added. these improvements will be done in multiple phases

### Phase 1
- Dedicated Relays for VCC1 and VCC2 controlled by E-Stop and On/Off Switch respectively
- Dedicated Buck Convertors for each power rail (5v/9v/12v) for VCC2
- Dedicated Fuses for VCC1 & VCC2

### Phase 2
- Over & Under & Reverse Voltage Protection
- Adding control of VCC1 relay for MCU
- Attachment of external power meter to VCC1 and VCC2

### Phase 3
- Dedicated power meter to VCC1 and VCC2 (on-board)


## Schematics

Refer to [this](./schematics/mecatron-power-distribution-unit.pdf) for PDF version


## Board

Still a work in progress

