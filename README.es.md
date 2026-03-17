# 🌡️ Ahorro Energético AC — Cartagena

Herramienta web móvil para calcular y comparar el **costo mensual en pesos colombianos (COP)** entre aires acondicionados **convencionales e inverter**, en capacidades de **9.000 y 12.000 BTU**, diseñada para el clima tropical de **Cartagena, Colombia**.

## 🔗 Demo en vivo

https://jaimeoss.github.io/AhorroEnergeticoAC/

## ¿Qué problema resuelve?

En Cartagena, con temperaturas que rondan los **32°C todo el año**, el aire acondicionado es una necesidad — y una de las mayores cargas en la factura de energía. Esta calculadora responde una pregunta concreta:

> *¿Cuánto me ahorra realmente un equipo inverter frente a uno convencional?*

## ✨ Funcionalidades

- Compara **convencional vs inverter** para 9.000 y 12.000 BTU simultáneamente
- Ajusta el **costo del kWh** según tu empresa prestadora (Air-e, Afinia, etc.)
- Controla las **horas de uso diario** con un slider
- Selecciona la **temperatura objetivo** (16°C – 28°C)
- Simula entre **1 y 10 unidades** de aire
- Muestra el **ahorro mensual estimado** y el porcentaje de eficiencia
- Modela el comportamiento real del inverter: **pico en la primera hora** y consumo estabilizado después
- Ajuste automático por diferencial térmico (**8% por grado** respecto a los 24°C base)
- Diseño **mobile-first**, optimizado para celular

## 📸 Vista previa

> *(Puedes agregar aquí una captura de pantalla)*

## 🚀 Uso

No requiere instalación. Abre `index.html` directamente en cualquier navegador moderno, o visita la demo en vivo.
```bash
git clone https://github.com/JaimeOss/AhorroEnergeticoAC.git
# Abre index.html en tu navegador
```

## 🛠️ Tecnologías

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)

- HTML5, CSS3 y JavaScript vanilla
- Tailwind CSS (CDN)
- Sin frameworks, sin dependencias, sin backend

## 📊 Especificaciones técnicas

| Equipo | Capacidad | Consumo |
|--------|-----------|---------|
| Convencional | 9.000 BTU | 0,82 kWh/h (fijo) |
| Inverter | 9.000 BTU | 0,95 kWh/h (pico) → 0,38 kWh/h (estable) |
| Convencional | 12.000 BTU | 1,15 kWh/h (fijo) |
| Inverter | 12.000 BTU | 1,25 kWh/h (pico) → 0,52 kWh/h (estable) |

> Temperatura ambiente base: **32°C** (condición típica Cartagena)

## 👤 Autor

**Jaime Oss** — [@JaimeOss](https://github.com/JaimeOss)

---

⭐ Si te fue útil, dale una estrella al repositorio.

📖 [Read in English](README.md)