# 🎉 Money Mix Mania: Turn Pesos into Dollars!

Welcome to **Money Mix Mania**, where we’re wrapping up Chapter 2 with a currency-converting bash! 💰 You’ve mastered variables, data types, operators, exponents, and user input—now let’s mix them all to convert South American cash into USD. From travel budgets to exchange rates, these examples will recap your skills and get you ready to cash in. Let’s hit the money trail! ✈️

## 📖 Chapter 2 Recap

Here’s what you’ve learned in Chapter 2:

- **Data Type Disco**: Variables store data like integers (`int`), decimals (`float`), text (`str`), and true/false (`bool`).
- **Math Magic Mix**: Operators (`+`, `-`, `*`, `/`, `%`) let you calculate, with `%` finding remainders.
- **Power-Up Punch**: The `**` operator raises numbers to powers, like squaring.
- **Chatty Code Craze**: `input()` gets user text, and `int()`/`float()` converts it to numbers.

Now, let’s use them all in a travel adventure!

### Example 1: Travel Budget with Variables and Operators

```python
# Planning a trip budget
souvenirs = 25.99  # float: Cost in USD
flights = 300  # int: Cost in USD
total_cost = souvenirs + flights
tax = total_cost * 0.08  # 8% tax
final_bill = total_cost + tax

print("Final Trip Bill:", final_bill, "USD")  # Output: Final Trip Bill: 347.9824 USD
```

This uses `float` and `int` data types, plus `+` and `*` operators, to calculate a trip’s cost with tax.

### Example 2: Exponents for Souvenir Boxes

```python
# Calculating souvenir box volume
box_side = 0.2  # float: Side length in meters
volume = box_side ** 3  # Cube it!

print("Box Volume:", volume, "cubic meters")  # Output: Box Volume: 0.008 cubic meters
```

Here, `**` (from Power-Up Punch) computes the volume using a `float`.

### Example 3: Input for Travel Plans

```python
# Asking for travel days
days = int(input("How many days are you traveling? "))
meals = days * 3  # 3 meals per day
meal_cost = 10.50  # float: Cost per meal
food_budget = meals * meal_cost

print("Food Budget:", food_budget, "USD")  # E.g., Input 5 → Food Budget: 157.5 USD
```

This uses `input()` and `int()` (from Chatty Code Craze) to get user data, then `*` to calculate costs.

**Knowledge Nugget**: The `%` operator is great for travel! For example, `days % 7` tells you how many days are left after full weeks, helping you plan trips or split expenses.

## 🎯 Currency Conversion Example

Let’s convert some Peruvian soles (PEN) to USD using a sample exchange rate (e.g., 1 PEN ≈ 0.27 USD).

```python
# Converting soles to USD
soles = float(input("How many Peruvian soles do you have? "))  # float for decimals
rate = 0.27  # 1 PEN = 0.27 USD
usd = soles * rate

print("That’s", usd, "USD!")  # E.g., Input 100 → That’s 27.0 USD!
```

**Why `float()`?** Currency amounts often have decimals (e.g., 105.50 PEN), so `float()` is safer than `int()` for user input here.

**Fun Fact**: Exchange rates change daily, driven by global markets, trade, and economics. Sites like XE.com or Wise.com provide real-time rates, making your converter super practical![](https://www.xe.com/currencyconverter/)

## 💡 Tips for Money Mixing

- **Use** `float()` **for Money**: Currencies often have decimals, so `float(input())` is better than `int()`.
- **Clear Prompts**: Write “How many pesos?” to guide users, like in Chatty Code Craze.
- **Check Rates**: Google exchange rates before coding (e.g., 1 COP ≈ 0.00025 USD).
- **Round Results**: Use `round(total, 2)` to keep USD values clean (e.g., 413.0).

## 🎯 What’s Next?

You’re ready to cash in on your Chapter 2 skills! Head to the Exercises folder to create a `currency.py` program that converts Colombian pesos, Peruvian soles, and Brazilian reais to USD. Let’s make it rain dollars! 💵

**Quick Challenge**: What’s the output if you input “20” days?

```python
days = int(input("Travel days: "))
cost = days * 15.25
print("Trip Cost:", cost, "USD")
```

Try it in the exercises!

## ❓ Need Help?

If your conversions don’t stack up, don’t lose your cash! **Leave a comment** on this GitHub page or **join our Discord community** (link in the repo description) to ask questions and get help from other noowbies.

**Back to Topic Guide**: Money Mix Mania | **Main Guide**: Python for Noowbies