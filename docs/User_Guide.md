# Introduction
The Calorie Calculator App helps users track their daily calorie intake, set personal calorie goals, and calculate nutritional needs based on their physical attributes and activity levels.

# Installation and Setup
- Install Python
Ensure you have Python 3.9 or higher installed. Download Python from python.org.

- Install Required Libraries
Open a terminal and run the following command to install the dependencies:

pip install tkinter pandas rapidfuzz requests

- Run the Application
Save the provided code in a file named calorie_app.py and run it using:

python calorie_app.py

# Usage Instructions
- Calculate BMR and Daily Calorie Needs
Click the "Calculate BMR & Daily Calories" button.
Input your age, gender, weight, height, and activity level.
The app calculates your BMR and daily calorie needs.

- Log Meals
Click the corresponding meal button (Breakfast, Lunch, Dinner, or Snack).
Enter the food name in the dialog box.
The app fetches nutritional data (calories, protein, carbs, fat) from the API and prompts for portion size.
Calories are added to your daily intake.

- Monitor Progress
The app displays:
* Eaten Calories: Total calories consumed.
* Calories Left: Remaining calories for the day.
* Burned Calories: A static value of 300 calories.
A circular progress ring shows the percentage of remaining calories.

- Alerts
If calorie intake exceeds your goal, the app shows a warning pop-up.

# Error Handling
Invalid Input: Ensure you input valid numeric values in the sliders and dialog boxes.
API Errors: If the app cannot fetch data, check your internet connection or API key.

# Screenshots
<img width="400" alt="Calorie Calculator" src="https://github.com/user-attachments/assets/d53e0729-8ec5-4169-a0a4-b55efceb697e">
<img width="438" alt="Input Details" src="https://github.com/user-attachments/assets/3042d22a-50d3-42b8-8540-2ee76da140a6">
<img width="272" alt="input" src="https://github.com/user-attachments/assets/47cedfa3-432b-4993-9aae-28856d522e3d">
<img width="664" alt="image" src="https://github.com/user-attachments/assets/032d277a-39e2-424b-895f-783ca224ef6c" />
<img width="676" alt="image" src="https://github.com/user-attachments/assets/64023ca0-27a7-4733-85ce-cba486c28509" />

