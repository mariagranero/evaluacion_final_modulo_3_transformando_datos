# ✈️ Evaluación Final — Customer Loyalty Program Analysis

Este repositorio contiene la resolución del **ejercicio de evaluación final** del módulo de análisis de datos.
El objetivo principal del proyecto es explorar, limpiar y analizar datos de un programa de fidelización de una aerolínea, utilizando técnicas de **Pandas, estadística descriptiva y visualización de datos**.

---

## 📌 Objetivo del Proyecto

El propósito de este análisis es comprender el comportamiento de los clientes dentro de un programa de lealtad aérea, estudiando aspectos como:

* Número de vuelos reservados
* Distancia recorrida
* Puntos acumulados y redimidos
* Perfil sociodemográfico de los clientes
* Diferencias en reservas según el nivel educativo

Este proyecto simula un caso real de análisis de datos aplicado a un entorno empresarial.

---

## 📂 Datos Utilizados

El análisis se basa en dos conjuntos de datos que se complementan:

### 1. **Customer Flight Activity.csv**

Contiene información mensual sobre la actividad de vuelo de los clientes.

Algunas variables relevantes:

* **Flights Booked**: vuelos reservados en el mes
* **Distance**: distancia total volada
* **Points Accumulated**: puntos acumulados
* **Points Redeemed**: puntos redimidos
* **Dollar Cost Points Redeemed**: coste en dólares de los puntos utilizados

---

### 2. **Customer Loyalty History.csv**

Incluye el perfil del cliente y características de su membresía.

Variables destacadas:

* **Gender**: género
* **Education**: nivel educativo
* **Salary**: salario anual estimado
* **Marital Status**: estado civil
* **Loyalty Card**: tipo de tarjeta
* **CLV**: valor de vida del cliente

---

## 🧩 Fases del Ejercicio

El proyecto está estructurado en varias fases:

### **Fase 1: Exploración y Limpieza**

* Revisión inicial de los datasets
* Identificación de valores nulos o inconsistencias
* Unión eficiente de los dos conjuntos de datos mediante `Loyalty Number`
* Tratamiento de datos faltantes y conversión de tipos

---

### **Fase 2: Análisis Estadístico**

* Estadísticas descriptivas (media, mediana, desviación estándar…)
* Detección de valores atípicos
* Correlaciones entre variables numéricas
* Distribución de variables categóricas

Cada resultado incluye una breve interpretación en lenguaje natural.

---

### **Fase 3: Visualización de Datos**

Se utilizan gráficos con **Matplotlib y Seaborn** para responder preguntas como:

* Distribución de vuelos reservados por mes
* Relación entre distancia y puntos acumulados
* Distribución geográfica de clientes por provincia
* Comparación salarial según nivel educativo
* Proporción de tipos de tarjetas de fidelidad
* Distribución de clientes por estado civil y género

---

### **Fase 4: Diferencias en Reservas según Educación**

Se evalúa si existen diferencias significativas en el número de vuelos reservados dependiendo del nivel educativo del cliente.

Pasos realizados:

* Selección de columnas relevantes (`Flights Booked`, `Education`)
* Agrupación por nivel educativo
* Cálculo de estadísticas descriptivas por grupo

---

## 🛠️ Herramientas Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## ✅ Buenas Prácticas

Durante el desarrollo se aplican:

* Código limpio y comentado
* Commits descriptivos en Git
* Interpretación analítica junto a resultados numéricos

---

## 👩‍💻 Autora

Ejercicio realizado de forma individual como parte del proceso de evaluación del módulo.
* **María Granero**
  * [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mar%C3%ADa-granero-l%C3%B3pez/)
  * [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/mariagranero)

