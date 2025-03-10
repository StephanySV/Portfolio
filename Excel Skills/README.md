# Análisis de Ventas en el Sector Automotriz en EE. UU.
### 📝 1. Introducción
Este proyecto tiene como objetivo analizar las principales fuentes de ventas en una red de tiendas de automóviles en Estados Unidos, identificando tendencias y patrones clave. Para ello, se utilizó Microsoft Excel como herramienta principal para la limpieza, transformación y visualización de los datos, permitiendo extraer información relevante de manera efectiva.

### 📂 2. Fuentes de Datos

Los datos utilizados en este análisis provienen de una base de datos pública en Kaggle, en formato CSV. Esta base contiene información estructurada sobre las ventas de vehículos realizadas entre 2022 y 2023, distribuidas en 16 columnas y 23,906 filas.

### 🖋️ 3. Limpieza y Preparación de Datos

Para garantizar la calidad y coherencia de los datos, se llevaron a cabo las siguientes acciones:
- Estandarización de formatos en fechas, números y texto.
- Incorporación de información adicional, como los estados en los que operan las tiendas de automóviles.
- Unificación de marca y modelo para facilitar el análisis y la segmentación de datos.

### 💻 4. Análisis y Transformación

Se aplicaron diversas funciones y herramientas de Excel para extraer información clave, incluyendo:
- Uso de funciones avanzadas como BUSCARV, UNICOS, TEXTO, MEDIANA(SI()), entre otras.
- Creación de columnas calculadas con funciones como CONTAR.SI y SUMAR.SI.
- Aplicación de tablas dinámicas para resumir los datos y facilitar su interpretación.

    #### *Creación de campo calculado*
   
  ![image](https://github.com/user-attachments/assets/35da696b-36dd-4163-874a-2c70ae334111)


    #### *Algunas formulas utilizadas* 

    `=MEDIAN(IF(car_sales[Customer Name]=List!$G2;car_sales[Annual Income]))`

    `=UNIQUE(car_sales[Dealer_Region])`



### 📊 5. Visualización y Presentación

Para representar los hallazgos de manera clara y comprensible, se utilizaron:
- Gráficos dinámicos, que permiten visualizar tendencias y comparaciones de manera interactiva.
- Segmentaciones de datos, facilitando el filtrado y análisis específico de cada variable.

    #### *Creación de graficas y segmentadores*
     ![image](https://github.com/user-attachments/assets/f58ae79c-8ed5-43f9-a5cb-f5344ecc1c71)


### 📈 6. Conclusiones y Resultados
- Se identificaron las tiendas y clientes con mayores volúmenes de ventas, así como las regiones y marcas con mayor participación en el mercado.
- Estos hallazgos permiten optimizar estrategias de marketing y promociones, enfocándose en los segmentos con mayor potencial de crecimiento.
- La información obtenida es clave para la toma de decisiones estratégicas, incluyendo posibles acuerdos comerciales con clientes de alto valor y la definición de estrategias de expansión.

### ✅ 7. Habilidades Demostradas

A través de este análisis, se demostraron las siguientes habilidades clave:

- Dominio avanzado de Excel, incluyendo funciones y herramientas avanzadas.
- Limpieza y transformación de datos, asegurando la integridad y coherencia de la información.
- Creación de visualizaciones efectivas, facilitando la interpretación de los datos.
- Pensamiento analítico y resolución de problemas, para extraer insights valiosos y accionables.

\_________________________________________________________________________________________________________________




# Sales Analysis in the Automotive Sector in the U.S.

### 📝 1. Introduction

This project aims to analyze the main sales sources in a network of automobile dealerships in the United States, identifying key trends and patterns. Microsoft Excel was used as the primary tool for data cleaning, transformation, and visualization, enabling the extraction of valuable insights effectively.

### 📂 2. Data Sources

The data used in this analysis comes from a public Kaggle database in CSV format. This dataset contains structured information on vehicle sales conducted between 2022 and 2023, distributed across 16 columns and 23,906 rows.

### 🖋️ 3. Data Cleaning and Preparation

To ensure data quality and consistency, the following actions were taken:
- Standardization of date, number, and text formats.
- Inclusion of additional information, such as the states where the dealerships operate.
- Unification of brand and model names to simplify analysis and data segmentation.

### 💻 4. Analysis and Transformation

Various Excel functions and tools were applied to extract key insights, including:
- Use of advanced functions such as VLOOKUP, UNIQUE, TEXT, MEDIAN(IF()), among others.
- Creation of calculated columns using functions like COUNTIF and SUMIF.
- Application of pivot tables to summarize data and facilitate interpretation.


    #### *Calculated field creation*

   ![image](https://github.com/user-attachments/assets/0cbe88c4-c6f1-49a7-a065-c7b4b55c13bd)

    #### *Some used formulas* 

    `=MEDIAN(IF(car_sales[Customer Name]=List!$G2;car_sales[Annual Income]))`

    `=UNIQUE(car_sales[Dealer_Region])`


### 📊 5. Visualization and Presentation

To represent the findings clearly and comprehensively, the following tools were used:
- Dynamic charts, allowing for interactive trend and comparison analysis.
- Data slicers, facilitating filtering and specific variable analysis.

    #### *Creating graphs and slicers*
    ![image](https://github.com/user-attachments/assets/05a676cd-bb48-4161-8d55-3ea4e39cfc03)


### 📈 6. Conclusions and Results
- The analysis identified the dealerships and customers with the highest sales volumes, as well as the regions and brands with the largest market share.
- These insights help optimize marketing strategies and promotions, focusing on segments with the highest growth potential.
- The extracted information is crucial for strategic decision-making, including potential commercial agreements with high-value clients and defining expansion strategies.

### ✅7. Demonstrated Skills

This analysis demonstrated the following key skills:

- Advanced proficiency in Excel, including complex functions and tools.
- Data cleaning and transformation, ensuring data integrity and consistency.
- Effective data visualization, enhancing data interpretation.
- Analytical thinking and problem-solving, extracting valuable and actionable insights.
