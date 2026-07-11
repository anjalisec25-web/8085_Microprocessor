# Addition of Two 8-bit Numbers

## Aim

To add two 8-bit numbers using the 8085 microprocessor.

## Algorithm

1. Load the first number into the accumulator.
2. Load the second number into another register.
3. Add the two numbers.
4. Store the result in memory.
5. Stop the program.

## Program

```assembly
LDA 2500H
MOV B, A
LDA 2501H
ADD B
STA 2502H
HLT
```

## Explanation

| Instruction | Description |
|-------------|-------------|
| LDA 2500H | Load first number into A |
| MOV B, A | Copy first number to B |
| LDA 2501H | Load second number |
| ADD B | Add first number to A |
| STA 2502H | Store result |
| HLT | Stop execution |
