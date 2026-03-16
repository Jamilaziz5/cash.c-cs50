# cash.c-cs50 

A greedy algorithm program written in C as part of Harvards's CS50x. 

## What it does 
Prompts the user for an amount of change 
owed in cents, then
calculates the minimum nuber of coins needed to make that change 
using quarters, dimes, nickles, and pennies 

## How to run 
1. Compile: 'make cash'
2. Run: './cash'
3. Enter the amount of change owed in cents when prompted

## Example output 
Change owed: 41 
4 

## How it works 
The program uses a greedy algorithm - it 
always picks the largest 
coin possibel first, reducing the 
remaining amount until it reaches zer. 

## Built with 
- c
- CS50 library
