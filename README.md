# TEJ4MI Programs and PCBs
Firefighter bot code and designs. [Jim Wang](https://github.com/Wangj3743) & [Larry Shi](https://github.com/LarryBananaShi).

## about
- these are the firefighter bot programs and PCBs that my teammate and I made in TEJ4MI
- here, we are using the PIC16F18875 microcontroller chip
- folders
 - breadboard: programs for the breadboard prototyping stage
 - final: programs for the final pcb stage
 - PCBs: pcb designs
- for the programs, they have already been compiled so you can directly program your chip with one of the compiled programs (if you're using MELabs Progrmamer, program with .hex)
- for the pcbs, you can directly print the .pcb files (can be done in TRAXMAKER)
- if you choose to deviate from our bot design, you will have to edit and recompile the programs and edit the pcbs (can be done in the great cow ide)


## ports
### sensors
- A0: phototransistor
- A1: IR sensor
- A2: wall sensor (front)
- A3: wall sensor (left)

### motors + motor fan
- C0: LME
- C1: LMB
- C2: RME
- C3: RMB
- A0: motor fan

### lcd
- D0: RS
- D1: RW
- D2: enable
- D4: DB4
- D5: DB5
- D6: DB6
- D7: DB7
