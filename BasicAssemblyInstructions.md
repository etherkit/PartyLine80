# Party Line 80 Basic Assembly Instructions

## Power Entry
* D13 - LED
* D14 - SB140
* R62 - 3.3 kΩ
* J4 - 2.1 x 5.5 mm DC power jack

### Power Entry Functional Test
Check for DC power on TP4, LED lights up.

## AF Power Amplifier
* D4, D4, D6 - 1N4148
* R31, R33 - 100 kΩ
* R29, R30 - 1 Ω
* R28 - 10 Ω
* R26 - 51 Ω
* R23 - 470 Ω
* R27 - 1 kΩ 
* R22, R24, R25 - 2.2 kΩ
* R21 - 4.7 kΩ
* R19 - 47 kΩ
* R20 - 10 kΩ
* C20 - 2.2 nF
* C19, C21, C24, C25 - 10 μF
* C17, C22, C23 - 100 μF
* Q10, Q11 - 2N7000
* Q9 - 2N4403
* Q5, Q6, Q7, Q8 - 2N4401
* J1 - 3.5 mm Jack

### AF Power Amplifier Functional Test

## Active AF Low-Pass Filter
* R12, R16 - 100 Ω
* R10, R11, R13, R14, R15, R17 - 4.7 kΩ
* C16 - 100 nF
* C5, C7, C11, C13 - 10 nF
* C9, C15 - 10 μF
* Q3, Q4 - 2N4401

## W7ZOI AF Feedback Amplifier
* R1, R7 - 51 Ω
* R3 - 150 Ω
* R5 - 22 Ω
* R8 - 680 Ω
* R9 - 220 Ω
* R4 - 1 kΩ
* R2, R6 - 1.8 kΩ
* Q1, Q2 - 2N4401
* C1 - 100 nF
* C3, C4 - 100 μF
* C2 - 220 μF
* L1 - FT37-43 25 turns

### Active AF Low-Pass Filter and W7ZOI AF Feedback Amplifier Functional Test
Listen for hiss, check AF gain pot function, listen for hum when a metal tool is used to probe TP10.

## Double-Balanced Diode Ring Mixer
* D1, D2, D3, D4 - 1N4148
* T3, T4 - FT37-43 10 turns bifilar

## 3.5815 MHz Crystal Filter
* T1, T2 - FT37-43 3 turns:21 turns
* C6, C10, C14 - 25 pF
* C8, C12 - 20 pF
* X1, X2, X3, X4 - 3.582 MHz crystal

## Local Oscillator
* D8 - 1N4148
* D10 - 1N5237B
* R35 - 100 kΩ
* R41, R42 - 10 kΩ
* R46, R51 - 100 Ω
* R52, R54 - 220 Ω
* R47, R50 - 470 Ω
* R53, R56 - 150 Ω
* C33, C34 - 560 pF
* C36, C37, C38, C39 - 100 nF
* Q13 - 2N7000
* Q15, Q16 - 2N4401
* C29 - 45 pF trim cap (yellow)
* X5 - 3.582 MHz crystal

### Local Oscillator Functional Test
Check for LO signal at TP1 and TP2

## TX Low-Pass Filter and T/R Switch
* D11, D12 - 1N4148
* C49, C53 - 270 pF
* C51, C52 - 1 nF
* C46 - 82 pF
* L5 - FT37-61 20 turns
* L7 - T37-2 26 turns
* L6, L8 - T37-2 20 turns
* J3 - BNC jack

### Receiver Functional Test

## Keying and Mute
* D15 - 1N4148
* R34 - 220 Ω
* R36 - 2.2 kΩ
* C28 - 100 nF
* Q12 - 2N4403
* J2 - 3.5 mm jack

### Keying and Mute Functional Test
Connect a key to the key jack and listen for the audio hiss to be muted when the radio is keyed.

## Sidetone Oscillator
* R57 - 47 Ω
* R59 - 330 Ω
* R58, R60, R61 - 3.3 kΩ
* R32 - 220 Ω
* C26, C45, C47, C48, C50 - 100 nF
* C44 - 1 μF
* Q20 - 2N4401

### Sidetone Oscillator Functional Test
Connect a key to the key jack and listen for a receiver muting and a sidetone when keying is activated.

## TX Preamp
* R43 - 47 Ω
* R44 - 4.7 Ω
* R40 - 100 Ω
* R37 - 1.5 kΩ
* R38 - 2.2 kΩ
* R39 - 3 kΩ
* C27, C30, C31, C32, C35 - 100 nF
* Q14 - 2N4401
* T5 - FT37-43 10 turns bifilar

### TX Preamp Functional Test

## TX Power Amplifier
* D9 - 1N5237B
* R45 - 10 kΩ
* R48, R49 - 3.3 kΩ
* C40 - 100 nF
* C41 - 560 pF
* C42 - 360 pF
* C43 - 1.5 nF
* L2, L3 - FT37-43 10 turns
* L4 - T50-2 36 turns
