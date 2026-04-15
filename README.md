
# 💰 Smart Income Tax Calculator

A modern, responsive, and feature-rich **Income Tax Calculator Web App** built using **HTML, CSS, and JavaScript**. This project provides a clean UI and supports both **Old and New Tax Regimes** with real-time tax computation.

---

## 🚀 Features

* ✅ **Old vs New Tax Regime Support**
* ✅ **Real-time Tax Calculation (No button click needed)**
* ✅ **Responsive & Modern UI Design**
* ✅ **Formatted Currency Output (₹ with commas)**
* ✅ **Supports Different Categories**

  * Normal
  * Senior Citizen (60+)
  * Super Senior (80+)
* ✅ **Automatic Surcharge Calculation**
* ✅ **Health & Education Cess (4%)**
* ✅ **Reset Functionality**
* ✅ **Clean and Modular Code**

---

## 📂 Project Structure

```
📁 Smart-Tax-Calculator
 ├── index.html   (Main application file)
 └── README.md    (Project documentation)
```

---

## 🧮 Tax Calculation Logic

### 🔹 Old Regime Slabs

* ₹0 – ₹2.5L → 0%
* ₹2.5L – ₹5L → 5%
* ₹5L – ₹10L → 20%
* Above ₹10L → 30%

👉 Basic exemption varies:

* Normal → ₹2.5L
* Senior → ₹3L
* Super Senior → ₹5L

---

### 🔹 New Regime Slabs

* ₹0 – ₹3L → 0%
* ₹3L – ₹6L → 5%
* ₹6L – ₹9L → 10%
* ₹9L – ₹12L → 15%
* ₹12L – ₹15L → 20%
* Above ₹15L → 30%

---

### 🔹 Additional Charges

* **Surcharge**

  * > ₹50L → 10%
  * > ₹1Cr → 15%

* **Cess**

  * 4% on (Tax + Surcharge)

---

## 🛠️ How to Run

1. Download or clone this repository
2. Open `index.html` in any browser
3. Enter income and select options
4. View results instantly 🎯

---

## 🧑‍💻 Technologies Used

* HTML5
* CSS3 (Flexbox + Modern UI)
* Vanilla JavaScript (ES6)

---

## 🎯 Future Enhancements

* 📊 Graph visualization of tax
* 📄 Downloadable PDF report
* 🌐 Backend integration (Node.js / Java)
* 📱 Mobile App version
* 💡 Tax-saving suggestions (80C, 80D, etc.)

---

## ⚠️ Disclaimer

This calculator is for **educational/demo purposes only**.
Actual tax liability may vary based on government rules, deductions, and updates.

---

## 🙌 Author

Developed as a learning + enhancement project to demonstrate:

* UI/UX Design
* JavaScript Logic Building
* Clean Code Practices

---

⭐ If you like this project, consider improving it further!
