# Challenge_Telecom-X

# Análisis de Evasión de Clientes (Churn) – Telecom X

## Descripción del Proyecto

Este proyecto forma parte de un análisis de datos realizado para Telecom X, una empresa del sector de telecomunicaciones que enfrenta una alta tasa de cancelación de clientes (Churn).

El objetivo principal del análisis es identificar los factores que influyen en la evasión de clientes, utilizando técnicas de limpieza de datos, análisis exploratorio y visualización. A partir de estos resultados, es posible comprender mejor el comportamiento de los usuarios y generar **insights que ayuden a mejorar la retención de clientes**.

Durante el desarrollo del proyecto se analizaron variables como:

* Tipo de contrato
* Servicios contratados
* Antigüedad del cliente
* Método de pago
* Cargos mensuales y totales

Los resultados obtenidos permiten detectar patrones que ayudan a explicar por qué algunos clientes cancelan el servicio, lo cual puede apoyar a la empresa en la toma de decisiones estratégicas.

# Propósito del Análisis

El propósito de este proyecto es analizar el fenómeno de evasión de clientes (Churn) dentro de Telecom X y detectar los factores que están asociados a este comportamiento.

En particular, el análisis busca responder preguntas como:

* ¿Qué tipo de clientes tienen mayor probabilidad de cancelar el servicio?
* ¿Existe relación entre el tipo de contrato y la evasión?
* ¿Influyen los métodos de pago en la cancelación?
* ¿Los clientes nuevos cancelan más que los antiguos?

A través de un análisis exploratorio de datos (EDA) se identifican patrones que pueden ayudar a la empresa a:

* Mejorar la experiencia del cliente
* Reducir la tasa de cancelaciones
* Diseñar estrategias de fidelización más efectivas


# Estructura del Proyecto

El proyecto está organizado de manera que sea fácil de entender y reproducir. La estructura principal es la siguiente:

```
TelecomX-Churn-Analysis
│
├── Solucion_final_Telecom_X_Latam.ipynb
│
├── data
│   └── TelecomX_Data.json
│
├── README.md

```

### Descripción de los archivos

**Solucion_final_Telecom_X_Latam.ipynb**

Notebook principal del proyecto donde se desarrolla todo el análisis. Incluye:

* Importación de datos
* Limpieza y transformación del dataset
* Análisis exploratorio
* Visualización de resultados

**data/**

Contiene el conjunto de datos utilizado para el análisis.

**README.md**

Documento que explica el propósito del proyecto, su estructura y cómo ejecutarlo.

# Ejemplos de Gráficos e Insights

Durante el análisis se generaron diversas visualizaciones que permiten identificar patrones relacionados con la evasión de clientes.

Algunos de los insights más relevantes incluyen:

### Distribución de clientes que cancelan el servicio

Uno de los primeros análisis consistió en observar la proporción de clientes que permanecen en la empresa frente a aquellos que cancelan el servicio. Este gráfico permite dimensionar la magnitud del problema de churn.

### Relación entre tipo de contrato y evasión

Los resultados muestran que los clientes con contratos mensuales presentan una mayor probabilidad de cancelar el servicio en comparación con aquellos que tienen contratos anuales o de dos años.

Este hallazgo sugiere que los contratos de mayor duración ayudan a reducir la tasa de evasión.


### Antigüedad del cliente

Se observó que los clientes con menor tiempo en la empresa tienen mayor probabilidad de cancelar, mientras que los clientes con mayor antigüedad tienden a permanecer.

Esto indica que los primeros meses del servicio son críticos para la retención.

### Métodos de pago

El análisis también reveló que ciertos métodos de pago, como el cheque electrónico, presentan una mayor proporción de cancelaciones en comparación con métodos automáticos.

Esto podría indicar fricciones en el proceso de pago o menor compromiso del cliente con el servicio.

# Conclusión

Este proyecto demuestra cómo el análisis de datos puede ayudar a comprender mejor el comportamiento de los clientes y detectar factores asociados a la evasión. A través de la exploración y visualización de los datos, es posible generar insights valiosos que pueden apoyar la toma de decisiones dentro de una empresa.
El análisis realizado proporciona una base para futuras mejoras, como el desarrollo de **modelos predictivos de churn** que permitan anticipar la cancelación de clientes y diseñar estrategias de retención más efectivas.

