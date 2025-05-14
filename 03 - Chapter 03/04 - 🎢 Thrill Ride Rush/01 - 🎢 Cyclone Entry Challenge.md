# 🎢 Cyclone Entry Challenge: Control the Roller Coaster!

It’s time to take charge at the **Thrill Ride Rush**! 🎠 In this folder, you’ll create a `the_cyclone.py` program that uses **logical operators** to manage entry to the legendary Cyclone roller coaster at Coney Island. You’ll ask users for their height and credits, then use `and` with `if`/`elif`/`else` to decide who rides. Strap in and let’s code some thrills! 🚂

## 📋 Instructions

Follow these steps to complete the main exercise and try the extra challenges. Use VS Code, an online IDE (like Replit), or any Python environment (check Gear Up for Coding Magic for setup help).

### Exercise 1: Manage Cyclone Entry

Your mission is to create a `the_cyclone.py` program that:

- Asks the user for their height (in cm) and credits, storing them in `height` and `credits` variables.
- Uses logical and relational operators to check:
    - If height ≥ 137 cm _and_ credits ≥ 10, print “Enjoy the ride!”
    - Else if credits ≥ 10 but height < 137 cm, print “You are not tall enough to ride.”
    - Else if height ≥ 137 cm but credits < 10, print “You don’t have enough credits.”
    - Else (neither requirement met), print “You need more height and credits.”
- Tests the program with different height and credits values to ensure it works.

Here’s how to do it:

1. **Create a File**:
    
    - Open VS Code or your IDE.
    - Create a new file called `the_cyclone.py` (use the sample file in this folder).
2. **Write the Code**:
    
    - Start with a comment, like:
        
        ```python
        # Managing Cyclone roller coaster entry!
        ```
        
    - Use `input()`, logical operators, and `if`/`elif`/`else`:
        
        ```python
        height = float(input("Enter your height (cm): "))
        credits = int(input("Enter your credits: "))
        if height >= 137 and credits >= 10:
          print("Enjoy the ride!")
        elif credits >= 10 and height < 137:
          print("You are not tall enough to ride.")
        elif height >= 137 and credits < 10:
          print("You don't have enough credits.")
        else:
          print("You need more height and credits.")
        ```
        
    - Use **2-space indentation** for code inside `if`/`elif`/`else`, as in previous topics.
        
3. **Run the Program**:
    
    - In VS Code, click the “Run” triangle or right-click and select “Run Python File in Terminal”.
        
    - In an online IDE, hit the “Run” button.
        
    - In a terminal, navigate to the folder and run:
        
        ```bash
        python3 the_cyclone.py
        ```
        
4. **Test Different Inputs**:
    
    - Run the program with height and credits pairs like:
        - 150 cm, 12 credits (both met)
        - 130 cm, 15 credits (enough credits, not tall enough)
        - 140 cm, 5 credits (tall enough, not enough credits)
        - 120 cm, 3 credits (neither met)
    - Check the output matches the rules.

**Expected Output** (example with height 130, credits 15):

```
Enter your height (cm): 130
Enter your credits: 15
You are not tall enough to ride.
```

**Sample File**: Check out `the_cyclone.py` in this folder for the code or use it to test.

**Share the Thrill**: Save a screenshot of your Cyclone outputs and share it with friends or post it on X with #PythonForNoowbies to show off your roller coaster skills!

### Exercise 2: Extra Challenges

Want to keep the ride roaring? Try these tasks! Create a new file (e.g., `my_cyclone.py`) or edit `the_cyclone.py`.

1. **Fancy Ride Report**:
    
    - Add a roller-coaster-themed border:
        
        ```python
        print("~~~ Cyclone Entry Check ~~~")
        print("Enjoy the ride!")
        print("~~~ Cyclone Entry Check ~~~")
        ```
        
2. **Detailed Feedback**:
    
    - Include height and credits in the output:
        
        ```python
        if height >= 137 and credits >= 10:
          print(f"Height {height} cm, {credits} credits: Enjoy the ride!")
        ```
        
3. **VIP Pass**:
    
    - Add an `or` condition for a VIP pass:
        
        ```python
        vip = input("Have a VIP pass? (yes/no): ") == "yes"
        if (height >= 137 and credits >= 10) or vip:
          print("VIP or qualified: Enjoy the ride!")
        # Add remaining conditions
        ```
        
4. **Stricter Rules**:
    
    - Add an age requirement (e.g., ≥ 12):
        
        ```python
        height = float(input("Enter your height (cm): "))
        credits = int(input("Enter your credits: "))
        age = int(input("Enter your age: "))
        if height >= 137 and credits >= 10 and age >= 12:
          print("Enjoy the ride!")
        # Add remaining conditions
        ```
        

## 💡 Tips for Cyclone Success

- **Use float for Height**: Height can be decimal (e.g., 137.5 cm), so use `float(input())` (from Money-Mix-Mania).
- **Use int for Credits**: Credits are whole numbers, so use `int(input())` (from Chatty-Code-Craze).
- **Check Logic**: `and` requires both conditions to be `True`. Test each `elif` to ensure correct relational operators (`>=`, `<`) from Chem-Craze-Carnival.
- **Indent Properly**: Use **2 spaces** for `if`/`elif`/`else` code to avoid IndentationError (see Bug-Buster-Bonanza).
- **Test All Cases**: Try inputs for all four outcomes (both met, credits only, height only, neither).
- **Order Conditions**: Check the most inclusive condition (`height >= 137 and credits >= 10`) first to avoid logic errors.

## 🎯 Did It Work?

- Did your `the_cyclone.py` print the correct message for different inputs? If yes, you’re a roller coaster superstar! 🌟
- If not, check your `and` operators, indentation (2 spaces), and input conversions (`float()`, `int()`). Confirm Python is set up (see Gear Up for Coding Magic).

## ❓ Need Help?

If your ride rules don’t click, don’t fret! **Leave a comment** on this GitHub page or **join our Discord community** (link in the repo description) to get help from other noowbies and code wizards.

## 🛠️ What’s Next?

You’ve mastered the Cyclone entry system—way to thrill at the carnival! 🎆 Head back to the Thrill Ride Rush guide to review, or check the Python for Noowbies main guide for the next stop in Chapter 3.

**Super Challenge**: Can you add a comment with a ride vibe, like `# Zooming with code!`? Try it and keep the rush alive! 😺

**Back to Topic Guide**: Thrill Ride Rush | **Main Guide**: Python for Noowbies