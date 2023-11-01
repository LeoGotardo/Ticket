# Fine Calculation Application - Documentation

## Introduction

This Python program is an application that calculates the fine amount based on the number of cards a user has received. The first card is free, and the subsequent cards have a fine amount of $500 each, forming an arithmetic progression (AP).

## How to Use

1. Run the program in your preferred Python environment.
2. Enter the total number of cards the user has received when prompted by the application.
3. The application will calculate and display the fine for each card, as well as the total fine amount.

## Program Logic

- The program consists of a single function:

### 1. `main()`

- This is the main function that performs the fine calculation based on the number of cards received by the user.
- It takes the input for the total number of cards (`cartao`) received by the user.
- The variable `cartao_main` is calculated by subtracting 2 from the total number of cards, as the first card is free and already accounted for in the initial loop.
- Two loops are used: 
  - The first loop prints the fine amount (0) for the first and second cards, as they are free.
  - The second loop calculates the fine for the remaining cards and prints the fine amount for each card in the sequence.
- The total fine amount (`Soma`) is calculated using the formula for the sum of an arithmetic progression.
- Finally, the program displays the total fine amount.

## Example Usage

```
Digite a quantidade total de cartões : 6
Cartão 1º  : 0
Cartão 2º  : 0
Cartão 3º  : 500
Cartão 4º  : 1000
Cartão 5º  : 1500
Cartão 6º  : 2000
Total R$ :  3000.0
```

## Note

- The program demonstrates a simple fine calculation application based on the number of cards received, using an arithmetic progression for the fine amounts.
- The input validation is minimal in this implementation. In a real-world application, proper validation for the input value (e.g., non-negative integer) should be implemented for robustness.