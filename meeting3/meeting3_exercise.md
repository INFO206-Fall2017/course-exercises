# Meeting 3 Exercise
## Info 206
## 31 August 2017

Write a script to solve each of the following problems. Each problem should have its solution as a separate .py file, named as outlined in each problem. Please upload the .py scripts to your GitHub repository in your meeting_3 folder.

Assignment due date: Midnight 31 August 2017.

## 1. Tip Calculator

Below, you can see the script to compute the tip for a meal. Fix it so that it works correctly. 

Save your result as the file tip_calculator_[LastName].py.


``` python
price = input("Enter the price of a meal:")

tip = price * 0.16
total = price + tip

print("A 16% tip would be ", tip)
print("The total including tip would be ", total)
```


## 2. Gas Pump Conversions

Write a script that prompts the user for a number of gallons of gasoline. Reprint that value, along with its conversion to other measurements:

* Equivalent number of liters

* Number of barrels of oil required to produce it

* Price in U.S. dollars

Figures to use:

  * 1 gallon is equivalent to 3.7854 liters.
  
  * 1 barrel of oil produces 19.5 gallons of gas.

  * The average price of gas is approximately $3.17 (source: http://www.sanfrangasprices.com/ 30 August 2017).

Save your script as gas_conversion_LastName.py


## 3. Number Averager (Extra Credit)

Write a script that prompts the user for two numbers, a and b. Then, prompt the user to enter a type of average (out of the three options below). Output the correct average, based on what the user selected:

1. The arithmetic mean $(a + b)/2$
2. The geometric mean $\sqrt{ab}$
3. The root-mean-square $\sqrt{\frac{a^2 + b^2}{n}}$

Save your script as averages_LastName.py
