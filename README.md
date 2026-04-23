📚 Bootcamp Big Data: Prácticas de Matemáticas y Estadística
Este repositorio contiene las soluciones detalladas a las prácticas de los módulos de Estadística y Álgebra Lineal correspondientes al programa de Big Data. 
El objetivo de estos proyectos es aplicar conceptos matemáticos y estadísticos fundamentales mediante la programación en R y Python.

📊 Módulo 1: Estadística con R
Archivo: Practica-LuisManuelHernandezCancho.qmd
En esta práctica se realiza un análisis exploratorio y predictivo utilizando un dataset de listados de AirBnB en Madrid.

Puntos Clave:
- Análisis Exploratorio de Datos (EDA): Limpieza y transformación de variables relacionadas con alojamientos.
- Modelado Predictivo: Creación de un modelo de regresión para estimar los metros cuadrados (Square.Meters) de una propiedad basándose en características como el número de habitaciones, baños y capacidad.
- Tratamiento de NAs: Implementación de técnicas para rellenar valores faltantes mediante las predicciones del modelo ajustado.

📐 Módulo 2: Álgebra Lineal con Python
Archivo: ALG-PRACTICA_propuestaresuelto.ipynb
Esta práctica se centra en la implementación de algoritmos de Regresión Lineal desde una perspectiva algebraica, utilizando el dataset Auto MPG del repositorio UC Irvine.

Puntos Clave:
- Regresión Lineal por Mínimos Cuadrados: Implementación de la forma matricial $\widehat{w} = (X^T X)^{-1}X^T y$ para el cálculo de pesos.
- Descenso del Gradiente: Aplicación del algoritmo de optimización para ajustar la recta de regresión de forma iterativa.
- Visualización: Generación de gráficos comparativos entre los datos reales y las predicciones del modelo (MPG vs Peso/Caballos de fuerza).

🛠️ Tecnologías Utilizadas
- Lenguajes: R (Quarto), Python (Jupyter Notebook).
- Librerías R: dplyr, ggplot2.
- Librerías Python: numpy, pandas, matplotlib, ucimlrepo.

🚀 Ejecución
Para visualizar los notebooks:
- Asegúrate de tener instalado RStudio para el archivo .qmd.
- Para el archivo .ipynb, puedes usar Jupyter Lab o VS Code.
- Se requiere la instalación de la librería ucimlrepo en Python para la descarga automática del dataset.
