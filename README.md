# FizzBuzz Implementation

A simple Python implementation of the classic FizzBuzz programming challenge that prints numbers from 1 to 100, replacing multiples of 3 with "Fizz", multiples of 5 with "Buzz", and multiples of both with "FizzBuzz".

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)

## Description
This project implements the FizzBuzz challenge, a common programming task often used in software developer job interviews. The program iterates through numbers 1 to 100 and applies the following rules:
- Prints "FizzBuzz" if the number is divisible by both 3 and 5
- Prints "Fizz" if the number is divisible by 3
- Prints "Buzz" if the number is divisible by 5
- Prints the number itself if none of the above conditions are met

## Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/fizzbuzz.git
```
2. No additional dependencies are required as this project uses only Python's built-in functionality.

## Usage
To run the FizzBuzz program, simply execute the Python script:
python fizzbuzz.py
```
Example output:
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
...

```
## How It Works
The core logic of the program is implemented as follows:

```python
for num in range(1, 101):
    # "FizzBuzz" if number is divisible by both 3 and 5
    if num % 3 == 0 and num % 5 == 0:
        print("FizzBuzz")
    # "Fizz" if divisible by 3
    elif num % 3 == 0:
        print("Fizz")
    # "Buzz" if divisible by 5
    elif num % 5 == 0:
        print("Buzz")
    # The number itself if none of above conditions met
    else:
        print(num)
```

## Contribution
Feel free to improve this implementation by:

1. Suggesting improvements in code efficiency
2. Adding comments for better code understanding
3. Fixing any bugs you find
