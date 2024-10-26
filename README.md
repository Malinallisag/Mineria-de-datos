# Proyecto de Minería de Datos: Clasificación Socioeconómica de la Población en México (2019 - 2023)

Este proyecto utiliza datos de la Encuesta Nacional sobre Disponibilidad y Uso de Tecnologías de la Información en los Hogares (DUTIH) del INEGI para clasificar a la población en categorías socioeconómicas (baja, media y alta) en México y explorar modelos de predicción para entender la dinámica de estos niveles en distintos periodos entre 2019 y 2023.

**Ejemplo de formato de datos**: Este proyecto sigue una estructura similar a la de otros datasets como el [dataset Iris en UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/53/iris), adaptado a las variables específicas de los datos del INEGI.

## Descripción del Proyecto

El propósito de este proyecto es clasificar a la población en diferentes niveles socioeconómicos (bajo, medio y alto) en función de factores como el acceso a dispositivos tecnológicos, la disponibilidad de internet y el tamaño de la localidad. Además, se implementarán modelos predictivos para observar las tendencias y posibles cambios en estos niveles en los próximos años.

## Datos Utilizados

- **Fuente**: [INEGI - DUTIH 2019](https://www.inegi.org.mx/programas/dutih/2019/#datos_abiertos) hasta [INEGI - DUTIH 2023](https://www.inegi.org.mx/programas/dutih/2023/#datos_abiertos)
- **Variables Clave**:
  - **Entidad**: Estado donde se recolectaron los datos
  - **Selección de Vivienda**: Identificador de la vivienda
  - **Tamaño de Localidad**: Clasificación según la población del área
  - **Total de Personas**: Número de personas en el hogar
  - **Disponibilidad de PC, Celular e Internet**: Indicadores de acceso a tecnologías en cada hogar
  - **Edad**: Indicar las edades de la poblacion
  - **Sexo**: Indica la diferencia entre hombres y mujeres en el uso de TIC's
  - Los datos se han filtrado para centrarse en estas variables, que serán la base para clasificar el nivel socioeconómico de los hogares.

## Objetivos

1. **Clasificación Socioeconómica**: Determinar el nivel socioeconómico de los hogares utilizando técnicas de clasificación en minería de datos.
2. **Predicción de Niveles Socioeconómicos**: Implementar modelos predictivos (KNN, regresión lineal y otros) para predecir cambios en los niveles socioeconómicos y observar posibles patrones a lo largo del tiempo.
3. **Análisis de Resultados**: Comparar y analizar las predicciones de los modelos para encontrar las tendencias más comunes y entender factores clave de cambio en el nivel socioeconómico.

## Requerimientos

- Python 3.x
- Bibliotecas: `pandas`, `numpy`, `scikit-learn`, `matplotlib` (para el análisis y visualización de datos)
