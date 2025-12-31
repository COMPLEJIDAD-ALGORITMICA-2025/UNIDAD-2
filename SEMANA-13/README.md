# 📘 Semana 13 – Programación Dinámica en Grafos

Este directorio contiene el material correspondiente a la **Semana 13** del curso de **Complejidad Algorítmica**, donde se estudia la aplicación del paradigma de **Programación Dinámica (DP)** en **grafos ponderados**, con énfasis en la resolución de **problemas de caminos mínimos**.

Durante esta semana se analizan los algoritmos **Bellman-Ford** y **Floyd-Warshall**, ambos fundamentales para el cálculo de rutas óptimas en grafos, especialmente cuando existen **pesos negativos**.

---

## 📌 Contenidos principales

Los archivos PDF, notebooks y hojas de ejercicios incluidos en esta carpeta desarrollan los siguientes temas:

---

## 🔹 Programación Dinámica aplicada a Grafos

### 📍 Objetivo de la DP en grafos
- Encontrar **caminos mínimos** en grafos ponderados.
- Resolver problemas donde los subproblemas se superponen.
- Aplicar un enfoque **bottom-up** para mejorar la eficiencia.
- Manejar grafos con **pesos negativos** y detectar ciclos negativos.

---

## 🔹 Algoritmo Bellman-Ford

### 📍 Objetivo
- Calcular el camino más corto desde un **vértice origen** hacia todos los demás vértices de un grafo dirigido y ponderado.
- Funciona correctamente incluso cuando existen **aristas con peso negativo**.

### 📍 Características principales
- Basado en **Programación Dinámica**.
- Relaja todas las aristas del grafo **(|V| − 1)** veces.
- Permite **detectar ciclos de peso negativo**.

### 📍 Funcionamiento general
1. Inicializar las distancias desde el vértice origen.
2. Relajar todas las aristas repetidamente.
3. Verificar si aún es posible reducir alguna distancia:
   - Si es así, el grafo contiene un **ciclo negativo**.
   - En caso contrario, las distancias obtenidas son óptimas.

### 📍 Complejidad
\[
O(V \times E)
\]

---

## 🔹 Algoritmo Floyd-Warshall

### 📍 Objetivo
- Calcular el camino más corto **entre todos los pares de vértices** en un grafo ponderado.

### 📍 Características principales
- Enfoque clásico de **Programación Dinámica**.
- Utiliza una **matriz de distancias**.
- Considera cada vértice como posible intermediario.
- Funciona con pesos negativos (si no existen ciclos negativos).

### 📍 Funcionamiento general
1. Inicializar la matriz de distancias.
2. Iterar sobre todos los vértices como intermediarios.
3. Actualizar las distancias mínimas posibles.

### 📍 Complejidad
\[
O(V^3)
\]

---

## 🔹 Detección de ciclos negativos

- Un **ciclo negativo** es aquel cuya suma total de pesos es negativa.
- Bellman-Ford permite detectar este tipo de ciclos.
- La presencia de un ciclo negativo implica que **no existe una distancia mínima finita**.

---

## 🧪 Ejercicios prácticos

- Implementación de:
  - Algoritmo Bellman-Ford.
  - Algoritmo Floyd-Warshall.
- Detección de ciclos negativos.
- Resolución de la **Hoja de Ejercicios 13**.
- Análisis comparativo de eficiencia.
- Ejemplos prácticos usando grafos ponderados.

---

## 🎯 Objetivo de la semana

Al finalizar esta semana, el estudiante será capaz de:

- Aplicar programación dinámica a problemas de grafos.
- Implementar Bellman-Ford y Floyd-Warshall.
- Detectar ciclos negativos en grafos.
- Analizar la complejidad temporal de algoritmos DP en grafos.
- Comparar algoritmos de caminos mínimos según el tipo de grafo.

---

## 📂 Estructura del contenido

- Diapositivas teóricas del Módulo 13.
- Hoja de Ejercicios 13.
- Notebooks en Python:
  - Bellman-Ford.
  - Floyd-Warshall.
  - Ejercicios complementarios y pruebas.
- Ejemplos paso a paso y análisis de resultados.

---

📌 **Nota:**  
Este material corresponde exclusivamente a la **Semana 13** y consolida el uso de **Programación Dinámica en Grafos**, cerrando el estudio de algoritmos de rutas mínimas dentro del curso.
