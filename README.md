# PRODIGY_ML_03
---

# 🍽️ Food Calorie Estimation

This project is a **Macihine Learning-based model** that can recognize food items from images and estimate their **calorie content** using a trained CNN model and a nutrition dataset.

## 🗂️ Project Structure

```
📂 dataset/
 ┣ 📂 train/              # Training images (folder per food item)
 ┣ 📂 validation/               # Testing images (folder per food item)
 ┣ 📂 evaluation/               # Testing images (folder per food item)
📄 model.h5               # Trained CNN model
📄 calories.csv           # Nutrition data (FoodItem, Calories, Protein, etc.)
📄 requirements.txt       # Python dependencies
📄 README.md              # Project documentation
```

## ⚙️ Installation & Setup

1. **Clone the Repository**

```bash
git clone https://github.com/Soundar586/food-calorie-estimator.git
cd food-calorie-estimator
```

2. **Install Dependencies**

```bash
pip install -r requirements.txt
```

## 📊 Dataset

* **Images**: Organized by class (one folder per food type).
* **Nutrition Data**: `calories.csv` containing calorie & nutrient values for each food item.

## 🧠 Model

* Model Type: Convolutional Neural Network (CNN)
* Framework: TensorFlow / Keras
* File: `model.h5`

## 📸 Example Prediction

<img width="1097" height="753" alt="image" src="https://github.com/user-attachments/assets/ff90d536-2fa2-4770-9dee-d8a2ac96dc44" />


**Input Image:**
🍔 *Burger*
**Output:**

* Food: Burger
* Calories: 354 kcal
* Protein: 17g
* Carbs: 29g

## 📌 Future Improvements

* Add support for multiple foods in one image.
* Integrate with a mobile app.
* Add more nutritional metrics (fiber, sugar, etc.).

## 🤝 Contributing

Feel free to submit issues or pull requests to improve the project!

---

## 🚀 Features

* Upload a food image and get **predicted food name**.
* Displays **calories** and other nutrient details from the CSV database.
* Works with **your custom trained model** and dataset.

---

## 🛠️ Tech Stack

* **Backend:** Python, Flask, TensorFlow/Keras
* **Data:** CSV for nutrition info
* **Model:** Trained CNN model saved as `model.h5`

---

---

## 📊 Dataset

* **Training Images:** Stored in `dataset/train/` folder, categorized into food classes.
* **Nutrition Data:** `calories.csv` contains food items and their nutritional values.

---

## 📜 License

This project is licensed under the **MIT License** 

---

---

## 👨‍💻 Author

**Soundira Ragavendiran** – [Your GitHub Profile](https://github.com/Soundar586)
