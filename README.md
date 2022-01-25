# food-shopping mobile app

Use-case: When shopping for groceries, use this app to planout ahead of time what you are buying, their prices, 
quantities being purchased and nutritional data. 

The app also has internal database of which foods are considered Thermo approved (refer to ThermoDiet.com) and which ones are Gundry approved (refer to https://gundrymd.com/dr-gundry-diet-food-list/). The Thermo foods are ones which help keep a warm metabolism and hormones in a healthy range. The Gundry approved ones which have been shown to be less likely to cause a problem if you have experienced digestive issues for some time or if you suffer from an autoimmune condition.

Input: 1) For each item, scan the bar code of the product or manually enter the product info

2) User Parameters to set up:
  a) Body Weight
  b) % Fat
  c) % Bone Density
  d) % Muscle
  e) Desired body goal: (gain muscle, maintainance, loss weight)
  f) Daily Calorie breakdown needed for protein, fat, carbs and day total for given body goal,   


3) Food Nutrition Parameters:
  For each Thermo food item, show serving size, protein, fat, carb and total calories.
  
4) Number of days to get food for
5) Spending Limit

Storage: Use SQLite

Output:
1) Itemized List of foods & quantities to buy for given number of days and body goal. 
  a) for each item show count, item name, units, single item cost, total line item costs, per serving cals, total cals.
  b) for each food item it also shows if the food is Thermo approved or Gundry approved.
  
2) Grand total cost at checkout, Daily calories


Software Product will be a mobile app that targets Android and IOS. 
