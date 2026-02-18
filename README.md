# Estructuras de Datos. FINAL – FEBRERO – 13 / 02 / 2025  
**Examen Final: "Titanic: El Viaje Inolvidable"**

Completa los siguientes datos en la parte superior del archivo:

- **Nombre y Apellido:**
- **Email:**
- **Año, Cuatrimestre, Comisión:**
- **Carrera:**

---

## Modalidad

- **El Final es virtual pero sincrónico.**
- Los/as alumnos/as deberán conectarse al Meet, con la cámara encendida y mostrar una identificación válida (DNI/DNU).
- El examen se realizará mediante la plataforma de Github Classroom.
- Se deberá acceder al examen y al Meet sincrónico mediante el programa **Safe Exam Browser**.
- Dispondrán de **3:30 hs (tres horas y treinta minutos)** para realizar el examen.
- **Importante:** Redacta las resoluciones en los archivos correspondientes a cada ejercicio (por ejemplo: `ejercicio1.py`, `ejercicio2.py`, etc.).
- El examen se corrige al momento de la entrega.

---

## Ejercicios

### Ejercicio 1: Implementación Teórica de Funciones

Durante el viaje del Titanic se implementaron diversas funciones para gestionar operaciones críticas, como la navegación, la administración de pasajeros y la coordinación de emergencias.  
**Pregunta:**  
Desde una perspectiva teórica, explica en detalle qué es una función en programación. En tu respuesta, aborda los siguientes puntos:

- **Definición y Propósito:** Describe la estructura general de una función (definición, parámetros, valor de retorno) y cuál es su utilidad en el desarrollo de software.  
- **Paso de Parámetros:** Explica cómo se manejan los parámetros (por valor y por referencia) y las implicaciones de cada método en términos de rendimiento y seguridad.  
- **Problemas Comunes:** Menciona y explica al menos dos problemas comunes que pueden surgir en la implementación de funciones (por ejemplo, recursión infinita o manejo inadecuado de excepciones) y cómo podrían abordarse en un entorno real.
---

### Ejercicio 2: Estructuras de Datos Recursivas

Imagina que las rutas de emergencia y las conexiones entre los distintos compartimentos del Titanic se pueden representar mediante un grafo.  
**Pregunta:**  
Define qué es un grafo y describe dos representaciones posibles (por ejemplo, lista de adyacencia y matriz de adyacencia). ¿En qué casos es preferible usar listas de adyacencia en lugar de matrices de adyacencia?

---

### Ejercicio 3: Análisis de Algoritmos

En una situación de emergencia, los ingenieros del Titanic implementan un algoritmo para ubicar rápidamente las cabinas disponibles.  
**Pregunta:**  
Explica qué es la notación O() y cómo se utiliza para determinar el mejor, peor y caso promedio de un algoritmo de búsqueda en un arreglo desordenado.

---

### Ejercicio 4: Problemas NP

Ante una crisis, el capitán del Titanic debe determinar la ruta de evacuación óptima hacia los botes salvavidas.  
**Pregunta:**  
Discute la diferencia entre problemas que pueden resolverse en tiempo polinómico y aquellos que son NP-completos, ejemplificando con el algoritmo de Dijkstra para encontrar la ruta más corta en un grafo ponderado. Argumenta por qué, en un escenario real, la elección del algoritmo adecuado es crucial para la toma de decisiones en tiempo crítico.

---

### Ejercicio 5: Árboles Binarios

El proceso de decisión en el Titanic para elegir entre evacuar por la cubierta principal o dirigirse a una bodega de emergencia puede representarse mediante un árbol binario.  
**Instrucciones:**  
Implementa en Python un árbol con los siguientes nodos:
- **"Inicio"**
- **"Cubierta Principal"**
- **"Bodega de Emergencia"**

Realiza un recorrido **InOrden** del árbol e imprime los nodos visitados.

---

### Ejercicio 6: Heap Binaria y Cola de Prioridades

