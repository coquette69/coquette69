import random

def choose_multiplier():
    multiplier = random.choice([1, 2, *range(6, 31)])
    return multiplier

def choose_number():
    number = random.choice([*range(1, 16), *range(16, 31)])
    return number

# Usage example:
multiplier = choose_multiplier()
number = choose_number()

print("Multiplier:", multiplier)
print("Number:", number)
```
