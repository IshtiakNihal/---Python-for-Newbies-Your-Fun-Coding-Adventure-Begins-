# 🪄 Wizardry Word Wiz: Master Control Flow Magic!

Welcome to the **Wizardry Word Wiz**, where your Python programs become magical Sorting Hats, using **control flow** to make decisions! 🧙 In Chapter 3, you’ve learned `if`/`else` (**Fork-Frenzy-Fiesta**), relational operators and `elif` (**Chem-Craze-Carnival**), logical operators (**Thrill-Ride-Rush**), and randomness (**Fortune-Fun-Fair**). Now, you’ll combine them to create a Hogwarts quiz. These examples show how to use `if`, `elif`, `else`, relational, and logical operators together. Let’s cast some coding spells! ✨

## 📖 Recap: Control Flow Essentials

**Control flow** determines the order your code runs, using:

- **if/elif/else**: Tests conditions and runs code if `True` (**Fork-Frenzy-Fiesta**, **Grade-Guru-Gala**).
- **Relational operators**: Compare values (`==`, `!=`, `>`, `>=`, `<`, `<=`) (**Chem-Craze-Carnival**).
- **Logical operators**: Combine conditions (`and`, `or`, `not`) (**Thrill-Ride-Rush**).

**Syntax**:

```python
if condition1 and condition2:
  # Code if both True
elif condition3 or condition4:
  # Code if at least one True
else:
  # Code if none True
```

**Key Rule**: Use **2-space indentation** for code inside `if`/`elif`/`else` (like in Thrill-Ride-Rush) to avoid SyntaxError or IndentationError (see Bug-Buster-Bonanza).

### Example 1: Spell Casting Check

```python
# Checking spell casting eligibility
wand = input("Have a wand? (yes/no): ") == "yes"
if wand:
  skill = int(input("Enter spell skill (1-10): "))
  if skill >= 7:
    print("Cast a powerful spell!")
  elif skill >= 4:
    print("Cast a basic spell.")
  else:
    print("Practice your spellwork!")
else:
  print("Get a wand first!")
```

**How It Works**:

- Outer `if`: Checks if `wand` is `True` (user types “yes”).
- Inner `if`/`elif`/`else`: If `wand` is `True`, checks `skill` (from Chatty-Code-Craze).
- Outputs:
    - “Cast a powerful spell!” if wand and skill ≥ 7.
    - “Cast a basic spell.” if wand and 4 ≤ skill < 7.
    - “Practice your spellwork!” if wand and skill < 4.
    - “Get a wand first!” if no wand.

**Terminal View** (example with “yes”, 5):

```
Have a wand? (yes/no): yes
Enter spell skill (1-10): 5
Cast a basic spell.
```

### Example 2: Potion Brewing Score

```python
# Scoring potion brewing
ingredients = int(input("Enter ingredients ready (0-5): "))
if ingredients >= 3:
  technique = input("Is technique correct? (yes/no): ") == "yes"
  if ingredients == 5 and technique:
    print("Perfect potion!")
  elif ingredients >= 4 or technique:
    print("Good potion!")
  else:
    print("Potion needs work.")
else:
  print("Gather more ingredients!")
```

**How It Works**:

- Outer `if`: Checks if `ingredients` ≥ 3.
- Inner `if`/`elif`/`else`: If enough ingredients, checks `ingredients` and `technique`.
- Uses `and` and `or` (from Thrill-Ride-Rush).
- Outputs:
    - “Perfect potion!” if 5 ingredients and correct technique.
    - “Good potion!” if ≥4 ingredients or correct technique.
    - “Potion needs work.” if 3 ingredients and wrong technique.
    - “Gather more ingredients!” if <3 ingredients.

**Terminal View** (example with 4, “yes”):

```
Enter ingredients ready (0-5): 4
Is technique correct? (yes/no): yes
Good potion!
```

### Example 3: Quidditch Team Selection

```python
# Selecting Quidditch players
speed = int(input("Enter broom speed (1-10): "))
if speed >= 6:
  accuracy = int(input("Enter goal accuracy (1-10): "))
  if accuracy > speed:
    print("Join as Chaser!")
  elif accuracy == speed:
    print("Join as Seeker!")
  else:
    print("Join as Beater!")
else:
  print("Train your broom speed!")
```

**How It Works**:

- Outer `if`: Checks if `speed` ≥ 6.
- Inner `if`/`elif`/`else`: If speed is enough, compares `accuracy` to `speed` using relational operators (`>`, `==`).
- Outputs:
    - “Join as Chaser!” if accuracy > speed.
    - “Join as Seeker!” if accuracy == speed.
    - “Join as Beater!” if accuracy < speed.
    - “Train your broom speed!” if speed < 6.

**Terminal View** (example with 7, 8):

```
Enter broom speed (1-10): 7
Enter goal accuracy (1-10): 8
Join as Chaser!
```

**Knowledge Nugget**: Control flow with `if`/`elif`/`else` and operators mimics decision trees in real-world apps, like game AI (e.g., choosing a Hogwarts house) or chatbots. Python’s clear syntax, introduced in 1991, makes combining conditions easier than in older languages like C, which used complex `switch` statements.

**History Lesson**: The concept of control flow dates to the 1940s with early computers like ENIAC, where programmers wired decision paths. Structured programming (1960s, Edsger Dijkstra) formalized `if`/`else`, inspiring Python’s readable control flow. The Sorting Hat’s logic resembles early expert systems, like MYCIN (1970s), which used rule-based decisions for medical diagnoses.

## 💡 Tips for Control Flow Success

- **Check Inputs**: Use `int()` for numbers to avoid TypeError (from Chatty-Code-Craze).
- **Indent Consistently**: Use **2 spaces** for `if`/`elif`/`else` code to avoid IndentationError (see Bug-Buster-Bonanza).
- **Test All Cases**: Try valid and invalid inputs to ensure `elif` and `else` handle all scenarios (from Chem-Craze-Carnival).
- **Use Logical Operators**: Combine conditions with `and`/`or` for efficiency (from Thrill-Ride-Rush).
- **Track Variables**: Update scores carefully to avoid logic errors when accumulating values.

## 🎯 What’s Next?

You’re ready to sort wizards! Head to the Exercises folder to create a `sorting_hat.py` program that uses control flow to assign Hogwarts houses. Test different answers to cast your sorting spell! 🧙‍♂️

**Quick Challenge**: What’s the output if `magic` is 8 and `charm` is 8?

```python
magic = int(input("Enter magic level (1-10): "))
if magic >= 7:
  charm = int(input("Enter charm level (1-10): "))
  if charm > magic:
    print("Charm Wizard!")
  elif charm == magic:
    print("Balanced Wizard!")
  else:
    print("Magic Specialist!")
else:
  print("Study more magic!")
```

Try it in the exercises!

## ❓ Need Help?

If your wizard logic wanders, don’t stress! **Leave a comment** on this GitHub page or **join our Discord community** (link in the repo description) to ask questions and get help from other noowbies.

**Back to Topic Guide**: Wizardry Word Wiz | **Main Guide**: Python for Noowbies