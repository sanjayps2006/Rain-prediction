# 🌧️ 𝐑𝐚𝐢𝐧 𝐏𝐫𝐞𝐝𝐢𝐜𝐭𝐢𝐨𝐧 𝐔𝐬𝐢𝐧𝐠 𝐑𝐚𝐧𝐝𝐨𝐦 𝐅𝐨𝐫𝐞𝐬𝐭

> 🤖 **A Simple Machine Learning Project to Predict Rainfall Based on Temperature and Humidity**

## ✨ 𝐀𝐛𝐨𝐮𝐭 𝐓𝐡𝐞 𝐏𝐫𝐨𝐣𝐞𝐜𝐭

This project uses the **Random Forest Classifier** from **Scikit-learn** to predict whether it will **Rain** or **No Rain** based on two weather parameters:

- 🌡️ Temperature
- 💧 Humidity

The model is trained using sample weather data and predicts the weather condition based on user input.

---

## 🎯 𝐎𝐛𝐣𝐞𝐜𝐭𝐢𝐯𝐞

✔ Train a Random Forest Classification model

✔ Predict whether it will rain

✔ Accept real-time user input

✔ Demonstrate supervised machine learning for classification

---

## 📂 𝐃𝐚𝐭𝐚𝐬𝐞𝐭

### Training Data

| Temperature (°C) | Humidity (%) | Rain |
|-----------------|--------------|------|
| 30 | 80 | Yes |
| 25 | 60 | No |
| 28 | 70 | Yes |
| 35 | 40 | No |
| 20 | 90 | Yes |
| 22 | 85 | Yes |

**Target Values**

- **1 → Rain**
- **0 → No Rain**

---

## 🛠️ 𝐓𝐞𝐜𝐡𝐧𝐨𝐥𝐨𝐠𝐢𝐞𝐬 𝐔𝐬𝐞𝐝

- 🐍 Python
- 🤖 Scikit-learn

---

## 📦 𝐑𝐞𝐪𝐮𝐢𝐫𝐞𝐝 𝐋𝐢𝐛𝐫𝐚𝐫𝐢𝐞𝐬

Install the required library:

```bash
pip install scikit-learn
```

---

## ▶️ 𝐇𝐨𝐰 𝐓𝐨 𝐑𝐮𝐧

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/rain-prediction-random-forest.git
```

### 2️⃣ Navigate to the project folder

```bash
cd rain-prediction-random-forest
```

### 3️⃣ Run the program

```bash
python rain_prediction.py

## 📸 𝐒𝐚𝐦𝐩𝐥𝐞 𝐎𝐮𝐭𝐩𝐮𝐭

### Example 1

```text
Enter Temperature: 24
Enter Humidity: 88

Prediction: Rain
```

### Example 2

```text
Enter Temperature: 34
Enter Humidity: 45

Prediction: No Rain
```

---

## ⚙️ 𝐇𝐨𝐰 𝐈𝐭 𝐖𝐨𝐫𝐤𝐬

1. Import the Random Forest Classifier.
2. Create a sample weather dataset.
3. Train the Random Forest model.
4. Accept temperature and humidity as user input.
5. Predict whether it will rain.
6. Display the prediction.

---

## 🌲 𝐌𝐚𝐜𝐡𝐢𝐧𝐞 𝐋𝐞𝐚𝐫𝐧𝐢𝐧𝐠 𝐀𝐥𝐠𝐨𝐫𝐢𝐭𝐡𝐦

### Random Forest Classifier

Random Forest is a supervised machine learning algorithm used for classification and regression tasks. It builds multiple decision trees and combines their predictions to improve accuracy and reduce overfitting.

**Advantages:**

- ✔ High Accuracy
- ✔ Handles Non-linear Data
- ✔ Reduces Overfitting
- ✔ Robust and Reliable

---

## 🚀 𝐅𝐮𝐭𝐮𝐫𝐞 𝐄𝐧𝐡𝐚𝐧𝐜𝐞𝐦𝐞𝐧𝐭𝐬

⭐ Train the model using a real weather dataset

⭐ Include additional weather features like:

- Wind Speed
- Atmospheric Pressure
- Cloud Cover
- Rainfall History

⭐ Visualize weather patterns using Matplotlib

⭐ Build a Weather Prediction Web App using Streamlit or Flask

---

## 📁 𝐏𝐫𝐨𝐣𝐞𝐜𝐭 𝐒𝐭𝐫𝐮𝐜𝐭𝐮𝐫𝐞

```
Rain-Prediction-Random-Forest/
│
├── rain_prediction.py
├── README.md
└── requirements.txt
```

---

## 👨‍💻 𝐀𝐮𝐭𝐡𝐨𝐫

**Sanjay palaniyappan senthil kumar**

---

This project is licensed under the **MIT License**.

---

⭐ **If you found this project helpful, please consider giving it a Star on GitHub!**
