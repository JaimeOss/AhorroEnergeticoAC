# 🌡️ AC Energy Savings Calculator — Cartagena

A mobile-first web tool to calculate and compare the **monthly electricity cost in Colombian pesos (COP)** between **conventional and inverter air conditioners** at **9,000 and 12,000 BTU**, tailored to the tropical climate of **Cartagena, Colombia**.

## 🔗 Live Demo

https://jaimeoss.github.io/AhorroEnergeticoAC/

## What problem does it solve?

In Cartagena, with temperatures averaging **32°C year-round**, air conditioning is a necessity — and one of the biggest items on the electricity bill. This calculator answers one concrete question:

> *How much does an inverter unit actually save compared to a conventional one?*

## ✨ Features

- Compares **conventional vs inverter** for 9,000 and 12,000 BTU simultaneously
- Adjustable **kWh cost** to match your energy provider (Air-e, Afinia, etc.)
- **Daily usage hours** control via slider
- **Target temperature** selector (16°C – 28°C)
- Simulate **1 to 10 units** at once
- Displays **estimated monthly savings** and efficiency percentage
- Models real inverter behavior: **peak consumption in the first hour**, then stabilized usage
- Automatic adjustment by thermal differential (**8% per degree** from 24°C baseline)
- **Mobile-first** design, optimized for smartphones

## 📸 Preview

> *(Add a screenshot here)*

## 🚀 Usage

No installation required. Open `index.html` directly in any modern browser, or visit the live demo.
```bash
git clone https://github.com/JaimeOss/AhorroEnergeticoAC.git
# Open index.html in your browser
```

## 🛠️ Tech Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)

- HTML5, CSS3 and vanilla JavaScript
- Tailwind CSS (CDN)
- No frameworks, no dependencies, no backend

## 📊 Technical Reference

| Unit | Capacity | Consumption |
|------|----------|-------------|
| Conventional | 9,000 BTU | 0.82 kWh/h (fixed) |
| Inverter | 9,000 BTU | 0.95 kWh/h (peak) → 0.38 kWh/h (steady) |
| Conventional | 12,000 BTU | 1.15 kWh/h (fixed) |
| Inverter | 12,000 BTU | 1.25 kWh/h (peak) → 0.52 kWh/h (steady) |

> Baseline ambient temperature: **32°C** (typical Cartagena condition)

## 👤 Author

**Jaime Oss** — [@JaimeOss](https://github.com/JaimeOss)

---

⭐ If you found this useful, consider starring the repository.

📖 [Leer en Español](README.es.md)