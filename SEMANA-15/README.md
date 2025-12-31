# 📘 Semana 15 – Problemas de Tipo P vs NP

Este directorio contiene el material correspondiente a la **Semana 15** del curso de **Complejidad Algorítmica**, donde se introduce la **Teoría de la Complejidad Computacional**, enfocándose en la clasificación de los problemas en las clases **P**, **NP**, **NP-Complete** y **NP-Hard**.

Durante esta semana se analizan los límites de lo que puede resolverse eficientemente mediante algoritmos y se estudia uno de los problemas abiertos más importantes de la informática: **¿P = NP?**

---

## 📌 Contenidos principales

Los archivos PDF incluidos en esta carpeta desarrollan los siguientes temas:

---

## 🔹 Importancia de clasificar los problemas computacionales

- La clasificación de un problema permite saber:
  - Si es resoluble algorítmicamente.
  - Si puede resolverse en un tiempo razonable.
- La **teoría de la complejidad** se enfoca en el problema, no en el algoritmo específico.
- Un problema mal clasificado puede llevar a soluciones inviables en la práctica.

---

## 🔹 Tipos de problemas computacionales

### 📍 Problemas tratables
- Problemas que se pueden resolver en **tiempo polinomial**.
- Complejidades consideradas eficientes:
  - \( O(1) \), \( O(n) \), \( O(n \log n) \), \( O(n^2) \), \( O(n^3) \).

### 📍 Problemas no tratables
- Problemas que crecen de forma **exponencial o factorial**:
  - \( O(2^n) \), \( O(n!) \).
- No pueden resolverse en un tiempo razonable para entradas grandes.

---

## 🔹 Problemas de decisión y optimización

- **Problemas de decisión**:
  - Respuesta **sí/no**.
  - Ejemplo:  
    ¿Existe un árbol de expansión mínima de peso ≤ W?

- **Problemas de optimización**:
  - Buscan la mejor solución posible.
  - Ejemplos:
    - Mochila 0-1.
    - Árbol de expansión mínima (MST).
    - Problema del viajero (TSP).

- Muchos problemas de optimización pueden transformarse en problemas de decisión.

---

## 🔹 Clases de complejidad

### 🔸 Clase P
- Problemas que pueden resolverse en **tiempo polinomial** usando algoritmos deterministas.
- Considerados **eficientes**.
- Ejemplos:
  - Búsqueda y ordenamiento.
  - MST.
  - Versiones tratables de la mochila.

### 🔸 Clase NP
- Problemas cuyas soluciones pueden **verificarse** en tiempo polinomial.
- Utilizan modelos no deterministas.
- Ejemplos:
  - Mochila.
  - TSP.
  - SAT.
  - Coloración de grafos.

### 🔸 NP-Complete
- Problemas más difíciles dentro de NP.
- Si uno de ellos se resuelve en tiempo polinomial, entonces **P = NP**.
- Son problemas NP a los que todos los demás problemas NP pueden reducirse.

### 🔸 NP-Hard
- Problemas al menos tan difíciles como los NP-Complete.
- No necesariamente pertenecen a NP.
- Pueden no ser problemas de decisión.

---

## 🔹 Relación entre P y NP

- Se cumple:
  \[
  P \subseteq NP
  \]
- Se cree que:
  \[
  P \neq NP
  \]
- Demostrar si \( P = NP \) o \( P \neq NP \) es uno de los **grandes problemas abiertos** de la informática teórica.

---

## 🎯 Objetivo de la semana

Al finalizar esta semana, el estudiante será capaz de:

- Comprender la importancia de la teoría de la complejidad.
- Clasificar problemas computacionales en P, NP, NP-Complete y NP-Hard.
- Diferenciar problemas tratables e intratables.
- Reconocer problemas de decisión y optimización.
- Entender el impacto práctico del problema **P vs NP**.

---

## 📂 Estructura del contenido

- Diapositivas teóricas del Módulo 15.
- Ejemplos conceptuales de problemas P y NP.
- Diagramas de clasificación de complejidad.
- Análisis teórico y conclusiones.

---

📌 **Nota:**  
Este material corresponde exclusivamente a la **Semana 15** y **cierra el curso de Complejidad Algorítmica**, proporcionando una visión global de los límites teóricos de los algoritmos y la computación.
