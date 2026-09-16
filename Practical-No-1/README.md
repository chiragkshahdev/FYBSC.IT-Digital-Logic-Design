# FYBScIT - Digital Electronics Practical 1

### Practical 1A: Study of Basic Logic Gates

#### Aim:
To study and verify the truth tables of basic logic gates: AND, OR, NOT, NAND, NOR, XOR, XNOR.

#### Apparatus:
IC 7400 (NAND), IC 7402 (NOR), IC 7404 (NOT), IC 7408 (AND), IC 7432 (OR), IC 7486 (XOR), Breadboard, 5V Supply, LEDs, Connecting wires.

#### Theory:

1.  **NOT Gate (IC 7404):** Single input, output is complement. Y = A'
2.  **AND Gate (IC 7408):** Output is high only if all inputs are high. Y = A.B
3.  **OR Gate (IC 7432):** Output is high if any input is high. Y = A+B
4.  **NAND Gate (IC 7400):** AND + NOT. Y = (A.B)'
5.  **NOR Gate (IC 7402):** OR + NOT. Y = (A+B)'
6.  **XOR Gate (IC 7486):** Output high if odd no of 1s. Y = A⊕B
7.  **XNOR Gate:** XOR + NOT. Y = (A⊕B)'

#### Truth Tables:

**NOT Gate:**
| A | Y |
|---|---|
| 0 | 1 |
| 1 | 0 |

**AND / OR / NAND / NOR / XOR / XNOR (2-Input):**
| A | B | AND | OR | NAND | NOR | XOR | XNOR |
|---|---|---|---|---|---|---|---|
| 0 | 0 | 0 | 0 | 1 | 1 | 0 | 1 |
| 0 | 1 | 0 | 1 | 1 | 0 | 1 | 0 |
| 1 | 0 | 0 | 1 | 1 | 0 | 1 | 0 |
| 1 | 1 | 1 | 1 | 0 | 0 | 0 | 1 |

#### Procedure:
1.  Place IC on breadboard.
2.  Connect VCC (Pin 14) to 5V and GND (Pin 7) to 0V.
3.  Give inputs A,B via switches.
4.  Observe output on LED.
5.  Verify truth table.

#### Conclusion:
All truth tables of basic gates are verified successfully.

#### Circuit Diagrams:
Refer images / Logisim Simulation