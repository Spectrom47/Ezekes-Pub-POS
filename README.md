# 🍻 Ezeke's Pub - Point of Sale (Tkinter POS)

![Status](https://img.shields.io/badge/Status-Archived%20(2022)-blue)
![Score](https://img.shields.io/badge/Exam%20Score-193%2F200-brightgreen)
![Python](https://img.shields.io/badge/Python-3.x-blue)

A graphical Point of Sale (POS) system built for my **final exam** in 2022 using Python's Tkinter library. It simulates a pub environment where staff can quickly add food, drinks, and desserts to a customer's order, calculate totals, and submit the order with a branded confirmation popup.

---

## 📊 The Origin Story
This project was my final exam submission. I scored **193 out of 200** on it. 

It represents my foundational knowledge of:
- GUI development with Tkinter
- Event-driven programming (button clicks)
- Managing global state across functions
- Basic file integration (embedding images into the UI)

---

## ⚙️ Features
- **Categorized Menu**: Separate buttons for Desserts, Drinks, and Food.
- **Individual Pricing**: Each item has its own price; clicking it appends the cost to the running total.
- **Running Total**: A display screen shows the current order total.
- **Checkout Popup**: Hitting "Total" opens a branded confirmation window with a checkmark.
- **Restart Order**: Clears the current order to start fresh.
- **Pub Atmosphere**: Includes a burger and hotdog graphic placed alongside the menu.

---

## 🐞 Known Issue (V1)
The original code has a small bug in the `button_equal()` function. The `second_number` variable is referenced but was commented out during a rushed exam submission. 

> *Don't worry—this is exactly why V2 is being built!*

---

## 🚀 The Vision: V2 Refactor
I am currently applying the professional standards I've learned since 2022 to refactor this entire system:

- ✅ **Constants at the top** for prices, colors, and window sizes.
- ✅ **Pure functions** that return values instead of relying on `global` variables.
- ✅ **Separation of Concerns**: Business logic (math) separated from UI logic.
- ✅ **Fixed the `second_number` bug**.
- ✅ **Proper documentation** with a file header and line-by-line comments.

> The refactored version will be uploaded as **V2** to showcase my growth as a developer.

---

## 🛠️ How to Run (V1)
1. Make sure you have Python 3 installed.
2. Clone this repository.
3. Ensure the following image files are in the same directory:
   - `checkmark.png`
   - `Burger.png`
   - `hotdog.png`
4. Run the script:
   ```bash
   python ezekes_pub_pos.py
