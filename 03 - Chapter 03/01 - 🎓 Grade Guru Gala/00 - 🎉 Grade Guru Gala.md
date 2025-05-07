# 🎉 Grade Guru Gala: Make Decisions with If/Else!

Welcome to the **Grade Guru Gala**, where your Python programs become festival judges, making decisions with **if** and **else** statements! 🎓 In **Fork-Frenzy-Fiesta**, you used `if`/`else` to flip coins—now you’ll dive deeper, checking conditions to award prizes or plan festival fun. These examples will show you how to use `if`/`else`, indent like a pro, and compare values at the school festival. Let’s get the gala started! 🚀

## 📖 What Are If/Else Statements?

An **if** statement checks a condition (like “Is the score high enough?”). If the condition is **true**, it runs the code inside. If it’s **false**, an **else** clause (optional) runs different code. It’s like deciding who wins a festival game based on their points.

**Syntax**:

```python
if condition:
  # Code if true (indented)
else:
  # Code if false (indented)
```

**Key Rule**: Code inside `if` or `else` must be **indented** (2 spaces, as you’ll do in the exercise) to tell Python what’s part of the block. No indentation = SyntaxError (see Bug Buster Bonanza)!

### Example 1: Festival Points Prize

```python
# Awarding festival prizes
points = 75
if points >= 50:
  print("You win a festival badge!")
else:
  print("Try again for a prize!")
```

**How It Works**:

- `points >= 50` checks if `points` is 50 or more (using `>=` from Math Magic Mix).
- Since `points` is 75, the condition is **true**, so it prints “You win a festival badge!”.
- If `points` was 40, it would print “Try again for a prize!”.

**Output**: `You win a festival badge!`

### Example 2: Quiz Score Check with Input

```python
# Checking a quiz score
score = int(input("Enter your quiz score (0-100): "))
if score > 80:
  print("Awesome, you get a festival star!")
else:
  print("Good effort, keep studying!")
```

**How It Works**:

- `int(input())` gets a number from the user (from Chatty Code Craze).
- `score > 80` checks if the score is above 80.
- If true, it awards a star; otherwise, it encourages studying.

**Terminal View** (if user types “90”):

```
Enter your quiz score (0-100): 90
Awesome, you get a festival star!
```

**Knowledge Nugget**: Comparison operators (`>`, `<`, `>=`, `<=`, `==`, `!=`) are your `if` statement’s best friends. They compare numbers, strings, or variables. For example, `!=` means “not equal” (e.g., `score != 100` checks if the score isn’t 100). Review Math Magic Mix for more!

### Example 3: Festival Schedule Planner

```python
# Planning festival activities
time = float(input("Enter the hour (0-24): "))
if time < 12.0:
  print("Join the morning parade!")
else:
  print("Head to the afternoon games!")
```

**How It Works**:

- `float(input())` gets a decimal hour (from Money Mix Mania).
- `time < 12.0` checks if it’s before noon.
- If true, it suggests the parade; otherwise, it picks games.

**Terminal View** (if user types “14.5”):

```
Enter the hour (0-24): 14.5
Head to the afternoon games!
```

**Why Indentation Matters**: Python uses indentation to group code. If you forget to indent or use the wrong number of spaces, you’ll get a SyntaxError or IndentationError. Stick to 2 spaces for this exercise, as requested!

**History Lesson**: The `if` statement’s roots trace to 1950s languages like ALGOL, which used conditionals for scientific calculations. Python’s clean `if`/`else` syntax, introduced in 1991, was designed to be readable, with indentation replacing curly braces (unlike C or Java). This makes Python’s control flow noowbie-friendly but strict about spacing!

## 💡 Tips for If/Else Success

- **Indent Consistently**: Use 2 spaces for `if`/`else` code, as specified. Mixing spaces or tabs causes errors (see Bug Buster Bonanza).
- **Test Both Paths**: Try values that trigger both `if` and `else` to check your logic.
- **Use Clear Conditions**: Operators like `>=` or `<` make conditions precise. Double-check your comparisons!
- **Handle Inputs**: If using `input()`, convert to `int()` or `float()` for numbers, or you’ll get a TypeError when comparing.

## 🎯 What’s Next?

You’re ready to shine at the festival! Head to the Exercises folder to create a `grades.py` program that checks test scores with `if`/`else`. Test it with different scores to become a grade guru! 🏅

**Quick Challenge**: What’s the output if `tickets` is 30?

```python
tickets = 30
if tickets >= 25:
  print("You get a festival wristband!")
else:
  print("Not enough for a wristband.")
```

Try it in the exercises!

## ❓ Need Help?

If your code doesn’t win a festival prize, don’t stress! **Leave a comment** on this GitHub page or **join our Discord community** (link in the repo description) to ask questions and get help from other noowbies.

**Back to Topic Guide**: Grade Guru Gala | **Main Guide**: Python for Noowbies