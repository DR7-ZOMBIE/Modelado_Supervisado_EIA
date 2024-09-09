# 📊 Taller de Clasificación - Caso 6

**Asignatura:** Computación Científica  
**Semestre:** 2024 - II  

---

## 🎯 Objetivo

El objetivo de este proyecto es implementar la metodología **ASUM-DM** (Analytics Solutions Unified Method for Data Mining) para diseñar modelos de clasificación. Se abordará un caso práctico de negocio enfocado en los préstamos P2P, donde se buscará predecir si un usuario incumplirá con el pago de su préstamo.

---

## 📝 Descripción del Problema

En los préstamos en línea **P2P**, los prestatarios pueden completar un formulario en línea y obtener la aprobación sin una entrevista presencial. La información proporcionada por el prestatario puede estar distorsionada, lo que aumenta el riesgo para las empresas P2P. El desafío es construir un modelo de clasificación que prediga si un usuario incumplirá su préstamo.

**Datos proporcionados:**

- Se tiene acceso a un conjunto de datos (`datos_caso_6.csv`) con múltiples variables que describen a los prestatarios y sus préstamos.
- El modelo debe predecir la variable objetivo `loan_status` (estado de la deuda).

---

## 📊 Conjunto de Datos

El conjunto de datos contiene las siguientes variables:

| **Variable**           | **Descripción**                        |
|------------------------|----------------------------------------|
| `loan_status`          | Estado de la deuda (Variable Objetivo)  |
| `annual_inc`           | Ingresos anuales                       |
| `verification_status`  | Validación del historial crediticio     |
| `emp_length`           | Tiempo laborado                        |
| `home_ownership`       | Tipo de vivienda                       |
| `int_rate`             | Tasa de interés                        |
| `loan_amnt`            | Monto del crédito                      |
| `purpose`              | Propósito del crédito                  |
| `term`                 | Duración del crédito                   |
| `grade`                | Calificación de riesgo                 |

---

## 🚀 Metodología ASUM-DM

La metodología **ASUM-DM** es un marco de trabajo para soluciones de minería de datos, basado en CRISP-DM, que sigue las siguientes fases:

1. **Entendimiento del negocio**: Comprender el problema a resolver, en este caso, la predicción de incumplimientos en préstamos P2P.
2. **Entendimiento de los datos**: Realizar una exploración profunda de los datos proporcionados, entendiendo las variables y sus relaciones.
3. **Preparación de los datos**: Limpiar y transformar los datos para hacerlos adecuados para el modelado.
4. **Modelado**: Aplicar modelos de clasificación, tales como regresión logística, árboles de decisión o bosques aleatorios.
5. **Evaluación**: Medir el rendimiento de los modelos usando métricas como precisión, recall, F1-score, entre otras.
6. **Despliegue**: (Opcional) Desplegar el modelo en un entorno de producción.

---

## 🛠️ Tecnologías Utilizadas

El proyecto ha sido desarrollado utilizando las siguientes herramientas y bibliotecas:

- **Lenguaje**: Python 🐍
- **Análisis de Datos**: Pandas, NumPy
- **Modelado**: Scikit-learn
- **Visualización**: Matplotlib, Seaborn
- **Preparación de datos**: Scikit-learn (StandardScaler, OneHotEncoder)

---

## 📈 Proceso de Modelado

### 1. **Exploración de Datos**
   - Distribución de las variables.
   - Identificación de valores atípicos.
   - Análisis de correlaciones.

### 2. **Preparación de Datos**
   - Imputación de valores nulos.
   - Codificación de variables categóricas.
   - Escalamiento de variables numéricas.

### 3. **Modelos de Clasificación**
   - **Regresión Logística**
   - **Árboles de Decisión**
   - **Random Forest**
   - **Gradient Boosting**

### 4. **Evaluación**
   - Matriz de confusión.
   - Curva ROC y AUC.
   - Precisión, Recall, F1-Score.

---

## 📅 Entregables

- Un **notebook en Python** detallando todo el proceso de análisis y modelado.
- Una **presentación de 10 minutos** donde se explica la metodología y los resultados obtenidos.

---

## 📅 Fecha de Entrega

- **Mayo 3 de 2024**

---

## 📧 Contacto

Para cualquier consulta o sugerencia, no dudes en contactarme a través de este repositorio o vía correo electrónico.

---

© 2024 - Dennis Juilland - Computación Científica
