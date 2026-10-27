# BCD to 7-Segment Display

A digital logic circuit that converts **BCD (Binary-Coded Decimal)** input into signals for a **7-segment display**.

## Preview & Explanation

For a visual explanation of the complete logic circuit:

🔗 **[View the 7-Segment Logic Circuits](https://gates.darfurqan.com/7segment)**

## Logisim Circuit

The repository contains the Logisim circuit file for the BCD-to-7-segment decoder.

### Input
- 4-bit BCD input: `A B C D`
- Represents decimal digits `0–9`

### Output
- Seven outputs: `a b c d e f g`
- Controls the seven segments of the display.

## Truth Table

| Decimal | BCD | Display |
|---:|:---:|:---:|
| 0 | 0000 | 0 |
| 1 | 0001 | 1 |
| 2 | 0010 | 2 |
| 3 | 0011 | 3 |
| 4 | 0100 | 4 |
| 5 | 0101 | 5 |
| 6 | 0110 | 6 |
| 7 | 0111 | 7 |
| 8 | 1000 | 8 |
| 9 | 1001 | 9 |

BCD inputs `1010–1111` are unused/invalid decimal digits.

## Requirements

- [Logisim](https://sourceforge.net/projects/circuit/)
- Basic knowledge of Boolean algebra and logic gates

## Circuit File

Download or clone this repository and open the `.circ` file in Logisim.

---

Made for learning and practicing **Digital Electronics & Logic Circuits**.
