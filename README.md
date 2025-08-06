
# 📄 README – TIC_Repository-Análisis 404: Razones por las que las tiendas de barrio NO usan Internet

## 📌 Descripción
Este repositorio contiene el análisis completo de la pregunta 404 de la encuesta TenderosFU03, que indaga ¿por qué las tiendas de barrio no usan Internet para sus actividades económicas?.  
El estudio se basa en **507 tiendas** que declararon no utilizar Internet.
Razones para no usar internet
  "no_uso_internet1" = "Piensa que no es necesario por el tamaño o tipo",
  "no_uso_internet2" = "No sabe cómo utilizar internet",
  "no_uso_internet3" = "No tiene recursos para contratar internet",
  "no_uso_internet4" = "No tiene computador/notebook/tablet/smartphone"
---

## 📁 Estructura del repositorio
404-no-uso-internet-tiendas/
├── data/
│   └── /TenderosFU03_Publica.dta            # Datos originales (.dta)
├── scripts/
│   └── codigo                               # Script principal en R
├── logs/
│   └── tabla_404.png                        # Tabla de frecuencias generada
│   └── No_uso_internet.png                  # Gráfico de barras final
└── README.md                                # Este archivo

---

## 🛠️ Instalación
Abre R (versión ≥ 4.0) y ejecuta:
```r
install.packages(c("haven", "dplyr", "tidyr", "ggplot2", "scales", "stringr"))

git clone https://github.com/<TU USUARIO>/TIC_Repository.git
cd TIC_Repository
