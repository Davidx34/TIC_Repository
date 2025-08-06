# TIC_Repository
# 📄 README – Análisis 404: Razones por las que las tiendas de barrio NO usan Internet

## 📌 Descripción
Este repositorio contiene el análisis completo de la pregunta 404 de la encuesta TenderosFU03, que indaga ¿por qué las tiendas de barrio no usan Internet para sus actividades económicas?.  
El estudio se basa en **507 tiendas** que declararon no utilizar Internet.

---

## 📁 Estructura del repositorio
404-no-uso-internet-tiendas/
├── data/
│   └── TenderosFU03_BLandFUmerged_pub.dta   # Datos originales (.dta)
├── R/
│   └── 404_analisis.R                       # Script principal en R
├── logs/
│   └── tabla_404.png                        # Tabla de frecuencias generada
│   └── No_uso_internet.jpg                  # Gráfico de barras final
└── README.md                                # Este archivo

---

## 🛠️ Instalación
Abre R (versión ≥ 4.0) y ejecuta:
```r
install.packages(c("haven", "dplyr", "tidyr", "ggplot2", "scales", "stringr"))

git clone https://github.com/Davidx34/TIC_Repository.git
cd TIC_Repository
