# Análisis de Churn en TelecomX

## Contexto
Este proyecto analiza el fenómeno de *churn* (abandono de clientes) en una empresa de telecomunicaciones con el objetivo de identificar los principales factores asociados a la pérdida de clientes y aportar información útil para el diseño de estrategias de retención.

El análisis se realiza a partir del dataset `TelecomX_Data.json`, que contiene información demográfica, contractual y de facturación de los clientes.

---

## Pregunta de análisis
**¿Qué características de los clientes y de los servicios contratados están más asociadas a una mayor probabilidad de churn?**

---

## Enfoque del análisis
El proyecto se estructura en las siguientes etapas:

- Extracción y carga de datos desde un archivo JSON
- Limpieza y transformación de los datos (ETL)
- Análisis exploratorio de datos (EDA)
- Análisis del churn en función de variables categóricas y numéricas
- Elaboración de un informe final con conclusiones y recomendaciones estratégicas

---

## Síntesis de resultados
El análisis muestra que el churn no se distribuye de manera uniforme entre los clientes, sino que está fuertemente asociado a:

- El tipo de contrato y la duración de la relación con la empresa
- La ausencia de servicios adicionales de soporte y seguridad
- Determinadas características demográficas
- Variables vinculadas a la facturación y métodos de pago

Estos patrones permiten identificar segmentos de clientes con mayor riesgo de abandono.

---

## Recomendaciones
A partir de los resultados obtenidos, se proponen líneas de acción orientadas a:

- Incentivar la migración hacia contratos de mayor duración
- Fortalecer la propuesta de valor de los servicios de soporte y seguridad
- Diseñar estrategias de retención focalizadas en segmentos de alto riesgo
- Implementar mecanismos de monitoreo temprano del churn

---

## Contenido del repositorio
- `TelecomX_LATAM.ipynb`: notebook con el análisis completo, visualizaciones y conclusiones.
