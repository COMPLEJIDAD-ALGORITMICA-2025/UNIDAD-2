# 📘 Semana 12 – Programación Dinámica: Casos de Uso

Este directorio contiene el material correspondiente a la **Semana 12** del curso de **Complejidad Algorítmica**, donde se estudia el paradigma de **Programación Dinámica (DP)** aplicado a problemas clásicos de optimización.

Durante esta semana se analizan los **principios fundamentales de la programación dinámica** y se desarrollan soluciones eficientes para problemas que presentan **subestructura óptima** y **subproblemas superpuestos**.

---

## 📌 Contenidos principales

Los archivos PDF, notebooks y hojas de ejercicios incluidos en esta carpeta desarrollan los siguientes temas:

---

## 🔹 Introducción a la Programación Dinámica

### 📍 ¿Qué es Programación Dinámica?
- Paradigma algorítmico para resolver problemas complejos dividiéndolos en subproblemas más pequeños.
- Almacena soluciones parciales para evitar cálculos repetidos.
- Se aplica cuando el problema cumple:
  - **Subestructura óptima**
  - **Subproblemas superpuestos**

### 📍 Pasos para resolver un problema con DP
1. Reconocer el problema de programación dinámica.
2. Identificar las variables del problema.
3. Formular la relación de recurrencia.
4. Definir los casos base.
5. Elegir enfoque iterativo o recursivo.
6. Aplicar **memorización** o **tabulación**.

---

## 🔹 Casos de uso de Programación Dinámica

### 🔸 Sucesión de Fibonacci
- Implementación usando programación dinámica.
- Comparación con la solución recursiva simple.
- Optimización del tiempo de ejecución.

### 🔸 El problema de la Mochila (Knapsack)
- Dada una mochila con capacidad limitada, seleccionar artículos para **maximizar la ganancia**.
- Construcción de una tabla DP.
- Complejidad:
  \[
  O(N \times W)
  \]
  donde \( N \) es el número de artículos y \( W \) la capacidad de la mochila.

### 🔸 Problema del Cambio Mínimo de Monedas
- Determinar el **mínimo número de monedas** necesarias para dar un monto dado.
- No siempre se puede resolver de forma óptima con algoritmos voraces.
- Definición recursiva:
  \[
  C[p] = \min_{d_i \leq p} (1 + C[p - d_i])
  \]
- Complejidad:
  \[
  O(m \times n)
  \]
  donde \( m \) es el número de monedas y \( n \) el monto a cambiar.

### 🔸 La función de Ackermann
- Función altamente recursiva.
- Implementación mediante programación dinámica para reducir redundancias.
- Ejemplo de crecimiento rápido en funciones recursivas.

### 🔸 Problemas de optimización financiera
- Distribución óptima de inversión entre múltiples bancos.
- Maximización de beneficios bajo restricciones.
- Aplicación directa de DP en decisiones económicas.

---

## 🧪 Ejercicios prácticos

- Implementación de:
  - Fibonacci con DP.
  - Problema de la mochila.
  - Cambio mínimo de monedas.
  - Función de Ackermann.
- Construcción y análisis de tablas DP.
- Comparación entre soluciones voraces y DP.
- Resolución de la **Hoja de Ejercicios 12**.

---

## 🎯 Objetivo de la semana

Al finalizar esta semana, el estudiante será capaz de:

- Identificar problemas que se resuelven con programación dinámica.
- Formular relaciones de recurrencia.
- Implementar soluciones eficientes usando DP.
- Comparar DP con algoritmos voraces.
- Analizar la complejidad temporal y espacial de los algoritmos DP.
- Aplicar programación dinámica a problemas reales de optimización.

---

## 📂 Estructura del contenido

- Diapositivas teóricas del Módulo 12.
- Hoja de Ejercicios 12.
- Notebooks en Python:
  - Problema de la mochila (DP).
  - Cambio mínimo de monedas (DP).
  - Ejercicios complementarios.
- Ejemplos paso a paso y análisis de resultados.

---

📌 **Nota:**  
Este material corresponde exclusivamente a la **Semana 12** y cierra el bloque de **algoritmos voraces y programación dinámica**, consolidando técnicas clave para la resolución de problemas de optimización y toma de decisiones.
