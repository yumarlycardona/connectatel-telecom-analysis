# Análisis de clientes de ConnectaTel

## Descripción del proyecto

Este proyecto analiza los datos de clientes de ConnectaTel con el propósito de identificar patrones de uso de los servicios de telecomunicaciones, reconocer segmentos de clientes y detectar oportunidades para mejorar la oferta comercial.

El análisis se desarrolló utilizando Python y herramientas de análisis y visualización de datos en Jupyter Notebook.

## Objetivos

- Explorar y comprender los datos disponibles.
- Identificar y tratar problemas de calidad de los datos.
- Analizar patrones de consumo de llamadas y mensajes.
- Segmentar a los clientes por edad y nivel de uso.
- Identificar valores atípicos en las variables de consumo.
- Formular recomendaciones comerciales basadas en los resultados obtenidos.

## Datos utilizados

El proyecto utiliza dos conjuntos de datos principales:

- **Usuarios (`users`):** contiene información de los clientes, como edad, ciudad, fecha de registro y plan.
- **Registros de uso (`usage`):** contiene información sobre el consumo de llamadas y mensajes, según las variables disponibles.

Ambos conjuntos se integraron para consolidar la información de consumo por cliente y realizar los análisis correspondientes.

## Etapas del análisis

1. **Exploración de los datos:** revisión de la estructura, las columnas y los tipos de datos.
2. **Calidad y limpieza:** identificación y tratamiento de valores faltantes, datos inválidos y fechas que requerían validación.
3. **Preparación de los datos:** organización y consolidación de la información de usuarios y consumo.
4. **Análisis exploratorio:** revisión de la distribución de las variables relevantes.
5. **Detección de valores atípicos:** análisis de patrones extremos en mensajes, llamadas y minutos de llamada mediante el rango intercuartílico (IQR).
6. **Segmentación de clientes:** clasificación por grupos de edad y niveles de uso.
7. **Análisis ejecutivo:** interpretación de los hallazgos y formulación de recomendaciones comerciales.

## Principales hallazgos

- El grupo de uso medio concentra **2.943 clientes (73,58 %)** de los 4.000 usuarios analizados.
- Los adultos representan el **50,45 %** de la base, seguidos por los adultos mayores (**30,55 %**) y los jóvenes (**19,00 %**).
- Se identificaron valores atípicos en las tres variables de consumo evaluadas: 46 en mensajes, 30 en llamadas y 109 en minutos de llamada.
- Los resultados permiten identificar oportunidades para evaluar la adecuación de los planes a las necesidades de los distintos segmentos.

Estos hallazgos describen la distribución y los patrones observados; no demuestran por sí solos la rentabilidad de cada segmento.

## Herramientas utilizadas

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Cómo ejecutar el proyecto

1. Descarga el archivo `connectatel_analysis.ipynb` desde este repositorio.
2. Abre [Google Colab](https://colab.research.google.com/) o un entorno Jupyter Notebook.
3. Carga el archivo del notebook.
4. Verifica que los archivos de datos originales estén disponibles en las rutas utilizadas por el código.
5. Ejecuta las celdas en orden, desde el inicio hasta el análisis ejecutivo.

**Nota:** para reproducir el análisis es necesario disponer de los archivos de datos originales utilizados por el notebook. Estos deben incorporarse al entorno de ejecución respetando las condiciones de uso y evitando publicar información sensible.

## Estructura del repositorio

- `connectatel_analysis.ipynb`: notebook con el desarrollo del análisis, la limpieza, la segmentación y las conclusiones.
- `README.md`: documentación del proyecto, sus objetivos, etapas y guía de ejecución.

## Conclusión

Este proyecto aplica técnicas de análisis exploratorio, limpieza y segmentación para transformar datos de uso de telecomunicaciones en hallazgos que pueden orientar la evaluación de los planes de ConnectaTel. También destaca la importancia de validar la calidad de los datos antes de tomar decisiones comerciales.
