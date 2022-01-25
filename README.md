# food-shopping
Use-case: When shopping for groceries, use this app to track groceries you are buying, their prices, 
quantities being purchased and nutritional data.

Input: 1) Scan the bar code on the product or manually enter the product info

2) User Parameters:
  a) Body Weight
  b) % Fat
  c) % Bone Density
  d) % Muscle
  e) Desired body goal: (gain muscle, maintainance, loss weight)
  f) Daily Calorie breakdown needed for protein, fat, carbs and day total for given body goal,   


3) Food Nutrition Parameters:
  For each food, show serving size, protein, fat, carb and total calories.
  
4) Number of days to get food for
5) Spending Limit

Storage: Use SQLite

Output:
1) Itemized List of foods & quantities to buy for given number of days and body goal. 
  a) for each item show count, item name, units, single item cost, total line item costs, per serving cals, total cals
2) Grand total cost, Daily calories