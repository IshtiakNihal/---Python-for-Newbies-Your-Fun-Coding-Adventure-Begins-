# 🌍 Money Mix Challenge: Convert Your Travel Cash!

It’s time to cash in with **Money Mix Mania**! 💸 In this folder, you’ll create a `currency.py` program that asks the user for their leftover Colombian pesos (COP), Peruvian soles (PEN), and Brazilian reais (BRL) from a South American adventure, then converts it all to USD using current exchange rates. You’ll use variables, operators, `input()`, and `float()` to make your code a global hit. Cha-ching! Let’s get converting! 🎉

## 📋 Instructions

Follow these steps to complete the main exercise and try the extra challenges. Use VS Code, an online IDE (like Replit), or any Python environment (check Gear Up for Coding Magic for setup help).

### Exercise 1: Convert South American Currencies

Your mission is to create a `currency.py` program that:

- Asks the user for amounts in COP, PEN, and BRL.
- Converts each to USD using exchange rates.
- Prints the total USD, matching the format: `What do you have left in pesos?` etc., with the final total (e.g., `413.0`).

**Exchange Rates** (approximated for April 19, 2025, based on sample output):

- 1 COP ≈ 0.00025 USD (1 USD ≈ 4000 COP).
- 1 PEN ≈ 0.27 USD (1 USD ≈ 3.704 PEN).
- 1 BRL ≈ 1.37 USD (1 USD ≈ 0.73 BRL).

**Note**: These rates are tuned to match the sample (5600 COP + 105 PEN + 280 BRL = 413.0 USD). Real rates may differ—check sites like XE.com or Wise.com for accuracy

Here’s how to do it:

1. **Create a File**:
    
    - Open VS Code or your IDE.
    - Create a new file called `currency.py` (use the sample file in this folder).
2. **Write the Code**:
    
    - Start with a comment to set the vibe, like:
        
        ```python
        # Converting South American cash to USD!
        ```
        
    - Get three inputs, convert to USD, and print the total. For example:
        
        ```python
        # Converting South American cash to USD!
        pesos = float(input("What do you have left in pesos? "))
        soles = float(input("What do you have left in soles? "))
        reais = float(input("What do you have left in reais? "))
        usd_total = (pesos * 0.00025) + (soles * 0.27) + (reais * 1.37)
        print(usd_total)
        ```
        
3. **Run the Program**:
    
    - In VS Code, click the “Run” triangle or right-click and select “Run Python File in Terminal”.
        
    - In an online IDE, hit the “Run” button.
        
    - In a terminal, navigate to the folder and run:
        
        ```bash
        python3 currency.py
        ```
        
4. **Check the Output**:
    
    - The program should match the sample:
        
        ```
        What do you have left in pesos? 5600
        What do you have left in soles? 105
        What do you have left in reais? 280
        413.0
        ```
        
    - If the total is off, check your rates or ensure `float()` is used.
        

**Sample File**: Check out `currency.py` in this folder for an example or use it to test.

**Share the Wealth**: Save a screenshot of your USD total and share it with friends or post it on X with #PythonForNoowbies to show off your global skills!

### Exercise 2: Extra Challenges

Ready to make more money moves? Try these tasks! Create a new file (e.g., `my_currency.py`) or edit `currency.py`.

1. **Fancy Cash Report**:
    
    - Add a border and message, like:
        
        ```
        ~~~ Cash Converter ~~~
        413.0
        Cha-ching! You’ve got 413.0 USD!
        ~~~ Cash Converter ~~~
        ```
        
    - Use `print()` for borders and “Cha-ching!”.
        
2. **Round the Total**:
    
    - Round the USD total to 2 decimal places:
        
        ```python
        usd_total = round((pesos * 0.00025) + (soles * 0.27) + (reais * 1.37), 2)
        print(usd_total)
        ```
        
3. **Breakdown Report**:
    
    - Show each currency’s USD value:
        
        ```python
        usd_pesos = pesos * 0.00025
        usd_soles = soles * 0.27
        usd_reais = reais * 1.37
        print("Pesos in USD:", usd_pesos)
        print("Soles in USD:", usd_soles)
        print("Reais in USD:", usd_reais)
        print("Total USD:", usd_pesos + usd_soles + usd_reais)
        ```
        
4. **Reverse Converter**:
    
    - Convert USD back to COP:
        
        ```python
        usd = float(input("Enter USD amount: "))
        cop = usd / 0.00025
        print("That’s", cop, "COP!")
        ```
        

## 💡 Tips for Money Mastery

- **Use** `float()`: Currency inputs may have decimals (e.g., 105.50 PEN), so `float()` is key.
- **Verify Rates**: The sample uses 1 COP = 0.00025 USD, 1 PEN = 0.27 USD, 1 BRL = 1.37 USD. Check XE.com for real rates
- **Clear Prompts**: Match “What do you have left in pesos?” exactly for user clarity.
- **Test Inputs**: Try the sample (5600, 105, 280) to ensure 413.0 USD.

## 🎯 Did It Work?

- Did your `currency.py` output the correct USD total? If yes, you’re a money-mixing superstar! 🌟
- If not, check your rates, ensure `float()` is used, and confirm Python is set up (see Gear Up for Coding Magic).

## ❓ Need Help?

If your conversions don’t cash out, don’t lose your coins! **Leave a comment** on this GitHub page or **join our Discord community** (link in the repo description) to get help from other noowbies and code wizards.

## 🛠️ What’s Next?

You’ve conquered Chapter 2 with a currency-converting bang! 💪 Head back to the Money Mix Mania guide to review, or check the Python for Noowbies main guide for what’s next in your coding quest.

**Super Challenge**: Add a comment with a travel tip, like `# Spend your USD on a cool souvenir!`? Try it and keep the mania going! 😺

**Back to Topic Guide**: Money Mix Mania | **Main Guide**: Python for Noowbies