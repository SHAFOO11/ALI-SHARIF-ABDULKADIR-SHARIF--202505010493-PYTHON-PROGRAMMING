# Week 5 - Tutorial 5 Documentation

## 1. Problem Analysis

### 1.1 Problem Statement
A café needs a program to automatically calculate customer bills
instead of doing it manually.

### 1.2 Inputs
- Customer name
- Quantity of Coffee ordered
- Quantity of Tea ordered
- Quantity of Sandwich ordered

### 1.3 Outputs
- A receipt showing customer name, quantities, and total bill

### 1.4 Process Flow
1. Ask the customer for their name
2. Ask how many of each item they ordered
3. Multiply each quantity by its price
4. Add everything together to get the total
5. Print the receipt

### 1.5 Constraints
- Quantities must be whole numbers (you can't order half a sandwich)
- Prices are fixed (Coffee=8.50, Tea=6.00, Sandwich=12.00)

## 2. Problem Decomposition
- Task 1: Get inputs from the user
- Task 2: Calculate the total bill (coffee + tea + sandwich)
- Task 3: Print a formatted receipt

## 3. Pseudocode
START
  GET customer name
  GET coffee quantity
  GET tea quantity
  GET sandwich quantity
  total = (coffee x 8.50) + (tea x 6.00) + (sandwich x 12.00)
  PRINT receipt with name, quantities, and total
END