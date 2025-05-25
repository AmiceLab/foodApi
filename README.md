# 💪🏻👩🏻‍💻👩🏻‍⚕🍎 foodNutrientAPI

A simple and intelligent nutrition lookup API that returns nutritional data (Carbs, Protein, Iron, Vitamin C, etc.) per 100g of any given food item—using smart name matching if no exact match is found.

---

## 🧪 Project by AmiceLab

---

## ✨ Features

- Input any food name (e.g. `banana`, `broccoli`, `chicken breast`)
- Returns key nutrition facts per 100g:
  - Calories
  - Carbohydrates
  - Protein
  - Fat
  - Iron
  - Vitamin C
  - And more
- Handles typos or similar names (e.g. `bannana` → `banana`)
- Simple API format, ideal for integration into nutrition apps or personal tools

---

## 📦 Tech Stack

- Language: `Python`
- Framework: `Flask` (or `FastAPI`, if used)
- Data Source: [USDA FoodData Central](https://fdc.nal.usda.gov/) 
- Libraries: `requests`, `pandas`, `fuzzywuzzy` / `rapidfuzz`, etc.


Create and activate your virtual environment:

	python -m venv venv
	source venv/bin/activate  # Windows: venv\Scripts\activate
	Install requirements:
	pip install -r requirements.txt

---

## 🚀 Getting Started

### Installation

1. **Clone the repo**
   
		git clone https://github.com/AmiceLab/FoodAPI.git
		cd FoodAPI

2. **Create a Virtual Environment**

		python -m venv venv
		source venv/bin/activate  # For Mac/Linux
                      
3. **Install Requirements**

		pip install -r requirements.txt

4. **Done! Now you're ready to start developing.**

---

## 🙋‍♀️ About the Creator

AmiceLab is a HealthTech-focused creator with a passion for nutrition and wellness.
She is a Software Engineer and A Certified Functional Nutritionist.
This API is part of ongoing tools designed to make food knowledge more accessible and actionable.


                      
                      
