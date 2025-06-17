# challenge2-data-science-LATAM
# Análisis de Rendimiento de Tiendas - Alura Store

![Python](https://img.shields.io/badge/Python-3.9-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.4-yellow.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5-orange.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-0.11-purple.svg)

## 🎯 Descripción del Proyecto

Este proyecto es la solución al primer desafío del programa de Data Science de **Alura Latam**. El objetivo es analizar datos de ventas, rendimiento y reseñas de las 4 tiendas de la cadena "Alura Store" para ayudar al Sr. Juan, el dueño, a tomar una decisión informada.

El escenario es el siguiente: el Sr. Juan necesita vender una de sus cuatro tiendas para financiar un nuevo emprendimiento. El análisis se enfoca en identificar la tienda con el **peor rendimiento** en métricas clave para recomendar su venta, minimizando así el impacto en los ingresos totales de la cadena.

## 🚀 Características del Análisis

El cuaderno de Jupyter (`AluraStore_Analisis.ipynb`) realiza un completo proceso de análisis de datos, que incluye:

*   **Extracción y Simulación de Datos:** Creación de un conjunto de datos realista que simula las ventas, categorías de productos, reseñas de clientes y tiempos de envío de cada tienda.
*   **Transformación y Limpieza:** Cálculo de nuevas métricas, como el `Ingreso_Total` por transacción, para enriquecer el análisis.
*   **Análisis Exploratorio de Datos (EDA):**
    *   **Análisis de Ingresos:** Comparación de los ingresos totales generados por cada tienda para identificar la más y menos rentable.
    *   **Análisis de Satisfacción del Cliente:** Evaluación de la reputación de cada tienda a través de las reseñas promedio de los clientes.
    *   **Análisis de Eficiencia Logística:** Medición del tiempo promedio de envío para evaluar la eficiencia operativa.
*   **Visualización de Datos:** Creación de gráficos claros y efectivos (barras, dispersión y circular) con `Matplotlib` y `Seaborn` para presentar los hallazgos de manera visual.
*   **Informe Final y Recomendación:** Un informe detallado que resume los resultados y presenta una recomendación estratégica fundamentada en los datos.

## 🛠️ Tecnologías Utilizadas

*   **Python:** Lenguaje principal para el análisis.
*   **Pandas:** Para la manipulación y el análisis de datos.
*   **NumPy:** Para la generación de datos numéricos simulados.
*   **Matplotlib y Seaborn:** Para la creación de visualizaciones de datos.
*   **Jupyter Notebook:** Como entorno de trabajo interactivo para el desarrollo del proyecto.

## 📂 Estructura del Proyecto

El proyecto se encuentra contenido en un único Jupyter Notebook:

*   `AluraStore_Analisis.ipynb`: Contiene todo el código y la documentación del proceso, dividido en las siguientes secciones:
    1.  **Extracción:** Carga y simulación de los datos.
    2.  **Transformación:** Limpieza y creación de nuevas variables.
    3.  **Análisis y Visualización:** Exploración de los datos y creación de los 3 gráficos requeridos.
    4.  **Informe Final:** Conclusión y recomendación para el Sr. Juan.

## 🏁 Cómo Ejecutar el Proyecto

Para ejecutar este análisis en tu máquina local, sigue estos pasos:

1.  **Clona el repositorio (o descarga los archivos):**
    ```bash
    git clone https://github.com/tu-usuario/alura-store-analisis.git
    cd alura-store-analisis
    ```
    *(Reemplaza `tu-usuario/alura-store-analisis` con la URL de tu repositorio)*

2.  **Crea un entorno virtual (recomendado):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # En Windows: venv\Scripts\activate
    ```

3.  **Instala las dependencias:**
    ```bash
    pip install pandas numpy matplotlib seaborn jupyterlab
    ```

4.  **Inicia Jupyter Lab:**
    ```bash
    jupyter lab
    ```

5.  Abre el archivo `AluraStore_Analisis.ipynb` en Jupyter Lab y ejecuta las celdas en orden de arriba hacia abajo.

## 📈 Conclusión del Análisis

El análisis concluye que la **Tienda C** es la candidata ideal para la venta. Esta recomendación se basa en los siguientes hallazgos clave:

*   **Ingresos más Bajos:** Genera significativamente menos ingresos que las otras tres tiendas.
*   **Peor Satisfacción del Cliente:** Tiene la calificación promedio más baja, lo que indica una mala experiencia de compra.
*   **Mayor Ineficiencia Logística:** Presenta los tiempos de envío más largos, afectando la percepción del cliente y la eficiencia operativa.

Vender la Tienda C permite al Sr. Juan obtener el capital que necesita mientras conserva sus activos más fuertes y rentables.

---
**Desarrollado por [Angelo Araneda]**
