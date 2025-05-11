# 🎡 Carnival Booth Game: Win a Surprise Prize!

It’s time to shine at the **Fortune Fun Fair**! 🎠 In this folder, you’ll create a `booth.py` program that uses the **random** module to run a carnival prize booth. You’ll ask users for their favorite carnival activity, then use `random.randint()` to award a random prize, making every spin a surprise. Step up to the booth and let’s win some carnival goodies! 🎉

## 📋 Instructions

Follow these steps to complete the main exercise and try the extra challenges. Use VS Code, an online IDE (like Replit), or any Python environment (check Gear Up for Coding Magic for setup help).

### Exercise 1: Run a Carnival Prize Booth

Your mission is to create a `booth.py` program that:

- Asks the user for their favorite carnival activity (e.g., “Ring Toss”) using `input()`.
- Uses `random.randint(1, 9)` to pick a random number.
- Selects one of nine carnival prizes based on the number.
- Prints the activity and prize in the format:

```
Activity:      [Activity]
Prize Booth:   [Prize]
```

The nine possible prizes are:

- Plush Panda
- Glow Stick
- Cotton Candy
- Bouncy Ball
- Star Sticker
- Toy Rocket
- Glitter Hat
- Puzzle Cube
- Sparkler Pack

Here’s how to do it:

1. **Create a File**:
    
    - Open VS Code or your IDE.
    - Create a new file called `booth.py`.
2. **Write the Code**:
    
    - Start with a comment, like:
        
        ```python
        # Running the carnival prize booth!
        ```
        
    - Use `input()`, `random.randint()`, and `if` statements:
        
        ```python
        import random
        activity = input("What's your favorite carnival activity? ")
        pick = random.randint(1, 9)
        if pick == 1:
          print("Activity:      ", activity)
          print("Prize Booth:   Plush Panda")
        if pick == 2:
          print("Activity:      ", activity)
          print("Prize Booth:   Glow Stick")
        if pick == 3:
          print("Activity:      ", activity)
          print("Prize Booth:   Cotton Candy")
        if pick == 4:
          print("Activity:      ", activity)
          print("Prize Booth:   Bouncy Ball")
        if pick == 5:
          print("Activity:      ", activity)
          print("Prize Booth:   Star Sticker")
        if pick == 6:
          print("Activity:      ", activity)
          print("Prize Booth:   Toy Rocket")
        if pick == 7:
          print("Activity:      ", activity)
          print("Prize Booth:   Glitter Hat")
        if pick == 8:
          print("Activity:      ", activity)
          print("Prize Booth:   Puzzle Cube")
        if pick == 9:
          print("Activity:      ", activity)
          print("Prize Booth:   Sparkler Pack")
        ```
        
    - Use **2-space indentation** for code inside `if` statements, as in previous topics.
        
3. **Run the Program**:
    
    - In VS Code, click the “Run” triangle or right-click and select “Run Python File in Terminal”.
        
    - In an online IDE, hit the “Run” button.
        
    - In a terminal, navigate to the folder and run:
        
        ```bash
        python3 booth.py
        ```
        
4. **Test Different Activities**:
    
    - Run the program and enter activities like “Ring Toss”, “Ferris Wheel”, “Balloon Pop”.
    - Each run picks a random prize from the nine options.
    - Check the output format:

```
Activity:      Ring Toss
Prize Booth:   Glow Stick
```

**Sample Output** (example with input “Ferris Wheel”):

```
What's your favorite carnival activity? Ferris Wheel
Activity:      Ferris Wheel
Prize Booth:   Star Sticker
```

**Share the Fun**: Save a screenshot of your prize booth outputs and share it with friends or post it on X with #PythonForNoowbies to show off your carnival skills!

### Exercise 2: Extra Challenges

Want to keep the fair buzzing? Try these tasks! Create a new file (e.g., `my_booth.py`) or edit `booth.py`.

1. **Fancy Prize Format**:
    
    - Add a carnival-themed border:
        
        ```python
        print("~~~ Carnival Prize Booth ~~~")
        print("Activity:      ", activity)
        print("Prize Booth:   Plush Panda")
        print("~~~ Carnival Prize Booth ~~~")
        ```
        
2. **Custom Prizes**:
    
    - Replace prizes with your own (keep 9):
        
        ```python
        if pick == 1:
          print("Activity:      ", activity)
          print("Prize Booth:   Super Slinky")
        # Add 8 more custom prizes
        ```
        
3. **Prize Number**:
    
    - Show the random number:
        
        ```python
        print("Activity:      ", activity)
        print("Prize Booth:   Plush Panda (Pick #", pick, ")")
        ```
        
4. **Using Elif**:
    
    - Rewrite with `elif` (from Chem Craze Carnival) for efficiency:
        
        ```python
        import random
        activity = input("What's your favorite carnival activity? ")
        pick = random.randint(1, 9)
        if pick == 1:
          print("Activity:      ", activity)
          print("Prize Booth:   Plush Panda")
        elif pick == 2:
          print("Activity:      ", activity)
          print("Prize Booth:   Glow Stick")
        # Add remaining elif and else
        ```
        

## 💡 Tips for Prize Booth Success

- **Import Random**: Ensure `import random` is at the top, or you’ll get a NameError (see Bug Buster Bonanza).
- **Indent Properly**: Use **2 spaces** for `if` code to avoid IndentationError.
- **Check Range**: `randint(1, 9)` gives 1 to 9. Match each number to a prize.
- **Test Randomness**: Run multiple times to see different prizes. Each has a ~11% chance (1/9).
- **Format Exactly**: Use “Activity: ” and “Prize Booth: ” with spaces as shown.
- **Simple If**: Multiple `if` statements work for beginners. `elif` is optional but cleaner.

## 🎯 Did It Work?

- Did your `booth.py` print a random prize in the correct format? If yes, you’re a carnival champ! 🌟
- If not, check your `import`, indentation (2 spaces), and ensure all 9 prizes are coded. Confirm Python is set up (see Gear Up for Coding Magic).

## ❓ Need Help?

If your prize booth isn’t sparkling, don’t fret! **Leave a comment** on this GitHub page or **join our Discord community** (link in the repo description) to get help from other noowbies and code wizards.

## 🛠️ What’s Next?

You’ve mastered the prize booth—way to rock the fair! 🎆 Head back to the Fortune Fun Fair guide to review, or check the Python for Noowbies main guide for the next stop in Chapter 3.

**Super Challenge**: Can you add a comment with a carnival vibe, like `# Spinning for prizes!`? Try it and keep the fair glowing! 😺

**Back to Topic Guide**: Fortune Fun Fair | **Main Guide**: Python for Noowbies