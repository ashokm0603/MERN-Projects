# Software Requirements Specification (SRS)
## Project 29: Meal Macro Planner (Health & Wellness)

### 1. Project Description
The Meal Macro Planner is a comprehensive nutrition management application designed to help users achieve their fitness goals. It automates the process of building daily meal plans that fit specific macronutrient targets (Proteins, Carbs, Fats), tracks daily intake, and automatically generates organized grocery lists based on the planned meals.

### 2. Core Scope
The platform features a large recipe database, algorithm-driven meal matching to hit macro targets, a barcode scanner (for mobile web), and dynamic list generation.

### 3. Functionalities (Minimum 25)

#### Profile & Goal Setting
1. **User Onboarding:** Collect age, weight, height, gender, and activity level.
2. **Goal Selection:** Choose primary goal (Lose Weight, Maintain, Build Muscle).
3. **Macro Calculator:** Automatically calculate daily calorie and macronutrient targets based on user data and goals.
4. **Custom Macro Overrides:** Allow advanced users to manually set their desired Grams or Percentages for Macros.
5. **Dietary Preferences:** Select filters like Vegan, Keto, Paleo, Gluten-Free, or specific food allergies.

#### Meal Planning & Recipes
6. **Auto-Generate Meal Plan:** Click a button to generate a full day or week of meals that perfectly hit the macro targets.
7. **Recipe Database:** A searchable library of meals with detailed nutritional information and cooking instructions.
8. **Swap Meal Feature:** If the user dislikes an auto-generated meal, they can click 'Swap' to find an alternative with identical macros.
9. **Custom Recipe Builder:** Users can input their own ingredients to create and save a custom recipe, with the app calculating total macros.
10. **Favorite Meals:** Bookmark preferred recipes for quick access later.

#### Tracking & Logging
11. **Daily Diary:** A dashboard showing Breakfast, Lunch, Dinner, and Snacks, with running totals of calories and macros consumed versus remaining.
12. **Barcode Scanner Integration:** Use the device camera to scan food barcodes and auto-fill nutritional data via an external API (like OpenFoodFacts).
13. **Quick Add:** Manually input calories and macros if the exact food isn't in the database.
14. **Water Tracker:** Log daily water consumption in glasses or ounces/ml.
15. **Weight Logger:** Track body weight changes over time and view progress on a line chart.

#### Grocery & Shopping
16. **Auto-Grocery List:** Generate a shopping list based on the meals planned for the upcoming week.
17. **Categorized Shopping List:** Automatically sort grocery items by aisle (e.g., Produce, Meat, Dairy) for efficient shopping.
18. **Pantry Check:** Allow users to cross off items they already have before finalizing the list.
19. **Export List:** Share the list via WhatsApp, Email, or export as a PDF.

#### Analytics & Progress
20. **Weekly Macro Averages:** View charts showing adherence to macro goals over a 7-day period.
21. **Calorie Cycle Tracking:** Support for calorie cycling (e.g., eating more on workout days) with visual indicators.
22. **Streak Tracking:** Gamify adherence by tracking consecutive days the user hits their targets within a 5% margin.

#### Admin & System Features
23. **Food Database Management:** Admins can approve, edit, or remove user-submitted recipes to maintain data quality.
24. **Premium Tier Features:** Implement payment gateways for advanced features like personalized coach feedback or ad removal.
25. **Responsive Design:** Ensure the diary and grocery list features are heavily optimized for mobile usage while shopping or cooking.
