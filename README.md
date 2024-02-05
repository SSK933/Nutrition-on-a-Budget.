# Nutrition-on-a-Budget.
Identify the cheapest groceries to meet your monthly nutrition requirements.

MAIN GOAL: Find out the cheapest possible way to provide nutrition to your body. Do not worry about taste, appetite, or preferences.
Data Source(s): Government websites for nutrition info (USDA, HHS, Nutrition.gov), Grocery marts for costing (Walmart, Kroger, ALDI's, Target, etc)

Step#1: Gather the nutritional requirements of an average adult person. Capture all the macros and micros, etc.
Step#2: Get/Make a list of all the typical groceries along with their nutritional contents.
Step#3: Feed the above list of groceries and scrape prices of the groceries from online retailers.
Step#4: Create an SQL database on the local system, and organize, transform, and store all the data.
Step#5: DATA ANALYSIS. Convert the data in such a form that you have the price per unit of nutrient for each of grocery item. Make containers for each nutrient that the person will require over 30 days. Identify the cheapest sources of every micro and micronutrient, Then sequentially pick each container and fill about 50% of this container with the cheapest source available. Simultaneously, fill all the other nutrients that this item provides. Then move on to another nutrient, fill it 50% with the cheapest available source and simultaneously fill the other nutrients that this item provides. Repeat this for all the micro and macronutrients. Once we are done with the first round of filling (with 50% fill level) all the nutrients, start the second round this time target filling level is the remaining 25% of each nutrient. In the third round this again becomes 12.5% and 6.25% (fill levels) in the subsequent round. This process stops when all the containers are filled to the required levels. Keep track of the overall cost while filling the nutrient containers.
Step#6: Visualisation (if needed) to explain our observations and results.

