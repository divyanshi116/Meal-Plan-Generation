# 🍴 Meal Plan Generator

The **Meal Plan Generator** is a user-friendly web application that creates personalized meal plans based on user input. It uses the Edamam API to fetch recipes that meet specific calorie requirements, dietary preferences, and health specifications. Whether you're looking to maintain a balanced diet, follow a specific health regime, or explore new recipes, this app has you covered! 🥗

---

## 🌟 Features

- **Personalized Meal Plans**: Generate meal plans based on age, weight, height, gender, and activity level.
- **Dietary Preferences**: Choose from Balanced, Low-Carb, or Low-Fat diets.
- **Health Specifications**: Get Vegan, Vegetarian, Alcohol-Free, or Peanut-Free meals.
- **Dynamic Meal Display**: Plan your meals for the entire week, tailored to your calorie needs.
- **Edamam API Integration**: Fetch recipes with calorie and health specifications.

---

## 🛠️ Technologies Used

- **HTML & CSS**: For structuring and styling the webpage.
- **JavaScript**: For dynamic functionality and API integration.
- **Edamam API**: To fetch recipes based on user input.

---

## 🚀 Getting Started

### Prerequisites

- A web browser (e.g., Chrome, Firefox, Edge).
- Internet connection to fetch meal data from the Edamam API.

### Installation & Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/divyanshi116/Meal-Plan-Generation.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Meal-Plan-Generation
   ```
3. Open the `index.html` file in your browser.

---

## 🖥️ Usage

1. Open the application in your browser.
2. Fill out the form:
   - Enter your age, weight, and height.
   - Select your gender and activity level.
   - Choose your preferred number of meals and dietary preferences.
   - Specify any health-related requirements.
3. Click on the **"Generate Meal Plan"** button.
4. View your personalized weekly meal plan with recipes and calorie information.

---

## 📂 Project Structure

- **index.html**: The main HTML file for the application interface.
- **style.css**: Contains styles for the application.
- **script.js**: Includes JavaScript logic for form handling, API integration, and meal plan generation.

---



## 🔧 How It Works

1. **User Inputs**: The user fills out the form with their details and preferences.
2. **Calorie Calculation**: The app calculates the user's calorie needs using the BMR formula adjusted for activity levels.
3. **API Request**: The app fetches recipes from the Edamam API that align with the user's preferences and calorie requirements.
4. **Meal Plan Generation**: The app organizes the meals into a weekly plan and displays them in a table.

---

## 🎯 Example

### Input:
- **Age**: 25
- **Weight**: 70 kg
- **Height**: 175 cm
- **Gender**: Male
- **Activity Level**: Moderately active
- **Meals per Day**: 3
- **Diet Preference**: Balanced
- **Health Specification**: Vegetarian

### Output:
A weekly meal plan with recipes, images, and links to detailed preparation instructions.

---

## 📋 Dependencies

- **Edamam API**: Used to fetch recipes.
- **JavaScript Fetch API**: For making HTTP requests.

---

## 🌍 API Integration

This project uses the [Edamam Recipe Search API](https://developer.edamam.com/) to fetch meal data. You'll need an APP ID and APP KEY to use the API.

Replace the placeholders in `script.js` with your API credentials:
```javascript
const APP_ID = "your-app-id";
const APP_KEY = "your-app-key";
```

---

## 🤝 Contributing

Contributions are welcome! 🎉 If you have ideas or improvements, feel free to submit a pull request.

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 📧 Contact

For questions or feedback, reach out to [divyanshi116](https://github.com/divyanshi116). 💬
