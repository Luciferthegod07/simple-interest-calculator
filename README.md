# Simple Interest Calculator

This project is a simple interest calculator that calculates the simple interest based on principal amount, rate of interest, and time.

## Formula

Simple Interest = (Principal × Rate × Time) / 100

## Inputs
- Principal (P): The initial amount of money
- Rate (R): Rate of interest per year
- Time (T): Time period in years

## Output
- Simple Interest value

## Example

If  
Principal = 1000  
Rate = 5%  
Time = 2 years  

Then  
Simple Interest = (1000 × 5 × 2) / 100 = 100  

## Sample Code (Python)

```python
p = float(input("Enter principal: "))
r = float(input("Enter rate: "))
t = float(input("Enter time: "))

si = (p * r * t) / 100
print("Simple Interest =", si)