# 🥗 Vegetarian Recipes Dataset

This dataset contains 10 vegetarian recipes fetched using the [Spoonacular API](https://spoonacular.com/food-api), curated and shared by **Anjal Bhattarai**.  
It includes basic but insightful features that are great for **beginner data analysis**, **ML classification**, or **EDA projects**.

## 📦 What's Inside?

| Column          | Description                                 |
|------------------|---------------------------------------------|
| recipe no.       | Serial number (1–10)                        |
| title            | Name of the recipe                          |
| readyInMinutes   | Time required to prepare the dish ⏱️         |
| vegetarian       | Boolean (all are True in this dataset) 🥦    |
| veryPopular      | Boolean (whether the recipe is popular) ⭐   |
| healthScore      | Health rating score (0–100) 💚              |

## 📈 Why Use This Dataset?

- Build a **popularity classifier**
- Correlate **healthiness with preparation time**
- Use for **data cleaning, visualization, or modeling practice**

## 🔧 How It Was Made

Data was pulled using Python with the following tools:
- `requests` for API fetch
- `pandas` for DataFrame manipulation

View the code snippet in ***day17_practice[API_fetch].ipynb***

## ✅ License

Data is sourced from Spoonacular and is available under **educational use**.

---
