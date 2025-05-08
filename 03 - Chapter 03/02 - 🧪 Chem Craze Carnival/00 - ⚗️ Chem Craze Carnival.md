# ⚗️ Chem Craze Carnival: Compare & Choose with Relational Operators & Elif!

Welcome to the **Chem Craze Carnival**, where your Python programs become lab scientists, comparing values with **relational operators** and making choices with **elif** statements! 🧪 In **Grade-Guru-Gala**, you used `if`/`else` to check grades—now you’ll compare multiple conditions to sort potions and run experiments. These examples will show you how to use operators like `==` and `elif` to brew brilliant code. Let’s spark some reactions! 🔥

## 📖 What Are Relational Operators & Elif?

**Relational operators** compare two values and return `True` or `False`. They’re the heart of `if`/`elif` conditions, like checking if a potion’s strength matches a recipe. The operators are:

- `==`: Equal to (e.g., `x == 5` checks if `x` is 5).
- `!=`: Not equal to (e.g., `x != 5` checks if `x` isn’t 5).
- `>`: Greater than.
- `<`: Less than.
- `>=`: Greater than or equal to.
- `<=`: Less than or equal to.

An **elif** statement (short for “else if”) adds extra conditions between `if` and `else`. Python checks conditions in order, and **only one** `if`/`elif`/`else` block runs—the first one that’s `True`.

**Syntax**:

```python
if condition1:
  # Code if condition1 is True
elif condition2:
  # Code if condition2 is True
else:
  # Code if all conditions are False
```

**Key Rule**: Use **2-space indentation** for code inside `if`, `elif`, and `else` (like in Grade Guru Gala) to avoid SyntaxError or IndentationError (see Bug Buster Bonanza).

### Example 1: Potion Strength Tester

```python
# Testing potion strength
strength = 8
if strength > 10:
  print("Super strong potion!")
elif strength > 5:
  print("Medium strength potion!")
else:
  print("Weak potion!")
```

**How It Works**:

- `strength > 10` checks if `strength` is above 10. It’s 8, so `False`.
- `elif strength > 5` checks if `strength` is above 5. It’s 8, so `True`, and prints “Medium strength potion!”.
- The `else` is skipped because an `elif` was `True`.
- **Only one block runs**, even if multiple conditions could be true.

**Output**: `Medium strength potion!`

### Example 2: Lab Temperature Guide

```python
# Guiding lab experiments
temp = float(input("Enter lab temperature (Celsius): "))
if temp < 0:
  print("Freeze the sample!")
elif temp <= 25:
  print("Room temperature—mix the potion!")
elif temp < 100:
  print("Heat the solution carefully!")
else:
  print("Boiling! Turn off the burner!")
```

**How It Works**:

- `float(input())` gets a temperature (from Money Mix Mania).
- Conditions are checked in order:
    - `temp < 0`: False if temp is 20.
    - `temp <= 25`: True if temp is 20, so prints “Room temperature—mix the potion!”.
    - Later `elif` and `else` are skipped.
- Only the **first true condition** runs.

**Terminal View** (if user types “20”):

```
Enter lab temperature (Celsius): 20
Room temperature—mix the potion!
```

**Knowledge Nugget**: Order matters in `if`/`elif`! Python stops at the first `True` condition. In the grade example you saw (`if grade > 90`, `elif grade > 80`, etc.), a grade of 95 triggers only the `A` block, not `B`, because `> 90` comes first. Always arrange conditions from most specific to least!

### Example 3: Chemical Match Check

```python
# Checking chemical formulas
chemical = input("Enter chemical symbol: ")
if chemical == "H2O":
  print("Water detected!")
elif chemical != "CO2":
  print("Not carbon dioxide—test further!")
else:
  print("Carbon dioxide detected!")
```

**How It Works**:

- `input()` gets a string (from Chatty Code Craze).
- `chemical == "H2O"` checks for an exact match (case-sensitive).
- `elif chemical != "CO2"` runs if it’s not “CO2”.
- `else` runs only if the chemical is “CO2”.

**Terminal View** (if user types “N2”):

```
Enter chemical symbol: N2
Not carbon dioxide—test further!
```

**History Lesson**: Relational operators like `==` and `<` originated in 1950s languages like Fortran, used for math and science. Python’s `elif`, introduced in 1991, was inspired by C’s `else if` but made simpler with indentation. Unlike older languages with cryptic symbols, Python’s readable syntax makes comparisons fun for noowbies!

## 💡 Tips for Relational Operators & Elif

- **Use the Right Operator**: Choose `==` for equality, `>` for greater, etc. Mixing them up (e.g., `=` instead of `==`) causes errors (see Bug Buster Bonanza).
- **Order Conditions**: Place stricter conditions (e.g., `> 10`) before looser ones (e.g., `> 5`) in `elif` chains.
- **Indent Consistently**: Use **2 spaces** for `if`/`elif`/`else` code to avoid IndentationError.
- **Test All Paths**: Try inputs that hit each `if`, `elif`, and `else` to ensure logic works.
- **Handle Inputs**: Convert `input()` to `float()` for decimals or `int()` for whole numbers to avoid TypeError.

## 🎯 What’s Next?

You’re ready to brew some coding potions! Head to the Exercises folder to create a `ph_levels.py` program that tests pH levels with `if`/`elif`/`else`. Experiment with different values to master the carnival! 🧫

**Quick Challenge**: What’s the output if `bubbles` is 3?

```python
bubbles = 3
if bubbles > 5:
  print("Fizzy potion!")
elif bubbles >= 2:
  print("Sparkling potion!")
else:
  print("Flat potion!")
```

Try it in the exercises!

## ❓ Need Help?

If your potions don’t fizz, don’t stress! **Leave a comment** on this GitHub page or **join our Discord community** (link in the repo description) to ask questions and get help from other noowbies.

**Back to Topic Guide**: Chem Craze Carnival | **Main Guide**: Python for Noowbies