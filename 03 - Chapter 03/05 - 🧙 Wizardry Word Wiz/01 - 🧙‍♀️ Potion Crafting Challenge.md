# 🧙‍♀️ Potion Crafting Challenge: Brew Magical Potions!

It’s time to wield magic at the **Wizardry Word Wiz**! ✨ In this folder, you’ll create a `potion_crafter.py` program that uses **control flow** to become a master potion brewer. You’ll ask users three questions, update potion scores using `if`/`elif`/`else`, and print the results. Grab your cauldron and let’s brew some enchanted potions! 🧪

## 📋 Instructions

Follow these steps to complete the main exercise and try the bonus challenge. Use VS Code, an online IDE (like Replit), or any Python environment (check Gear Up for Coding Magic for setup help).

### Exercise 1: Create a Potion Crafting Quiz

Your mission is to create a `potion_crafter.py` program that:

- Initializes scores for four potion types (Strength, Wisdom, Harmony, Stealth) to 0.
- Asks the user three questions with `int()` and `input()`, updating potion scores based on answers:
    - **Q1: Which magical ingredient inspires you?**
        - Dragon Scale: Strength +1, Wisdom +1
        - Moonflower: Harmony +1, Stealth +1
        - Else: Print “Invalid ingredient.”
    - **Q2: What’s your brewing style?**
        - Precise: Wisdom +2
        - Bold: Strength +2
        - Gentle: Harmony +2
        - Secretive: Stealth +2
        - Else: Print “Invalid style.”
    - **Q3: Which cauldron material do you prefer?**
        - Iron: Strength +4
        - Silver: Wisdom +4
        - Copper: Harmony +4
        - Obsidian: Stealth +4
        - Else: Print “Invalid material.”
- Prints the final score for each potion type in the format:

```
Strength: [score]
Wisdom: [score]
Harmony: [score]
Stealth: [score]
```

- Tests the program with different answer combinations to ensure it works.

Here’s how to do it:

1. **Create a File**:
    
    - Open VS Code or your IDE.
    - Create a new file called `potion_crafter.py` (use the sample file in this folder).
2. **Write the Code**:
    
    - Start with a comment, like:
        
        ```python
        # Brewing potions with magical code!
        ```
        
    - Use `input()`, `int()`, `if`/`elif`/`else`, and variables:
        
        ```python
        strength = 0
        wisdom = 0
        harmony = 0
        stealth = 0
        
        # Question 1
        q1 = int(input("Which magical ingredient inspires you?\n1) Dragon Scale\n2) Moonflower\n"))
        if q1 == 1:
          strength += 1
          wisdom += 1
        elif q1 == 2:
          harmony += 1
          stealth += 1
        else:
          print("Invalid ingredient.")
        
        # Question 2
        q2 = int(input("What’s your brewing style?\n1) Precise\n2) Bold\n3) Gentle\n4) Secretive\n"))
        if q2 == 1:
          wisdom += 2
        elif q2 == 2:
          strength += 2
        elif q2 == 3:
          harmony += 2
        elif q2 == 4:
          stealth += 2
        else:
          print("Invalid style.")
        
        # Question 3
        q3 = int(input("Which cauldron material do you prefer?\n1) Iron\n2) Silver\n3) Copper\n4) Obsidian\n"))
        if q3 == 1:
          strength += 4
        elif q3 == 2:
          wisdom += 4
        elif q3 == 3:
          harmony += 4
        elif q3 == 4:
          stealth += 4
        else:
          print("Invalid material.")
        
        # Print scores
        print("Strength:", strength)
        print("Wisdom:", wisdom)
        print("Harmony:", harmony)
        print("Stealth:", stealth)
        ```
        
    - Use **2-space indentation** for code inside `if`/`elif`/`else`, as in previous topics.
        
3. **Run the Program**:
    
    - In VS Code, click the “Run” triangle or right-click and select “Run Python File in Terminal”.
        
    - In an online IDE, hit the “Run” button.
        
    - In a terminal, navigate to the folder and run:
        
        ```bash
        python3 potion_crafter.py
        ```
        
