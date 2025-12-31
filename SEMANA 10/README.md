# 📘 Semana 10 – Árbol de Expansión Mínima (MST)

Este directorio contiene el material correspondiente a la **Semana 10** del curso de **Complejidad Algorítmica**, donde se estudia el problema del **Árbol de Expansión Mínima (Minimum Spanning Tree – MST)**, uno de los problemas clásicos de optimización en grafos ponderados.

Durante esta semana se analizan los conceptos básicos de árboles y grafos, y se implementan los algoritmos voraces más utilizados para hallar el MST: **Kruskal** y **Prim**.

---

## 📌 Contenidos principales

Los archivos PDF, notebooks y hojas de ejercicios incluidos en esta carpeta desarrollan los siguientes temas:

---

## 🔹 Conceptos básicos

### 📍 Árbol y grafo
- Diferencias entre **árbol** y **grafo**.
- Características de un árbol:
  - Grafo conexo y acíclico.
  - Contiene exactamente \( n-1 \) aristas.
- Definición de **bosque** como conjunto disjunto de árboles.

### 📍 Árbol de Expansión (Spanning Tree)
- Subgrafo que:
  - Incluye todos los vértices del grafo original.
  - No contiene ciclos.
- Un grafo puede tener **múltiples árboles de expansión**.

### 📍 Árbol de Expansión Mínima (MST)
- Árbol de expansión cuyo **peso total de aristas es mínimo**.
- Puede existir más de un MST válido para un mismo grafo.
- Problema clásico de **optimización de redes**.

---

## 🔹 Algoritmos para obtener el MST

### 🔸 Algoritmo de Kruskal
- Algoritmo **voraz (greedy)**.
- Selecciona aristas en orden creciente de peso.
- Solo agrega una arista si **no forma ciclos**.
- Utiliza la estructura **Union-Find (UFDS)** para detección eficiente de ciclos.
- Complejidad típica:
  \[
  O(E \log E)
  \]

### 🔸 Algoritmo de Prim
- Algoritmo **voraz**.
- Construye el MST **agregando vértices** a partir de un nodo inicial.
- Utiliza estructuras como:
  - Arreglos de costos.
  - Colas de prioridad.
- Complejidad:
  - Implementación básica: \( O(V^2) \)
  - Con cola de prioridad: \( O(E \log V) \)

---

## 🔹 Comparación Kruskal vs Prim

| Característica | Kruskal | Prim |
|----------------|---------|------|
| Enfoque | Por aristas | Por vértices |
| Tipo | Greedy | Greedy |
| Uso de UFDS | Sí | No |
| Ideal para | Grafos dispersos | Grafos densos |
| Detección de ciclos | Union-Find | Implícita |

---

## 🔹 Aplicaciones del MST

- Diseño de redes eléctricas.
- Cableado de redes de computadoras.
- Redes de telecomunicaciones.
- Rutas de transporte y logística.
- Clustering y análisis de similitud.
- Optimización de costos de infraestructura.

---

## 🧪 Ejercicios prácticos

- Implementación de:
  - Algoritmo de fuerza bruta para MST.
  - Algoritmo de Prim.
  - Algoritmo de Kruskal.
- Uso de listas de adyacencia.
- Análisis del costo total del MST.
- Problema de **clustering** basado en MST.

---

## 🎯 Objetivo de la semana

Al finalizar esta semana, el estudiante será capaz de:

- Comprender el concepto de árbol de expansión mínima.
- Diferenciar árboles, grafos y bosques.
- Implementar los algoritmos de Prim y Kruskal.
- Analizar la complejidad algorítmica de cada enfoque.
- Aplicar MST a problemas reales de optimización.

---

## 📂 Estructura del contenido

- Diapositivas teóricas del Módulo 10.
- Hoja de Ejercicios 10.
- Notebooks en Python:
  - MST general.
  - Kruskal (lista de adyacencia).
  - Prim (lista de adyacencia).
- Ejercicios resueltos y ejemplos prácticos.

---

📌 **Nota:**  
Este material corresponde exclusivamente a la **Semana 10** y consolida el uso de **algoritmos voraces** en la resolución de problemas clásicos de grafos y optimización.
