# Bubble-Sort-Comparacion
Bubble sort
# Optimización del Algoritmo Bubble Sort en Java

## 📌 Descripción

Este proyecto implementa el algoritmo de ordenamiento Bubble Sort en Java, incluyendo:

- Versión tradicional
- Versión optimizada utilizando la marca del último intercambio

El objetivo es analizar la eficiencia del algoritmo y comparar su rendimiento en distintos escenarios.

---

## 🎯 Objetivo de la práctica

- Implementar Bubble Sort tradicional.
- Optimizar el algoritmo reduciendo pasadas innecesarias.
- Medir tiempos de ejecución con System.nanoTime().
- Comparar resultados en diferentes tipos de arreglos.

---

## 🧪 Escenarios evaluados

Se probaron tres tipos de arreglos:

1. Aleatorio  
2. Ordenado (mejor caso)  
3. Inverso (peor caso)

Se utilizaron distintos tamaños de entrada para analizar el crecimiento del tiempo de ejecución.

---

## 📂 Archivos del repositorio

- BubbleSortComparacion.java → Código fuente del programa.
- Informe_BubbleSort.pdf → Documento con análisis y gráfica de resultados.
- Conversacion_ChatGPT.md → Registro del uso de ChatGPT.

---

## ▶️ Cómo ejecutar el programa

1. Abrir la terminal en la carpeta del proyecto.
2. Compilar:

   javac BubbleSortComparacion.java

3. Ejecutar:

   java BubbleSortComparacion

---

## 📊 Resultados

Los resultados muestran que la versión optimizada mejora significativamente el tiempo de ejecución cuando el arreglo está ordenado, reduciendo comparaciones innecesarias. Sin embargo, en casos aleatorios e inversos, el comportamiento sigue siendo cuadrático O(n²).

