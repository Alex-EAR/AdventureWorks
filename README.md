# **Proyecto de Análisis de Datos con Power BI: AdventureWorksDW2019**
## **Descripción del Proyecto 📊**
Este proyecto tiene como objetivo analizar datos de la base de datos AdventureWorksDW2019 con un enfoque en los clientes, ingresos, costos y rentabilidad. Utilizando Power BI, se conectaron y transformaron los datos, 
se diseñó un modelo relacional optimizado, y se crearon visualizaciones interactivas que permiten explorar información clave sobre los mercados internacionales y estadounidenses.

## **Estructura del Proyecto 📂**
Preparación y Conexión de Datos con Power Query
Diseño del Modelo Relacional y Mockup
Creación de Medidas y Columnas Calculadas con DAX
Desarrollo del Reporte Final en Power BI
### **1. Preparación y Conexión de Datos con Power Query 🛠️**
Objetivo:
Garantizar que los datos estén limpios y listos para su análisis en Power BI.

Pasos Realizados:

Descarga y Restauración de la Base de Datos:
Se descargó la base de datos AdventureWorksDW2019 y se restauró en SQL Server.
Conexión con Power BI:
Se conectó la base de datos a Power BI, importando la tabla Customer y otras tablas necesarias.
Transformaciones con Power Query:
Limpieza de datos (eliminación de duplicados, tratamiento de valores nulos).
Normalización de los datos.
Combinación de tablas para crear un conjunto de datos cohesivo.
Resultado:
Los datos fueron preparados y optimizados para facilitar el análisis y la creación de informes.

### **2. Diseño del Modelo Relacional y Mockup 📐**
Modelo Relacional:
Se diseñó un modelo relacional en Power BI siguiendo buenas prácticas para optimizar el rendimiento y facilitar el análisis de los datos.

Mockup Visual:
Se creó un mockup para representar cómo se vería el reporte final. Este diseño debía responder a preguntas clave sobre:

Ingresos.
Ventas.
Utilidades.
Costos.
Distribución geográfica de clientes y productos.
Patrón de Visualización:
Se aplicó el patrón Z para garantizar una visualización clara y eficiente de la información más relevante.

### **3. Creación de Medidas y Columnas Calculadas con DAX 📊**
Objetivo:
Analizar indicadores clave como ingresos, costos y rentabilidad utilizando DAX (Data Analysis Expressions).

Pasos Realizados:

Medidas Calculadas:
Se crearon medidas para calcular indicadores importantes como:
Ingresos totales.
Costos totales.
Rentabilidad.
Columnas Calculadas:
Se mejoró la información del modelo mediante la creación de columnas calculadas.
Optimización del Modelo:
Se deshabilitó la carga de tablas innecesarias (ProductCategory, ProductSubcategory y Geography) para mejorar el rendimiento.

### **4. Desarrollo del Reporte Final en Power BI 📋**
Creación del Reporte:
Se diseñaron visualizaciones interactivas basadas en el mockup creado previamente.

Aspectos Destacados:

Enfoque Principal:
Ingresos, costos y rentabilidad.
Análisis de los mercados internacionales y estadounidenses.
Personalización del Lienzo:
Se diseñó un dashboard visualmente atractivo, ajustando colores, etiquetas y títulos descriptivos.
Narrativa Coherente:
Cada página del reporte sigue una narrativa clara, garantizando un diseño consistente.
Interactividad:

Incorporación de filtros y parámetros para permitir a los usuarios explorar los datos de manera dinámica.
Grupos de cálculo para facilitar el análisis comparativo.

## **Herramientas Utilizadas 🛠️**
Power Query: Limpieza y transformación de datos.
Power BI: Modelado, creación de medidas con DAX, visualización de datos.
SQL Server: Restauración y gestión de la base de datos AdventureWorksDW2019.

## **Conclusión 🎯**
Este proyecto proporciona una solución integral para el análisis de datos de AdventureWorksDW2019. Se creó un reporte en Power BI que permite explorar de manera interactiva los ingresos, 
costos y rentabilidad, con un enfoque en la distribución geográfica de los clientes y productos. La combinación de un modelo de datos optimizado, medidas DAX precisas y visualizaciones efectivas facilita la toma de decisiones estratégicas basadas en datos.
