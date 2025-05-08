# 🧫 pH Tester Challenge: Brew the Perfect Potion!

It’s time to light up the **Chem Craze Carnival**! 🎡 In this folder, you’ll create a `ph_levels.py` program that uses `if`/`elif`/`else` statements to classify a liquid’s pH as basic, acidic, or neutral. You’ll harness relational operators to compare pH values and make decisions, like a master chemist in a coding lab. Let’s mix some magic! ⚗️

## 📋 Instructions

Follow these steps to complete the main exercise and try the extra challenges. Use VS Code, an online IDE (like Replit), or any Python environment (check Gear Up for Coding Magic for setup help).

### Exercise 1: Test pH Levels

Your mission is to create a `ph_levels.py` program that:

- Creates a `ph` variable using user input (between 0 and 14).
- Uses `if`/`elif`/`else` to check the pH value.
- Prints “Basic” if pH > 7, “Acidic” if pH < 7, or “Neutral” if pH = 7.
- Tests the program with different pH values to ensure it works.

Here’s how to do it:

1. **Create a File**:
    
    - Open VS Code or your IDE.
    - Create a new file called `ph_levels.py` (use the sample file in this folder).
2. **Write the Code**:
    
    - Start with a comment, like:
        
        ```python
        # Testing pH in the coding lab!
        ```
        
    - Create a `ph` variable with `input()` and add `if`/`elif`/`else`:
        
        ```python
        ph = float(input("Enter pH level (0-14): "))
        if ph > 7:
          print("Basic")
        elif ph < 7:
          print("Acidic")
        else:
          print("Neutral")
        ```
        
    - Use **2-space indentation** for code inside `if`, `elif`, and `else`, as in Grade Guru Gala.
        
3. **Run the Program**:
    
    - In VS Code, click the “Run” triangle or right-click and select “Run Python File in Terminal”.
        
    - In an online IDE, hit the “Run” button.
        
    - In a terminal, navigate to the folder and run:
        
        ```bash
        python3 ph_levels.py
        ```
        
4. **Test Different pH Values**:
    
    - Run the program and enter pH values like 8, 6, 7, 12, 3.
    - Check the output:
        - pH > 7 (e.g., 8): “Basic”
        - pH < 7 (e.g., 6): “Acidic”
        - pH = 7: “Neutral”

**Expected Output** (example with input “6”):

```
Enter pH level (0-14): 6
Acidic
```

**Sample File**: Check out `ph_levels.py` in this folder for the code or use it to test.

**Share the Spark**: Save a screenshot of your outputs for different pH values and share it with friends or post it on X with #PythonForNoowbies to show off your chemistry skills!

### Exercise 2: Extra Challenges

Want to keep the carnival bubbling? Try these tasks! Create a new file (e.g., `my_chem.py`) or edit `ph_levels.py`.

1. **Fancy pH Report**:
    
    - Add a lab-themed border:
        
        ```python
        print("~~~ pH Test Result ~~~")
        print("Basic")
        print("~~~ pH Test Result ~~~")
        ```
        
2. **Detailed Output**:
    
    - Include the pH value in the output:
        
        ```python
        ph = float(input("Enter pH level (0-14): "))
        if ph > 7:
          print(f"pH {ph} is Basic")
        elif ph < 7:
          print(f"pH {ph} is Acidic")
        else:
          print(f"pH {ph} is Neutral")
        ```
        
3. **More pH Categories**:
    
    - Add `elif` for strong/weak acids/bases:
        
        ```python
        ph = float(input("Enter pH level (0-14): "))
        if ph > 10:
          print("Strong Base")
        elif ph > 7:
          print("Weak Base")
        elif ph < 4:
          print("Strong Acid")
        elif ph < 7:
          print("Weak Acid")
        else:
          print("Neutral")
        ```
        
4. **Input Validation**:
    
    - Check if pH is 0–14 using `if` (hint: we’ll cover nested `if` later):
        
        ```python
        ph = float(input("Enter pH level (0-14): "))
        if ph >= 0 and ph <= 14:
          if ph > 7:
            print("Basic")
          elif ph < 7:
            print("Acidic")
          else:
            print("Neutral")
        else:
          print("Invalid pH! Enter 0-14.")
        ```
        

## 💡 Tips for pH-Testing Success

- **Indent Properly**: Use **2 spaces** for `if`/`elif`/`else` code to avoid IndentationError (see Bug Buster Bonanza).
- **Use float()**: pH values can be decimals (e.g., 7.5), so use `float(input())` (from Money Mix Mania).
- **Test All Cases**: Try pH values like 8 (Basic), 6 (Acidic), 7 (Neutral), and decimals (e.g., 7.1).
- **Check Operators**: Use `>` and `<` correctly for pH comparisons. `== 7` works for Neutral, but `elif ph == 7` is optional since `else` covers it.
- **One Block Runs**: Only one `if`/`elif`/`else` block executes, so order conditions logically.

## 🎯 Did It Work?

- Did your `ph_levels.py` print the correct pH classification? If yes, you’re a chemistry coding star! 🌟
- If not, check your operators (`>`, `<`), indentation (2 spaces), and ensure `float()` is used. Confirm Python is set up (see Gear Up for Coding Magic).

## ❓ Need Help?

If your potions don’t react, don’t fret! **Leave a comment** on this GitHub page or **join our Discord community** (link in the repo description) to get help from other noowbies and code wizards.

## 🛠️ What’s Next?

You’ve mastered pH testing—way to fizz at the carnival! 🎆 Head back to the Chem Craze Carnival guide to review, or check the Python for Noowbies main guide for the next stop in Chapter 3.

**Super Challenge**: Can you add a comment with a lab vibe, like `# Mixing pH magic!`? Try it and keep the carnival sparkling! 😺

**Back to Topic Guide**: Chem Craze Carnival | **Main Guide**: Python for Noowbies