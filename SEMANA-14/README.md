# 📘 Semana 14 – Computabilidad

Este directorio contiene el material correspondiente a la **Semana 14** del curso de **Complejidad Algorítmica**, donde se introducen los **fundamentos teóricos de la computabilidad**, abordando qué problemas pueden o no ser resueltos mediante algoritmos.

Durante esta semana se estudian **modelos formales de computación**, en particular los **Programas WHILE** y las **Máquinas de Turing**, que permiten definir formalmente el concepto de problema computable.

---

## 📌 Contenidos principales

Los archivos PDF y hojas de ejercicios incluidos en esta carpeta desarrollan los siguientes temas:

---

## 🔹 Problemas computables vs no computables

### 📍 Conceptos clave
- Diferencia entre:
  - **Resolver un problema**.
  - **Reconocer una solución**.
- Existen problemas que:
  - No tienen solución algorítmica (problemas **no computables**).
  - Son computables, pero **intratables** por su alta complejidad.
- Introducción a problemas **indecidibles**.

### 📍 Ejemplo clásico
- Determinar si un programa imprimirá un resultado específico.
- Relación con el **problema de la parada**.
- Importancia de la **teoría de la indecidibilidad**.

---

## 🔹 Computación: historia y modelos formales

### 📍 Antecedentes históricos
- **David Hilbert**: búsqueda de algoritmos para decidir verdades matemáticas.
- **Kurt Gödel (1931)**: teoremas de incompletitud.
- **Alan Turing (1936)**: definición formal de computación mediante la **Máquina de Turing**.

### 📍 Modelos formales de computación
- Programas LOOP
- Programas WHILE
- Programas GOTO
- Máquinas de Turing
- Otros modelos equivalentes

---

## 🔹 Programas WHILE

### 📍 Definición
- Modelo de programación simple basado en:
  - Asignaciones.
  - Incrementos y decrementos.
  - Composición de instrucciones.
  - Bucles WHILE.
- Utiliza un conjunto finito de variables \( x_0, x_1, x_2, \dots \).

### 📍 Semántica
- Si la variable de control es 0, el programa termina.
- En caso contrario, el programa continúa ejecutándose.
- Puede ejecutar un número **finito o infinito** de pasos.

### 📍 Computabilidad WHILE
- Demostración de funciones **WHILE-computables**, como:
  - Asignación.
  - División entera y módulo.
  - Operaciones lógicas.
  - Potencias.
  - Factorial.
  - Serie de Fibonacci.
  - Construcciones IF y FOR basadas en WHILE.

---

## 🔹 Máquinas de Turing

### 📍 Definición
- Modelo abstracto de computación capaz de resolver cualquier problema computable.
- Componentes:
  - Cinta infinita.
  - Cabezal de lectura/escritura.
  - Conjunto finito de estados.
  - Alfabeto de símbolos.
  - Reglas de transición.

### 📍 Funcionamiento
- La máquina lee un símbolo.
- Escribe un nuevo símbolo (o lo deja igual).
- Se mueve a la izquierda o derecha.
- Cambia de estado según la función de transición.

### 📍 Importancia
- Base teórica de la informática moderna.
- Define formalmente el concepto de **algoritmo**.
- Programas WHILE y Máquinas de Turing tienen el **mismo poder computacional**.

---

## 🧪 Ejercicios prácticos

- Demostración de funciones WHILE-computables.
- Construcción de programas WHILE.
- Análisis de funciones Turing-computables.
- Diseño de Máquinas de Turing para:
  - Incrementar números.
  - Replicar secuencias binarias.
  - Complemento a 2.
  - Verificación de paridad.
- Resolución de la **Hoja de Ejercicios 14**.

---

## 🎯 Objetivo de la semana

Al finalizar esta semana, el estudiante será capaz de:

- Comprender el concepto de computabilidad.
- Diferenciar problemas computables y no computables.
- Analizar programas WHILE y su poder expresivo.
- Comprender el funcionamiento de una Máquina de Turing.
- Reconocer la equivalencia entre distintos modelos de computación.
- Valorar los límites teóricos de lo que una computadora puede resolver.

---

## 📂 Estructura del contenido

- Diapositivas teóricas del Módulo 14.
- Hoja de Ejercicios 14.
- Ejemplos conceptuales de Programas WHILE.
- Diagramas y ejemplos de Máquinas de Turing.
- Análisis teórico y conclusiones.

---

📌 **Nota:**  
Este material corresponde exclusivamente a la **Semana 14** y cierra el curso abordando los **fundamentos teóricos de la computación**, estableciendo los límites de los algoritmos y los problemas que pueden ser resueltos por una computadora.
