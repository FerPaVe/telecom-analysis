# Análisis de una empresa de telecomunicaciones (ConnectaTel)

📌 Descripción general

Este proyecto analiza el comportamiento de uso de los servicios móviles (llamadas y mensajes) de los clientes de ConnectaTel, una empresa de telecomunicaciones con operaciones en México y Colombia. El objetivo es comprender patrones de consumo, detectar comportamientos atípicos y segmentar clientes para generar insights accionables que apoyen la toma de decisiones comerciales.

🎯 Objetivos del proyecto

Integrar y analizar múltiples fuentes de datos relacionadas con clientes, planes y uso real.

Identificar y corregir problemas de calidad de datos.

Analizar patrones de uso de llamadas y mensajes.

Detectar outliers y comportamientos extremos.

Segmentar clientes por edad y nivel de uso.

Proponer recomendaciones comerciales basadas en datos.

🗂️ Datasets utilizados

plans.csv: Catálogo de planes móviles (precio, beneficios incluidos y costos por excedentes).

users_latam.csv: Información de clientes (edad, ciudad, plan contratado, fecha de registro, churn).

usage.csv: Detalle de uso real del servicio (llamadas, mensajes, duración y longitud).

🛠️ Herramientas y tecnologías

Python

Jupyter Notebook

pandas

numpy

seaborn

matplotlib

🔄 Flujo de trabajo

Carga y exploración de datos
Revisión inicial de estructura, tipos de datos y dimensiones de los datasets.

Calidad y limpieza de datos

Tratamiento de valores nulos.

Corrección de valores sentinela (ej. -999).

Normalización de variables categóricas.

Conversión y validación de fechas.

Análisis descriptivo
Estadísticas básicas para entender el comportamiento general de los usuarios.

Construcción de métricas por usuario
Agregación de mensajes, llamadas y minutos totales por cliente.

Visualización y detección de outliers
Uso de histogramas y boxplots para identificar patrones y valores extremos.

Segmentación de clientes

Segmentación por edad (jóvenes, adultos, adultos mayores).

Segmentación por nivel de uso (bajo, medio y alto uso).

Insights ejecutivos y recomendaciones
Traducción de hallazgos técnicos a conclusiones accionables para el negocio.

📊 Principales hallazgos

Existen diferencias claras de uso según la edad del cliente.

Los usuarios de alto consumo (heavy users) concentran gran parte del uso total.

Los outliers detectados representan comportamientos reales, no errores de datos.

El nivel de uso y el tipo de plan están estrechamente relacionados.

💡 Recomendaciones de negocio

Diseñar planes específicos para usuarios de alto consumo.

Implementar estrategias de upselling para usuarios de uso medio.

Crear planes enfocados en mensajería para usuarios jóvenes.

Ofrecer planes simples y enfocados en llamadas para adultos mayores.