4. **Test Different Inputs**:
    
    - Run the program with answer combinations like:
        - 1, 2, 1 (Dragon Scale, Bold, Iron): Strength +7 (1+2+4), Wisdom +1, Harmony 0, Stealth 0
        - 2, 3, 3 (Moonflower, Gentle, Copper): Harmony +7 (1+2+4), Stealth +1, Strength 0, Wisdom 0
        - 1, 1, 2 (Dragon Scale, Precise, Silver): Wisdom +7 (1+2+4), Strength +1, Harmony 0, Stealth 0
        - 5, 5, 5 (invalid): Prints “Invalid [ingredient/style/material].” for each
    - Check the output matches the scoring rules.

**Expected Output** (example with 1, 2, 1):

```
Which magical ingredient inspires you?
1) Dragon Scale
2) Moonflower
1
What’s your brewing style?
3) Precise
4) Bold
5) Gentle
6) Secretive
2
Which cauldron material do you prefer?
7) Iron
8) Silver
9) Copper
10) Obsidian
1
Strength: 7
Wisdom: 1
Harmony: 0
Stealth: 0
```

**Sample File**: Check out `potion_crafter.py` in this folder for the code or use it to test.

**Share the Magic**: Save a screenshot of your potion crafting outputs and share it with friends or post it on X with #PythonForNoowbies to show off your brewing skills!

### Exercise 2: Bonus Challenge

Want to make your potion crafting legendary? Add a feature to print the potion type with the most points! Create a new file (e.g., `my_potion_crafter.py`) or edit `potion_crafter.py`.

- After printing scores, use `if`/`elif`/`else` to find the potion type with the highest score.
- Print in the format:

```
Best Potion: [Potion Type]
```

- If there’s a tie, choose one potion type or (stretch goal) list all tied types.
- Example approach:

```python
if strength >= wisdom and strength >= harmony and strength >= stealth:
  print("Best Potion: Strength")
elif wisdom >= strength and wisdom >= harmony and wisdom >= stealth:
  print("Best Potion: Wisdom")
# Add for Harmony, Stealth
```

**Sample Output** (for above example):

```
Strength: 7
Wisdom: 1
Harmony: 0
Stealth: 0
Best Potion: Strength
```

## 💡 Tips for Potion Crafting Success

- **Initialize Scores**: Set all potion scores to 0 at the start (from Data-Type-Disco).
- **Use int()**: Convert `input()` to `int()` for numbers to avoid TypeError (from Chatty-Code-Craze).
- **Check Inputs**: Use `elif` for valid options (1, 2, etc.) and `else` for “Invalid [ingredient/style/material].” (from Chem-Craze-Carnival).
- **Indent Properly**: Use **2 spaces** for `if`/`elif`/`else` code to avoid IndentationError (see Bug-Buster-Bonanza).
- **Test All Cases**: Try valid answers (e.g., 1, 2) and invalid (e.g., 5, “abc”) to ensure correct scoring and error messages.
- **Track Scores**: Update scores carefully (e.g., `+= 1`) to avoid logic errors (from Math-Magic-Mix).
- **Bonus Logic**: For the bonus, compare all scores with `and` (from Thrill-Ride-Rush) to find the highest.

## 🎯 Did It Work?

- Did your `potion_crafter.py` print correct potion scores for different answers? If yes, you’re a magical brewing champion! 🌟
- If not, check your `int()` conversions, `elif` conditions, and indentation (2 spaces). Confirm Python is set up (see Gear Up for Coding Magic).

## ❓ Need Help?

If your potion brewing bubbles over, don’t fret! **Leave a comment** on this GitHub page or **join our Discord community** (link in the repo description) to get help from other noowbies and code wizards.

## 🛠️ What’s Next?

You’ve mastered potion crafting—way to enchant the wizarding world! 🎆 Head back to the Wizardry Word Wiz guide to review, or check the Python for Noowbies main guide for bonus content or future chapters.

**Super Challenge**: Can you add a comment with a magical vibe, like `# Brewing potions with code!`? Try the bonus challenge to find the top potion type and keep the magic flowing! 😺

**Back to Topic Guide**: Wizardry Word Wiz | **Main Guide**: Python for Noowbies