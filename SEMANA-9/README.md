# 📘 Semana 9 – Conjuntos Disjuntos (Union-Find / UFDS)

Este directorio contiene el material correspondiente a la **Semana 9** del curso de **Complejidad Algorítmica**, donde se estudia la **estructura de datos de Conjuntos Disjuntos**, también conocida como **Union-Find Disjoint Sets (UFDS)**.

Esta estructura es fundamental para resolver problemas de **conectividad**, **componentes conexos** y **detección de ciclos**, especialmente en grafos no dirigidos y aplicaciones a gran escala.

---

## 📌 Contenidos principales

Los archivos PDF, notebooks y hojas de ejercicios incluidos en esta carpeta desarrollan los siguientes temas:

---

## 🔹 Introducción a Union-Find Disjoint Sets (UFDS)

- Estructura de datos que mantiene una colección de **conjuntos disjuntos** (no superpuestos).
- Cada conjunto tiene un **representante**.
- Dos elementos pertenecen al mismo conjunto si comparten el mismo representante.
- Se basa en dos operaciones fundamentales:
  - **Find**: determina el representante de un elemento.
  - **Union**: une dos conjuntos distintos.

### 📍 Propiedades de la conectividad
- Reflexiva.
- Simétrica.
- Transitiva.
- Relación directa con los **componentes conexos** de un grafo.

---

## 🔹 Aplicaciones de UFDS

- Detección de conectividad entre nodos.
- Agrupación de elementos relacionados.
- Detección de ciclos en grafos no dirigidos.
- Redes sociales (amigos directos e indirectos).
- Redes de computadoras.
- Análisis de componentes conexos.

---

## 🔹 Algoritmos Union-Find

### 🔸 Quick-Find
- Cada elemento mantiene un identificador de conjunto.
- **Find**: O(1).
- **Union**: O(n).
- Desventaja: muy costoso cuando hay muchas uniones.

### 🔸 Quick-Union
- Representa cada conjunto como un árbol.
- **Find**: proporcional a la altura del árbol.
- **Union**: enlaza la raíz de un árbol con otro.
- Problema: los árboles pueden volverse muy altos.

### 🔸 Quick-Union Ponderado
- Mejora de Quick-Union.
- Une siempre el árbol más pequeño debajo del más grande.
- Reduce la altura del árbol.
- **Complejidad**:
  - Find: O(log n)
  - Union: O(log n)

### 🔸 Compresión de caminos
- Optimiza la operación Find.
- Reduce drásticamente la altura del árbol.
- Combinada con ponderación, logra complejidad casi constante:
  \[
  O(\alpha(n))
  \]
  donde \( \alpha \) es la función inversa de Ackermann.

---

## 🔹 Ejercicios prácticos

- Implementación de:
  - Find y Union.
  - Quick-Find.
  - Quick-Union.
  - Quick-Union Ponderado.
  - Compresión de caminos.
- Gestión de grupos de amigos (conectividad directa e indirecta).
- Detección de ciclos en grafos no dirigidos usando UFDS.
- Análisis comparativo del rendimiento de cada variante.

---

## 🎯 Objetivo de la semana

Al finalizar esta semana, el estudiante será capaz de:

- Comprender el funcionamiento interno de la estructura UFDS.
- Implementar distintas variantes de Union-Find.
- Analizar la complejidad temporal de cada estrategia.
- Resolver problemas de conectividad de manera eficiente.
- Aplicar UFDS en grafos y problemas reales de gran tamaño.

---

## 📂 Estructura del contenido

- Diapositivas teóricas del Módulo 9.
- Hoja de Ejercicios 9.
- Notebooks en Python:
  - Quick-Find.
  - Quick-Union.
  - Quick-Union Ponderado.
  - Optimización con compresión de caminos.
- Ejercicios resueltos y análisis de complejidad.

---

📌 **Nota:**  
Este material corresponde exclusivamente a la **Semana 9** y marca la introducción a estructuras de datos avanzadas utilizadas en algoritmos de grafos, optimización y problemas de conectividad a gran escala.
