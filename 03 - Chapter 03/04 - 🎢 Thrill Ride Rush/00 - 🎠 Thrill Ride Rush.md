# 🎠 Thrill Ride Rush: Combine Rules with Logical Operators!

Welcome to the **Thrill Ride Rush**, where your Python programs become carnival operators, using **logical operators** to make complex decisions! 🎢 In **Fortune-Fun-Fair**, you used `random` to pick prizes—now you’ll combine conditions with `and`, `or`, and `not` to control carnival rides and games. These examples will show you how to use logical operators with `if` statements. Let’s ride into the fun! 🚂

## 📖 What Are Logical Operators?

**Logical operators** (also called Boolean operators) combine two or more conditions to return `True` or `False`. They’re perfect for checking multiple rules, like “Is the rider tall enough _and_ do they have a ticket?” The operators are:

- **and**: `True` if _both_ conditions are `True`, else `False`.
- **or**: `True` if _at least one_ condition is `True`, else `False`.
- **not**: `True` if the condition is `False`, and vice versa.

**Truth Table**:

|A|B|A and B|A or B|not A|
|---|---|---|---|---|
|False|False|False|False|True|
|False|True|False|True|True|
|True|False|False|True|False|
|True|True|True|True|False|

**Syntax**:

```python
if condition1 and condition2:
  # Code if both are True
elif condition1 or condition2:
  # Code if at least one is True
elif not condition:
  # Code if condition is False
```

**Key Rule**: Use **2-space indentation** for code inside `if`/`elif`/`else` (like in Fortune-Fun-Fair) to avoid SyntaxError or IndentationError (see Bug-Buster-Bonanza).

### Example 1: Bumper Car Access

```python
# Checking bumper car eligibility
age = int(input("Enter your age: "))
ticket = int(input("Enter your tickets: "))
if age >= 12 and ticket >= 2:
  print("Hop in the bumper cars!")
else:
  print("Sorry, you can't ride yet!")
```

**How It Works**:

- `int(input())` gets age and tickets (from Chatty-Code-Craze).
- `age >= 12 and ticket >= 2` is `True` only if _both_ conditions are `True` (e.g., age 15, tickets 3).
- If `True`, prints “Hop in the bumper cars!”; else, prints “Sorry, you can’t ride yet!”.

**Terminal View** (example with age 14, tickets 2):

```
Enter your age: 14
Enter your tickets: 2
Hop in the bumper cars!
```

### Example 2: Carnival Game Entry

```python
# Checking game booth entry
tokens = int(input("Enter your tokens: "))
friends = int(input("Enter number of friends: "))
if tokens > 5 or friends > 0:
  print("Welcome to the game booth!")
else:
  print("Need more tokens or a friend!")
```

**How It Works**:

- `tokens > 5 or friends > 0` is `True` if _either_ condition is `True` (e.g., tokens 3, friends 2).
- If `True`, prints “Welcome to the game booth!”; else, prints “Need more tokens or a friend!”.

**Terminal View** (example with tokens 2, friends 1):

```
Enter your tokens: 2
Enter number of friends: 1
Welcome to the game booth!
```

### Example 3: Ride Wait Check

```python
# Checking if waiting is needed
queue_full = input("Is the queue full? (yes/no): ") == "yes"
if not queue_full:
  print("Board the ride now!")
else:
  print("Wait for the next round!")
```

**How It Works**:

- `input() == "yes"` sets `queue_full` to `True` if user types “yes” (from Chem-Craze-Carnival).
- `not queue_full` is `True` if `queue_full` is `False` (e.g., user types “no”).
- If `True`, prints “Board the ride now!”; else, prints “Wait for the next round!”.

**Terminal View** (example with “no”):

```
Is the queue full? (yes/no): no
Board the ride now!
```

**Knowledge Nugget**: Logical operators work with any conditions, not just numbers! For example, `name == "Alex" and score > 10` combines a string comparison with a number check (from Data-Type-Disco). Always test both sides of `and`/`or` to ensure your logic is sound—use the truth table to predict outcomes!

**History Lesson**: Logical operators stem from Boolean algebra, developed by George Boole in the 1840s for logical reasoning. Python’s `and`, `or`, and `not`, introduced in 1991, made complex conditionals readable, unlike older languages with symbols like `&&` or `||`. Python’s clarity makes it noowbie-friendly for carnival-level fun!

## 💡 Tips for Logical Operator Success

- **Check Both Sides**: For `and`/`or`, ensure both conditions use correct relational operators (`>`, `==`, etc.) from Chem-Craze-Carnival.
- **Use not Sparingly**: `not` flips `True` to `False` (and vice versa), so test it carefully to avoid confusion.
- **Indent Consistently**: Use **2 spaces** for `if`/`elif`/`else` code to avoid IndentationError (see Bug-Buster-Bonanza).
- **Test All Cases**: Try inputs that hit each `if`/`elif`/`else` branch to verify logic (e.g., both conditions `True`, one `True`, both `False`).
- **Convert Inputs**: Use `int()` or `float()` for number inputs to avoid TypeError when comparing (from Chatty-Code-Craze).

## 🎯 What’s Next?

You’re ready to run the carnival rides! Head to the Exercises folder to create a `the_cyclone.py` program that checks roller coaster eligibility with logical operators. Test different inputs to master the rush! 🎟️

**Quick Challenge**: What’s the output if `score` is 20 and `time_left` is 5?

```python
score = 20
time_left = 5
if score > 15 and time_left > 0:
  print("Win a carnival prize!")
else:
  print("Try again!")
```

Try it in the exercises!

## ❓ Need Help?

If your ride logic derails, don’t stress! **Leave a comment** on this GitHub page or **join our Discord community** (link in the repo description) to ask questions and get help from other noowbies.

**Back to Topic Guide**: Thrill Ride Rush | **Main Guide**: Python for Noowbies