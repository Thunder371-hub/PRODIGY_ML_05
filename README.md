# 🍽️ PRODIGY_ML_05 – Food Recognition and Calorie Estimation

This project was completed as part of my **Machine Learning Internship** at **Prodigy InfoTech**.

---

## 📌 Task Objective

Build a deep learning model that:
- 🧠 Recognizes food items from images
- 🔥 Estimates calorie content based on predicted food type

This system can help users **track their dietary intake** and make **healthier food choices**.

---

## 📂 Dataset

Used the **Food-101 Dataset** from Kaggle:  
🔗 [Food-101 Kaggle Dataset](https://www.kaggle.com/dansbecker/food-101)

- 101 food classes
- 1,000 images per class (750 train + 250 test)
- Images stored as: `images/food_name/*.jpg`

---

## ⚙️ Technologies Used

- Python
- TensorFlow / Keras
- MobileNetV2 (Transfer Learning)
- OpenCV
- NumPy, Matplotlib
- Jupyter Notebook

---

## 🔍 Workflow

1. **Image Preprocessing**
   - Resized to 224×224
   - Normalized pixel values
   - Augmented for training

2. **Modeling**
   - Used **MobileNetV2** with custom dense layers
   - Trained with categorical cross-entropy

3. **Prediction**
   - Predicts food label from image
   - Maps label to calories using a custom dictionary

4. **Demo**
   - Upload an image → see food name + estimated calories

---

## 🧮 Calorie Mapping (Sample)

| Food Item      | Calories (approx.) |
|----------------|--------------------|
| Pizza          | 266 kcal per slice |
| Apple Pie      | 296 kcal per slice |
| Caesar Salad   | 190 kcal per bowl  |
| Hamburger      | 354 kcal each      |

> 🔧 *You can expand this table for all 101 items using a dictionary or external API.*

---

## 🔗 LinkedIn Post

👉 *[https://www.linkedin.com/in/saran-kumar-s-b45b75317/overlay/about-this-profile/?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base%3BjzL3eUenRU%2BfbEwFfV2AGg%3D%3D]*

---

## 👨‍💻 Author

**Saran Kumar S**  
Machine Learning Intern – Prodigy InfoTech  
[GitHub Profile](https://github.com/Thunder371-hub) <!-- Replace with your profile -->
