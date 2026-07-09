# Find the Largest of Two Numbers

## Aim

To find the largest of two 8-bit numbers using the 8085 microprocessor.

## Algorithm

1. Load the first number.
2. Compare it with the second number.
3. If the first number is larger, store it.
4. Otherwise, store the second number.
5. Stop the program.

## Program

```assembly
LDA 2500H
MOV B, A
LDA 2501H
CMP B
JC STORE
STA 2502H
HLT

STORE:
MOV A, B
STA 2502H
HLT
```

## Explanation

| Instruction | Description |
|-------------|-------------|
| LDA | Load data into A |
| MOV | Copy data |
| CMP | Compare values |
| JC | Jump if carry |
| STA | Store result |
| HLT | Stop execution |