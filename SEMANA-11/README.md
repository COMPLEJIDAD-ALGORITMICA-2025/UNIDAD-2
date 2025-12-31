# 📘 Semana 11 – Flujo Máximo en Redes

Este directorio contiene el material correspondiente a la **Semana 11** del curso de **Complejidad Algorítmica**, donde se estudia el **problema del Flujo Máximo en redes**, uno de los problemas fundamentales de optimización en **grafos dirigidos ponderados**.

Durante esta semana se introducen los conceptos básicos de redes de flujo y se analiza el **Algoritmo de Ford–Fulkerson**, junto con sus aplicaciones en sistemas reales como tráfico, redes eléctricas y transporte de recursos.

---

## 📌 Contenidos principales

Los archivos PDF y notebooks incluidos en esta carpeta desarrollan los siguientes temas:

---

## 🔹 Conceptos básicos de flujos en redes

### 📍 Red y flujo
- Una **red** es un grafo dirigido con **capacidades** asociadas a sus aristas.
- Un **flujo** representa la cantidad de algún recurso que circula por la red:
  - Datos
  - Agua
  - Tráfico
  - Corriente eléctrica

### 📍 Elementos de una red de flujo
- **Fuente (s)**: nodo que produce flujo.
- **Sumidero (t)**: nodo que consume flujo.
- **Capacidad** \( c(u,v) \): máximo flujo permitido por una arista.
- **Flujo** \( f(u,v) \): cantidad real de flujo que circula por la arista.

### 📍 Restricciones del flujo
- \( f(u,v) \leq c(u,v) \)
- Conservación del flujo:
  - Para todo nodo intermedio, el flujo de entrada es igual al de salida.
- El flujo total que sale de la fuente es igual al flujo total que llega al sumidero.

---

## 🔹 El problema del Flujo Máximo

- Consiste en determinar la **máxima cantidad de flujo** que puede enviarse desde la fuente \( s \) hasta el sumidero \( t \).
- El valor del flujo máximo corresponde:
  - A la suma del flujo que sale de la fuente.
  - A la suma del flujo que entra al sumidero.
- Permite optimizar el uso de recursos y evitar desperdicios.

---

## 🔹 Algoritmo de Ford–Fulkerson

### 📍 Idea general
- Algoritmo **voraz (greedy)**.
- Busca **caminos de aumento** desde \( s \) hasta \( t \).
- Incrementa el flujo a lo largo del camino según la **capacidad residual mínima**.

### 📍 Conceptos clave
- **Camino de aumento**: camino desde la fuente al sumidero con capacidad residual disponible.
- **Capacidad residual**:
  \[
  c(e) - f(e)
  \]
- **Grafo residual**: red que representa las capacidades restantes.

### 📍 Pasos del algoritmo
1. Inicializar el flujo de todas las aristas en 0.
2. Buscar un camino de aumento entre \( s \) y \( t \) (usando DFS o BFS).
3. Calcular la capacidad residual mínima del camino.
4. Aumentar el flujo en todas las aristas del camino.
5. Actualizar el grafo residual.
6. Repetir hasta que no existan más caminos de aumento.

### 📍 Resultado
- Cuando no hay más caminos de aumento, el flujo alcanzado es el **flujo máximo** de la red.

---

## 🔹 Ejemplos prácticos

- Representación paso a paso del grafo residual.
- Identificación de múltiples caminos de aumento.
- Cálculo incremental del flujo máximo.
- Verificación de que el flujo total que sale de la fuente es igual al que entra al sumidero.

---

## 🔹 Aplicaciones del Flujo Máximo

- Gestión de tráfico vehicular.
- Redes de transporte y logística.
- Sistemas eléctricos (corriente máxima).
- Redes de agua y alcantarillado.
- Redes de comunicación y transmisión de datos.

---

## 🧪 Ejercicios prácticos

- Implementación del algoritmo de Ford–Fulkerson.
- Representación del grafo residual.
- Cálculo manual y programado del flujo máximo.
- Resolución de ejemplos clásicos de redes de flujo.
- Validación de resultados mediante notebooks en Python.

---

## 🎯 Objetivo de la semana

Al finalizar esta semana, el estudiante será capaz de:

- Comprender el concepto de red de flujo.
- Modelar problemas reales como redes de flujo.
- Implementar el algoritmo de Ford–Fulkerson.
- Identificar caminos de aumento y capacidades residuales.
- Calcular el flujo máximo en grafos dirigidos.
- Analizar la complejidad algorítmica del proceso.

---

## 📂 Estructura del contenido

- Diapositivas teóricas del Módulo 11.
- Notebooks en Python:
  - Implementación de Ford–Fulkerson.
  - Ejemplos guiados de flujo máximo.
  - Pruebas y borradores de solución.
- Ejercicios resueltos y análisis paso a paso.

---

📌 **Nota:**  
Este material corresponde exclusivamente a la **Semana 11** y cierra el bloque de **algoritmos de optimización en grafos**, consolidando el estudio de técnicas voraces aplicadas a problemas de redes.
