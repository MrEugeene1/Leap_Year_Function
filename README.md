# Leap Year Checker (Python)

## Overview
This project contains a simple Python implementation of a leap-year checker.
The function `is_year_leap(year)` returns:

- `True` if the input year is a leap year
- `False` otherwise

The script also includes a small built-in test loop to validate correctness against sample years.

## Leap Year Rules
A year is a leap year if:

1. It is divisible by `400`, or
2. It is divisible by `4` and not divisible by `100`

Otherwise, it is not a leap year.

## Project File
- `parameterized_6.py`: function implementation and test code.

## How to Run
From the project folder, run:

```bash
python parameterized_6.py
```

## Expected Output
```text
1900 -> OK
2000 -> OK
2016 -> OK
1987 -> OK
```

## Function Signature
```python
def is_year_leap(year):
	...
```

## Notes
- Input is expected to be an integer year.
- The included tests are minimal and intended as a quick verification.
# Leap_Year_Function
