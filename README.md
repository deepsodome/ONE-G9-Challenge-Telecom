<h1 align="center">📊 Análisis de Evasión de Clientes — Telecom X</h1>

![Python](https://img.shields.io/badge/Python-3.12.12-blue?logo=python)
![Status](https://img.shields.io/badge/Estado-Finalizado-success)

---

## 📋 Tabla de contenidos
1. [📖 Descripción](#-descripción)
2. [🎯 Objetivo del proyecto](#-objetivo-del-proyecto)
3. [🏁 Estado del proyecto](#-estado-del-proyecto)
4. [⚙️ Desarrollo del proyecto](#️-desarrollo-del-proyecto)
5. [📌 Resultados destacados](#-resultados-destacados)
6. [✅ Tecnologías utilizadas](#-tecnologías-utilizadas)
7. [👤 Autor](#-autor)

---

## 📖 Descripción
Telecom X enfrenta una alta tasa de cancelación de clientes, por lo que resulta necesario comprender los factores que influyen en la pérdida de clientes. En este proyecto se recopilan, procesan, transforman y analizan los datos utilizando **Python** y sus principales bibliotecas, con el objetivo de extraer información relevante.

Los resultados de este análisis sirven como base para el desarrollo de **modelos predictivos** y para la definición de **estrategias de retención**, orientadas a reducir la evasión de clientes.

---

## 🎯 Objetivo del proyecto
Identificar los principales factores asociados al abandono de clientes en Telecom X mediante un análisis exploratorio de datos, con el fin de generar **insights accionables** que permitan diseñar estrategias de retención y sentar las bases para futuros **modelos predictivos de churn**.

---

## 🏁 Estado del proyecto
🏁 **Proyecto finalizado** 🏁

---

## ⚙️ Desarrollo del proyecto

### 1. Recolección y preparación de datos
Se importaron las librerías necesarias para el análisis y la base de datos de la empresa, proveniente de un archivo **JSON**. Posteriormente, se normalizaron las columnas que contenían diccionarios y se ajustaron los tipos de datos.

Además, se trataron y eliminaron valores nulos, se renombraron columnas y se estandarizaron las variables de naturaleza binaria. Estas tareas permitieron mejorar la calidad, consistencia y legibilidad de los datos, facilitando su posterior análisis.

### 2. Análisis exploratorio de datos (EDA)
Se aplicaron distintos métodos para analizar la distribución de las variables y se calcularon y visualizaron las tasas de abandono bajo diferentes supuestos. Asimismo, se realizaron comparaciones entre variables mediante tablas resumen.
![image alt](https://github.com/JonathanMarino/Challenge-Telecom-X/blob/8de1f2c650e1e052e4032e07cc387410bad0fe12/images/tasas_abandono_cat.png)

![image alt](https://github.com/JonathanMarino/Challenge-Telecom-X/blob/8de1f2c650e1e052e4032e07cc387410bad0fe12/images/boxplots_var_num.png)

Se utilizó un **mapa de calor** para visualizar las correlaciones entre la variable *Abandono* y el resto de las variables numéricas y binarias. Además, se determinó el perfil de los clientes que continúan y de aquellos que abandonan la empresa a partir del análisis de sus preferencias, meses de permanencia y gasto acumulado.

![image alt](https://github.com/JonathanMarino/Challenge-Telecom-X/blob/8de1f2c650e1e052e4032e07cc387410bad0fe12/images/correlacion_variables.png)

Por último, mediante **gráficos de líneas**, se presentó la evolución de variables clave en función de los meses de permanencia de los clientes.
![image alt](https://github.com/JonathanMarino/Challenge-Telecom-X/blob/8de1f2c650e1e052e4032e07cc387410bad0fe12/images/evo_cargo_mensual.png)

### 3. Conclusiones e insights
En esta sección se presentan las principales conclusiones derivadas del análisis de las variables categóricas, los servicios contratados, el tiempo de permanencia y los cargos asociados a los clientes. A partir de estos análisis, se identificaron patrones claros de comportamiento y se definieron los perfiles del **cliente que abandona** y del **cliente que continúa** en la empresa.

Los insights obtenidos permiten comprender los factores que más influyen en la cancelación del servicio y sirven como base para la toma de decisiones estratégicas orientadas a la **retención de clientes**.

### 4. Recomendaciones
A partir de los insights obtenidos, se proponen acciones orientadas a **reducir la tasa de abandono** y **fortalecer la relación con los clientes**, con foco en las etapas tempranas del vínculo comercial.

Las principales líneas de acción recomendadas son:
- Implementar estrategias de **retención temprana**, priorizando clientes con contratos flexibles y servicios de alta exigencia como la fibra óptica.
- Incentivar la migración hacia **contratos de mayor duración**, generando barreras de salida amigables.
- Promover la contratación de **servicios complementarios** (soporte técnico, seguridad en línea) como factores de retención.
- Fomentar el uso de **medios de pago automatizados** para aumentar el compromiso del cliente.
- Orientar las estrategias comerciales hacia la **calidad del servicio y el valor agregado**, más que hacia la cantidad de servicios contratados.

Estas recomendaciones sientan las bases para el desarrollo de **modelos predictivos de abandono** y para la definición de **estrategias de retención basadas en datos**.

---

## 📌 Resultados destacados
- El abandono de clientes se concentra principalmente en los **primeros meses de permanencia**.
- Los contratos **mes a mes** presentan tasas de abandono significativamente más altas.
- La **fibra óptica** se identifica como un segmento de alto riesgo cuando no está acompañada de servicios de soporte.
- Los **medios de pago no automatizados** están asociados a una mayor probabilidad de evasión.
- Los servicios complementarios actúan como **barreras de salida** y mejoran la retención.

---

## ✅ Tecnologías utilizadas

### 💬 Lenguaje
- **Python**

### 📚 Librerías principales
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

### 🧩 Entorno de desarrollo
- **Google Colab**

---
 
