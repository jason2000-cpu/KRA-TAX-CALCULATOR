# KRA-TAX-CALCULATOR

# 🧮 KRA TAX CALCULATOR  

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
![Status](https://img.shields.io/badge/status-active-success.svg)
![Made with JavaScript](https://img.shields.io/badge/Made%20with-JavaScript-yellow)
![Made in Kenya](https://img.shields.io/badge/Made%20in-Kenya-green)

A simple and interactive web-based tool that helps Kenyan employees estimate their **net salary** after applying the **Kenya Revenue Authority (KRA)** PAYE tax bands.  

---

## 📑 Table of Contents  
- [🎯 Purpose](#-purpose)  
- [✨ Features](#-features)  
- [⚙️ How It Works](#️-how-it-works)  
- [🧰 Tech Stack](#-tech-stack)  
- [🚀 Getting Started](#-getting-started)  
- [🧠 Usage](#-usage)  
- [💰 Tax Band Reference](#-tax-band-reference)  
- [🤝 Contributing](#-contributing)  
- [📄 License](#-license)  

---

## 🎯 Purpose  
This project was created to:  
- Help Kenyan employees easily calculate **PAYE tax deductions** and **net income**.  
- Provide a real-world example of how JavaScript can handle business logic (tax computation).  
- Serve as a learning project for frontend developers working with user input and computation logic.  

---

## ✨ Features  
✅ Accepts **gross monthly salary** input.  
✅ Calculates PAYE tax using **official KRA tax bands**.  
✅ Displays **net salary** and **tax amount** clearly.  
✅ Fully **client-side** — no backend or database required.  
✅ Simple, responsive interface built with **HTML, CSS, and JavaScript**.  

---

## ⚙️ How It Works  
1. User enters **gross monthly salary** in Kenyan Shillings.  
2. The script computes **taxable income** and applies the correct **PAYE tax brackets**:  
   | Monthly Band (KES) | Annual Band (KES) | Rate |
   |--------------------|-------------------|-------|
   | First 24,000       | First 288,000     | 10%   |
   | Next 8,333         | Next 100,000      | 25%   |
   | Next 467,667       | Next 5,612,000    | 30%   |
   | Next 300,000       | Next 3,600,000    | 32.5% |
   | Above 800,000      | Above 9,600,000   | 35%   |
3. A **personal relief** of KSh 2,400 per month (KSh 28,800 per annum) is deducted.  
4. The resulting **tax due** is subtracted from the gross salary to yield the **net salary**.  

> ℹ️ Depending on version, other deductions such as **NSSF**, **SHIF**, or **Housing Levy** may be added later.

---

## 🧰 Tech Stack  
- **HTML5** – structure of the calculator  
- **CSS3** – styling and layout  
- **JavaScript (ES6)** – tax logic and DOM manipulation  
- **Git & GitHub** – version control and collaboration  

---

## 🚀 Getting Started  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/jason2000-cpu/KRA-TAX-CALCULATOR.git
```


### 2️⃣ Open the Project

Navigate to the project folder:

cd KRA-TAX-CALCULATOR

### 3️⃣ Run Locally

Simply open the file index.html in your browser.
No installations or servers needed — it runs entirely in your browser!

