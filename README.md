# BMI and BMR Calculator with Diet and Exercise Planner

This Python program calculates the **Body Mass Index (BMI)** and **Basal Metabolic Rate (BMR)** for users based on their input and offers personalized diet and exercise recommendations. It provides detailed feedback on weight categories and caloric needs based on daily physical activity levels.

---

## 🚀 Features

- Input validation for **gender** and **age**
- **BMI calculation** with category analysis
- **BMR calculation** using gender-specific formulas
- Suggests:
  - Whether to **gain** or **lose** weight to achieve a normal BMI
  - **Calories to consume** based on activity level
  - A **custom diet plan** based on caloric requirement
- Visual **BMI category chart** using PrettyTable

---


## 📊 Activity Level Multipliers

| Activity Level                                    | Multiplier |
|--------------------------------------------------|------------|
| Little/No Exercise                               | 1.2        |
| Light Exercise (1–3 days/week)                   | 1.375      |
| Moderate Exercise (3–5 days/week)                | 1.55       |
| Hard Exercise (6–7 days/week)                    | 1.725      |
| Very Hard Exercise/Physical Job                  | 1.9        |

---

## 🥗 Diet Plans

Personalized based on the **calorie requirement**:
- Ranges from under **1000 calories** to over **3000 calories**
- Covers:
  - Low-calorie, high-protein meals
  - Balanced macros
  - Muscle-gain diets
  - High-energy diets with low cholesterol

---

## 📦 Requirements

- Python 3.x
- `prettytable` package

### To install PrettyTable:
```bash
pip install prettytable
