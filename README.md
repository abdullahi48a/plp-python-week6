# Week 6 Assignment: Safe Functions with try/except

## Files

- safe_tools.py: Contains safe functions for division, number conversion, and dictionary lookups.
- README.md: Describes the assignment and explains the use of try/except.

## Reflection

An if check cannot catch "abc" because int("abc") raises a ValueError during conversion. Using try/except allows the program to handle this error without crashing.