# sprint7-final-project
Proyecto Triple Ten - Análisis de una empresa de telecomunicaciones

Objetivo del Proyecto
Este proyecto tiene como objetivo realizar un Análisis Exploratorio de Datos (EDA) para la compañía de telecomunicaciones ConnectaTel. Se busca comprender los patrones de comportamiento de los usuarios en dos planes distintos (Básico y Premium), identificar segmentos de clientes de alto valor y proponer estrategias de negocio basadas en datos para optimizar la retención y la oferta de planes.

Datasets Utilizados
El análisis se basa en los siguientes archivos CSV:
users.csv: Información demográfica (edad, ciudad, fecha de registro).
calls.csv: Registros detallados de llamadas (duración, fecha).
messages.csv: Registro de uso de mensajería.
internet.csv: Uso de datos móviles.
plans.csv: Descripción y tarifas de los planes disponibles.

Etapas del Análisis
El flujo de trabajo se dividió en las siguientes fases técnicas:
1. Cargar y explorar: Importación de los datasets y visión inicial de la estructura y variables del negocio.
2. Identificación de problemas de calidad: Auditoría de los datos para detectar valores nulos, duplicados o inconsistencias temporales y geográficas.
3. Limpieza básica: Tratamiento de datos faltantes, reclasificación de categorías y exclusión de registros fuera de rango para asegurar la integridad.
4. Summary statistics: Cálculo de métricas descriptivas para comprender la tendencia central y la dispersión del comportamiento de consumo.
5. Visualización & outliers: Generación de gráficos y análisis estadístico para identificar patrones de uso y perfilar a los usuarios extremos.
6. Segmentación: Clasificación de la base de clientes en grupos de uso y edad para identificar necesidades diferenciadas.
7. Insight ejecutivo: Síntesis de los hallazgos clave y formulación de recomendaciones estratégicas para la optimización de los planes.
8. Publicación: Documentación y despliegue del proyecto en un repositorio para asegurar la trazabilidad y comunicación de los resultados.

Cómo ejecutar el Notebook
El proyecto ha sido desarrollado en Python utilizando Jupyter Notebook.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1oWkRxHzSZSWWx8hlnNJCqEZ_YYjwX4vX#scrollTo=05e15812)

Puedes ejecutar el análisis directamente en tu navegador haciendo clic en el botón de arriba.

Guía de Reproducción
Es crucial ejecutar en orden ascenden el proyecto, sobre todo es crucial ejecutar las celdas de limpieza de datos antes de realizar cualquier gráfico o cálculo de segmentos, ya que el análisis de outliers y grupos depende de la integridad de los datos limpios.