La tripulación del Titanic utiliza una cola de prioridades para gestionar tareas críticas en situaciones de emergencia.  
**Instrucciones:**  
Implementa en Python una estructura de Heap Binaria que permita gestionar eventos (tareas) según su importancia (prioridad). Asegúrate de incluir las operaciones de inserción y extracción del máximo.

---

### Ejercicio 7: Algoritmos de Recorrido (BFS)

Diseña una función en Python para realizar un recorrido **BFS** en un grafo que representa la red de pasillos y compartimentos del Titanic.  
Utiliza el siguiente conjunto de datos para el grafo:

- **Nodos:** `[A, B, C, D, E]`  
- **Aristas:** `[(A, B), (A, C), (B, D), (C, E), (D, E)]`

---

### Ejercicio 8: Ordenamiento Topológico

El capitán del Titanic necesita organizar las secuencias de tareas y prioridades de evacuación para garantizar una salida ordenada.  
**Instrucciones:**  
Implementa en Python un algoritmo de ordenamiento topológico para el siguiente grafo dirigido:

- **Nodos:** `[A, B, C, D, E]`  
- **Aristas:** `[(A, B), (A, C), (B, D), (C, D), (D, E)]`

---

### Ejercicio 9: Heap Binario para Planificación

El oficial de a bordo del Titanic utiliza un montículo binario (heap mínimo) para gestionar las tareas de emergencia en tiempo real.  
**Instrucciones:**  
Implementa en Python un heap mínimo con soporte para operaciones de inserción, extracción del mínimo y disminución de clave. Prueba tu implementación con la siguiente lista de tareas y prioridades:

```python
[("Tarea A", 5), ("Tarea B", 3), ("Tarea C", 8), ("Tarea D", 1)]
```

---

### Ejercicio 10: Ruta Mínima en Grafos

En una situación de evacuación, el capitán del Titanic necesita encontrar la ruta más corta hacia un bote salvavidas en un grafo ponderado que representa los pasillos y escaleras del barco.  
**Instrucciones:**  
Implementa el algoritmo de Dijkstra en Python y aplícalo al siguiente grafo:

- **Nodos:** `[1, 2, 3, 4, 5]`  
- **Aristas y pesos:** `[(1, 2, 2), (1, 3, 4), (2, 3, 1), (2, 4, 7), (3, 5, 3), (4, 5, 1)]`

---

### Ejercicio 11: Teoría – Reflexión Personal sobre el Proyecto del Segundo Parcial y Aplicación de Estructuras de Datos

Durante el segundo parcial se desarrolló un proyecto extenso que requirió de un desarrollo largo y complejo, en el cual tuviste la oportunidad de aplicar diversas estructuras de datos para resolver problemas reales.
**Pregunta:**
Relata de forma detallada tu experiencia en el desarrollo del proyecto del segundo parcial. En tu respuesta, responde lo siguiente:

    Aplicación de Estructuras: Describe al menos tres estructuras de datos que implementaste (por ejemplo: pilas, colas, listas enlazadas, árboles, grafos, etc.) y explica cómo cada una ayudó a resolver desafíos específicos del proyecto.
    Análisis Crítico: Analiza las ventajas y desventajas de las estructuras seleccionadas, considerando aspectos como eficiencia, complejidad y aplicabilidad en el contexto del proyecto.
    Reflexión Personal: Relaciona tu experiencia personal durante el proyecto. Explica qué aprendizajes obtuviste, cómo enfrentaste los desafíos y de qué manera esta experiencia influyó en tu comprensión y elección de estructuras de datos en situaciones reales.

---

**Instrucciones Finales:**

- Revisa cuidadosamente cada ejercicio antes de entregar tu examen.  
- Asegúrate de que tus respuestas sean claras, bien fundamentadas y estén correctamente documentadas (en caso de código, incluye comentarios explicativos).  
- ¡Buena suerte en esta travesía, y recuerda que, al igual que en el Titanic, la planificación y el orden pueden marcar la diferencia!

---
