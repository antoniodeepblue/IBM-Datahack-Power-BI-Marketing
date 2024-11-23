# IBM-Datahack-Power-BI-Marketing
### Noviembre 2024
#### *Autor:* Antonio Fernández

### Análisis del Proyecto Final de Data Analytics con Power BI. 

#### Acceso al informe en línea en el Servicio Power BI:
https://app.powerbi.com/view?r=eyJrIjoiMWJlZTY5ZDUtODhkZC00YjMxLWFlOGUtMzQ0ZDNkOTVhZTZmIiwidCI6ImFlYzc2MmU0LTNkNTQtNDk1ZS1hOGZlLTQyODdkY2U2ZmU2OSIsImMiOjh9

#### Proyecto final para el curso de Data Analytics con Power BI, enfocado en el análisis de datos de campañas de marketing.

![image](https://github.com/user-attachments/assets/32b57fbb-8b26-4606-83dd-b21a388302e1)

## Objetivo del Proyecto:

El proyecto busca brindar una experiencia práctica en análisis de datos. El objetivo es crear un proyecto final basado en la práctica.

## Descripción del Proyecto:

El proyecto simula un escenario real donde una empresa de consultoría, DH Marketing Consultants, contrata al estudiante como analista de datos. La tarea consiste en analizar un conjunto de datos de marketing para generar insights y valor para el director de marketing. El análisis debe considerar diferentes factores y organizar la información por fechas, campañas y productos.

## Fuente de Datos:

El conjunto de datos proviene de una fuente abierta en Kaggle y contiene información sobre 5 campañas de marketing, incluyendo las plataformas utilizadas y el número de ventas generadas a través de cada plataforma. ("Los datos proporcionados corresponden a una fuente de datos abiertos, la cual nos proporciona data relacionada con 5 campañas de marketing que realizo una empresa...")

## Etapas del Proyecto:

El proyecto se divide en las siguientes etapas:

1.	Carga de datos: Importar el archivo CSV a Power BI y revisar los datos en Power Query.
2.	Limpieza de datos: Identificar y corregir errores en los datos, como valores atípicos, datos faltantes o errores de escritura.
3.	Transformación de datos: Renombrar y organizar las columnas, modificando los tipos de datos si es necesario. Justificar los cambios realizados.
4.	Modelado de datos: Crear un modelo de datos en estrella, con una tabla de hechos central conectada a las tablas de dimensiones.
5.	Visualizaciones: Diseñar un dashboard interactivo: una visión general, análisis de campañas y análisis de productos. Incluir filtros y botones para facilitar la navegación.


## Elementos Clave del Proyecto:

•	Utilización del proceso ETL (Extract, Transform, Load) completo.

•	Normalización de tablas para asegurar la calidad de los datos.

•	Creación de un modelo de datos robusto con relaciones entre tablas.

•	Implementación de medidas DAX (Data Analysis Expressions) para análisis en profundidad.

•	Diseño de un dashboard interactivo con insights relevantes.

## Desarrollo

➢ Implementar el modelo de datos adecuado para el análisis: debe generar un modelo lo más cercano a un modelo estrella.

➢ Métricas de DAX para calcular:

 • Total de clientes.
 
 • Ingreso medio de los clientes.
 
 • Totales de compras por producto.
 
 • Totales por campañas.
 
 • Tabla calendario.
 
➢ Desarrollar visualizaciones que permitan comprender los datos:

 • Gráficos de líneas.
 
 • Gráficos de barras (pueden ser apiladas).
 
 • Gráficos de anillos.
 
 • Tablas.
 
 • Matrices.
 
➢ Paneles de filtro.

 • Debes incluir por lo menos dos filtros sincronizados. Año, Mes y Estado Civil.
 
➢ Marcadores y botones de navegación

➢ Extrae los datos de la web:

 https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign?resource=download

## Fases de Power BI

Gestión de Datos (GD):

• Conexión y Actualización de Datos: Importar datos de diversas fuentes.

• Query Editor: Limpieza, transformación y preparación de datos.


Modelado de Datos (DM):

• Relaciones de Tablas: Establecer conexiones entre diferentes tablas.

• Introducción a DAX: Lenguaje de fórmulas para análisis avanzados.


Visualización de Datos (DV):

• Creación de Visualizaciones: Seleccionar el tipo de gráfico adecuado.

• Interacciones y Filtros: Crear reportes interactivos.

• Formato de Visualizaciones: Personalizar la apariencia de los gráficos.

Presentación de Reportes (DR):

• Formato de Reporte: Diseño y estructura del reporte.

• Publicación y Compartición: Compartir reportes en línea.


## Campos y registros

Los campos que conforman el dataset podrían ser clasificados en 4 grupos principales, siendo 29 en total:

* **Datos Demográficos y Personales:** 
<br></br>

1. **ID**: Identificación única del cliente. (Tipo de dato: Entero)

2. **Year_Birth**: Año de nacimiento del cliente. (Tipo de dato: Entero)

3. **Education**: Nivel educativo del cliente. (Tipo de dato: Cadena de texto)

4. **Marital_Status**: Estado civil del cliente. (Tipo de dato: Cadena de texto)

5. **Income**: Ingresos anuales del hogar del cliente. (Tipo de dato: Numérico - decimal)

6. **Kidhome**: Número de niños pequeños en el hogar del cliente. (Tipo de dato: Entero)

7. **Teenhome**: Número de adolescentes en el hogar del cliente. (Tipo de dato: Entero)

8. **Dt_Customer**: Fecha de inscripción del cliente con la empresa. (Tipo de dato: Fecha)
<br></br>

* **Comportamiento de Compra:**
<br></br>

1. **Recency**: Número de días desde la última compra del cliente. (Tipo de dato: Entero)

2. **NumDealsPurchases**: Número de compras realizadas con descuento. (Tipo de dato: Entero)

3. **NumWebPurchases**: Número de compras realizadas a través del sitio web de la empresa. (Tipo de dato: Entero)

4. **NumCatalogPurchases**: Número de compras realizadas usando catálogo. (Tipo de dato: Entero)

5. **NumStorePurchases**: Número de compras realizadas directamente en tiendas. (Tipo de dato: Entero)

6. **NumWebVisitsMonth**: Número de visitas al sitio web de la empresa en el último mes. (Tipo de dato: Entero)
<br></br>

* **Gastos en Productos**:
<br></br>

1. **MntWines**: Monto gastado en productos de vino en los últimos 2 años. (Tipo de dato: Numérico - decimal)

2. **MntFruits**: Monto gastado en productos de frutas en los últimos 2 años. (Tipo de dato: Numérico - decimal)

3. **MntMeatProducts**: Monto gastado en productos de carne en los últimos 2 años. (Tipo de dato: Numérico - decimal)

4. **MntFishProducts**: Monto gastado en productos de pescado en los últimos 2 años. (Tipo de dato: Numérico - decimal)

5. **MntSweetProducts**: Monto gastado en productos dulces en los últimos 2 años. (Tipo de dato: Numérico - decimal)

6. **MntGoldProds**: Monto gastado en productos de oro en los últimos 2 años. (Tipo de dato: Numérico - decimal)
<br></br>

* **Respuestas a Campañas de Marketing:**
<br></br>

1. **AcceptedCmp3**: 1 si el cliente aceptó la oferta en la tercera campaña, 0 en caso contrario. (Tipo de dato: Entero - binario)

2. **AcceptedCmp4**: 1 si el cliente aceptó la oferta en la cuarta campaña, 0 en caso contrario. (Tipo de dato: Entero - binario)

3. **AcceptedCmp5**: 1 si el cliente aceptó la oferta en la quinta campaña, 0 en caso contrario. (Tipo de dato: Entero - binario)

4. **AcceptedCmp1**: 1 si el cliente aceptó la oferta en la primera campaña, 0 en caso contrario. (Tipo de dato: Entero - binario)

5. **AcceptedCmp2**: 1 si el cliente aceptó la oferta en la segunda campaña, 0 en caso contrario. (Tipo de dato: Entero - binario)

6. **Complain**: 1 si el cliente presentó una queja en los últimos 2 años. (Tipo de dato: Entero - binario)

7. **Z_CostContact**: Costo fijo asociado al contacto con el cliente. (Tipo de dato: Entero)

8. **Z_Revenue**: Ingresos generados por el contacto con el cliente. (Tipo de dato: Entero)

9. **Response**: 1 si el cliente aceptó la oferta en la última campaña, 0 en caso contrario. (Tipo de dato: Entero - binario)

## Glosario de Términos

•	Power BI: Herramienta de análisis de negocios de Microsoft.

•	Power BI Desktop: Aplicación de escritorio para crear reportes y visualizaciones.

•	Dashboard: Panel interactivo que muestra visualizaciones clave.

•	Query Editor: Herramienta para limpiar, transformar y preparar datos.

•	Relaciones de Tablas: Conexiones lógicas entre diferentes tablas.

•	DAX (Data Analysis Expressions): Lenguaje de fórmulas para análisis avanzados.

•	Visualización: Representación gráfica de datos.

•	Filtro: Herramienta para seleccionar datos específicos.

•	Formato: Ajuste de la apariencia de un reporte o visualización.

•	Publicación: Compartir reportes en línea o en la nube.

## Conclusiones:

•	Se demuestra la importancia del análisis de datos en el marketing y cómo Power BI puede utilizarse para obtener insights valiosos de los datos. El uso de un proceso ETL, la creación de un modelo de datos sólido y el diseño de visualizaciones efectivas son elementos clave para el éxito de un proyecto de análisis de datos.

## Recomendaciones:

•	Es crucial comprender el contexto del negocio y las preguntas que se buscan responder con el análisis.

•	La limpieza y transformación de datos son fundamentales para obtener resultados precisos.

•	El modelo de datos debe ser claro y fácil de entender para facilitar el análisis.

•	Las visualizaciones deben ser intuitivas y comunicar la información de forma clara.
