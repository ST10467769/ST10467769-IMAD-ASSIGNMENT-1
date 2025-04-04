# 🍽️ Meal Suggestion App

A simple Android app that gives meal suggestions based on the time of day entered by the user. Built with Kotlin and designed for quick interaction and ease of use.

---

## 📱 Features

- Suggests meals for different times of the day
- Case-insensitive input (e.g., `Morning`, `morning`, etc.)
- Displays a Toast message on interaction
- Clears old suggestions when a new one is selected
- Simple, intuitive interface using `TextView` and `Button`

---

## 🛠️ How It Works

1. User taps on a `TextView` labeled with a time of day (e.g., "Morning").
2. App displays a Toast message confirming the action.
3. Based on the input, a meal suggestion is shown on a button below.
4. If the input is not recognized, the app displays an "Invalid option entered" message.

---

## 🍴 Example Time of Day & Suggestions

| Time of Day      | Suggested Meals                                  |
|------------------|--------------------------------------------------|
| Morning          | Oatmeal, Smoothie, Pancakes                      |
| Mid-Morning      | Avocado Toast, Yogurt, Oats                      |
| Afternoon        | Tacos, Sandwich, Pizza                           |
| Mid-Afternoon    | Mini Quesadillas, Protein Smoothie, Energy Bars |
| Dinner           | Mac and Cheese, Grilled Steak, Stir-Fry         |
| After-Dinner     | Milkshake, Fruit Salad, Ice Cream               |

---

## 🧑‍💻 Code Snippet

```kotlin
if (timeOfDay == "morning") {
    suggestionButton.text = "Oatmeal, Smoothie, Pancakes"
} else if (timeOfDay == "mid-morning") {
    suggestionButton.text = "Avocado Toast, Yogurt, Oats"
}
// ... and so on
