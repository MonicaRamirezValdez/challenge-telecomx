#  Análisis de Churn - TelecomX

##  Descripción del Proyecto

Este proyecto forma parte del Challenge de Ciencia de Datos de TelecomX.

El objetivo principal es analizar el comportamiento de los clientes y detectar los factores que influyen en la cancelación del servicio (*Churn*).

Se trabajó con un dataset en formato JSON que contiene información demográfica, servicios contratados y datos de facturación.

---

##  Objetivos

-  Limpiar y transformar los datos  
-  Convertir variables al formato adecuado  
-  Analizar la variable objetivo **Churn**  
-  Identificar patrones asociados a la evasión de clientes  
-  Preparar los datos para futuros modelos predictivos  

---

##  Dataset

Fuente del dataset:

- Challenge de Ciencia de Datos - Alura LATAM  
- Archivo utilizado: `TelecomX_Data.json`

---

##  Procesamiento de Datos

Durante el análisis se realizaron los siguientes pasos:

- Normalización de columnas anidadas (customer, phone, internet, account)
- Conversión de `Charges.Total` a formato numérico
- Tratamiento de valores nulos
- Codificación de variables categóricas (One Hot Encoding)
- Creación de variables derivadas

---

## Análisis Exploratorio

Se analizaron variables como:

- Tipo de contrato
- Método de pago
- Cargos mensuales
- Facturación sin papel
- Servicios adicionales contratados

### Principales hallazgos

- Los contratos mensuales presentan mayor tasa de churn.
- Clientes con facturación electrónica tienden a cancelar más.
- Cargos mensuales más altos están asociados a mayor probabilidad de evasión.

---

## Tecnologías Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## Próximos Pasos

- Implementar modelos de Machine Learning
- Evaluar métricas 
- Interpretar importancia de variables
- Generar recomendaciones estratégicas para el negocio

---

## Autora

Monica Ramirez  
Proyecto desarrollado como parte del Challenge de Ciencia de Datos 2026.
