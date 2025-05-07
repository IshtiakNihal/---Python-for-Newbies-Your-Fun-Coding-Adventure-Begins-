# 🏅 Grade Checker Challenge: Ace the Festival Test!

It’s time to steal the show at the **Grade Guru Gala**! 🎉 In this folder, you’ll create a `grades.py` program that uses `if`/`else` statements to check if a test score passes the festival’s curved grading scale. With a teacher’s curve boosting everyone’s chances, you’ll decide who gets to celebrate and who needs to hit the books. Let’s shine like festival stars! 🌟

## 📋 Instructions

Follow these steps to complete the main exercise and try the extra challenges. Use VS Code, an online IDE (like Replit), or any Python environment (check Gear Up for Coding Magic for setup help).

### Exercise 1: Check the Grade

Your mission is to create a `grades.py` program that:

- Creates a variable `grade` with a value between 0 and 100.
- Uses `if`/`else` to check if the grade is 55 or higher.
- Prints “You passed.” if the grade is 55 or more, or “You failed.” otherwise.
- Tests the program with different grade values to ensure it works.

Here’s how to do it:

1. **Create a File**:
    
    - Open VS Code or your IDE.
    - Create a new file called `grades.py` (use the sample file in this folder).
2. **Write the Code**:
    
    - Start with a comment, like:
        
        ```python
        # Checking grades at the festival!
        ```
        
    - Create a `grade` variable and add an `if`/`else` statement:
        
        ```python
        grade = 75  # Try values between 0-100
        if grade >= 55:
          print("You passed.")
        else:
          print("You failed.")
        ```
        
    - Use **2-space indentation** for code inside `if` and `else`, as specified.
        
3. **Run the Program**:
    
    - In VS Code, click the “Run” triangle or right-click and select “Run Python File in Terminal”.
        
    - In an online IDE, hit the “Run” button.
        
    - In a terminal, navigate to the folder and run:
        
        ```bash
        python3 grades.py
        ```
        
4. **Test Different Grades**:
    
    - Run the program with the initial `grade` (e.g., 75).
    - Change `grade` to other values (e.g., 50, 60, 30, 80) and rerun each time.
    - Check the output:
        - Grades ≥ 55 should print “You passed.”
        - Grades < 55 should print “You failed.”

**Expected Output** (example with `grade = 50`):

```
You failed.
```

**Sample File**: Check out `grades.py` in this folder for the code or use it to test.

**Share the Glory**: Save a screenshot of your outputs for different grades and share it with friends or post it on X with #PythonForNoowbies to show off your grade-checking skills!

### Exercise 2: Extra Challenges

Want to keep the gala glowing? Try these tasks! Create a new file (e.g., `my_grades.py`) or edit `grades.py`.

1. **Fancy Grade Report**:
    
    - Add a festival-themed border:
        
        ```python
        print("~~~ Festival Grade Check ~~~")
        print("You passed.")
        print("~~~ Festival Grade Check ~~~")
        ```
        
2. **Input-Based Grades**:
    
    - Let the user enter a grade:
        
        ```python
        grade = int(input("Enter your grade (0-100): "))
        if grade >= 55:
          print("You passed.")
        else:
          print("You failed.")
        ```
        
3. **Bonus Points**:
    
    - Add 10 bonus points before checking:
        
        ```python
        grade = 45
        grade = grade + 10
        if grade >= 55:
          print("You passed with bonus!")
        else:
          print("You failed, even with bonus.")
        ```
        
4. **Custom Threshold**:
    
    - Change the passing score to 70:
        
        ```python
        grade = 68
        if grade >= 70:
          print("You earned a festival medal!")
        else:
          print("Try harder next time!")
        ```
        

## 💡 Tips for Grade-Checking Success

- **Indent Properly**: Use **2 spaces** for code under `if`/`else`, as requested, to avoid SyntaxError or IndentationError (see Bug Buster Bonanza).
- **Test Both Outcomes**: Try grades above and below 55 (e.g., 60, 50) to ensure both “You passed.” and “You failed.” work.
- **Use >=**: The `>=` operator includes 55 in the passing range. Review Math Magic Mix for comparison operators.
- **Pick Valid Grades**: Stick to 0–100 for `grade` to match the exercise.

## 🎯 Did It Work?

- Did your `grades.py` print the correct message for different grades? If yes, you’re a festival superstar! 🌟
- If not, check your indentation (2 spaces), ensure `>=` is used, and confirm Python is set up (see Gear Up for Coding Magic).

## ❓ Need Help?

If your grades don’t shine, don’t fret! **Leave a comment** on this GitHub page or **join our Discord community** (link in the repo description) to get help from other noowbies and code wizards.

## 🛠️ What’s Next?

You’ve aced the grade-checking challenge—way to rock the festival! 🎆 Head back to the Grade Guru Gala guide to review, or check the Python for Noowbies main guide for the next stop in Chapter 3.

**Super Challenge**: Can you add a comment with a festival cheer, like `# Passing the test with flair!`? Try it and keep the gala buzzing! 😺

**Back to Topic Guide**: Grade Guru Gala | **Main Guide**: Python for Noowbies