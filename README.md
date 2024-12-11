# FizzBuzz Program
A Python program that prints numbers 1-100, replacing multiples of 3 with "Fizz", multiples of 5 with "Buzz", and multiples of both with "FizzBuzz".

## How to Run
1. Save the code as `fizzbuzz.py`
2. Run with Python: `python fizzbuzz.py`

## Code
```python
for num in range(1, 101):
    if num % 3 == 0 and num % 5 == 0:
        print('FizzBuzz')
    elif num % 3 == 0:
        print('Fizz')
    elif num % 5 == 0:
        print('Buzz')
    else:
        print(num)

##Screenshot
![image](https://github.com/user-attachments/assets/a0a7e2ee-19d5-4059-a596-8f9307138566)
