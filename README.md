# Análisis de Desempeño Comercial - Challenge Alura Store 

Este proyecto presenta un **Análisis Exploratorio de Datos (EDA)** detallado sobre el rendimiento operativo y financiero de cuatro sucursales de la cadena "Alura Store" en Colombia. El objetivo principal es proporcionar una recomendación estratégica basada en datos sobre la optimización del portafolio comercial.

##  Propósito del Análisis
El análisis busca responder a una necesidad de negocio crítica: **¿Cuál de las cuatro tiendas debería ser liquidada o traspasada?**

Para ello, se evaluaron las siguientes variables:
- **Volumen de Facturación:** Identificación de las tiendas con mayores ingresos.
- **Preferencia de Categorías:** Análisis de qué productos impulsan el negocio.
- **Satisfacción del Cliente:** Evaluación de la calidad del servicio mediante calificaciones.
- **Eficiencia Logística:** Comparación de costos de envío promedio.

##  Estructura del Proyecto
El proyecto está organizado en un único flujo de trabajo dentro del notebook `Challenge_Alura_FundamentDataScience.ipynb`:

1.  **Importación y Carga:** Configuración del entorno (Pandas, Numpy, Matplotlib, Seaborn) y carga de datos desde fuentes remotas (GitHub).
2.  **Análisis Exploratorio (EDA):** Revisión de la estructura, tipos de datos y estadísticas descriptivas de cada dataset.
3.  **Análisis de Facturación:** Comparativa de ingresos totales entre tiendas.
4.  **Ventas por Categoría:** Desglose del volumen de ventas por tipo de producto.
5.  **Valoración Media:** Cálculo del promedio de estrellas por sucursal.
6.  **Análisis Logístico:** Evaluación de costos de envío.
7.  **Informe de Conclusiones:** Síntesis de hallazgos y recomendación final.

##  Insights y Gráficos Obtenidos

### 1. Ingresos Totales por Tienda
Mediante un gráfico de pastel, se determinó que la **Tienda 1** representa la mayor porción de ingresos, mientras que la **Tienda 4** es la más rezagada financieramente.

### 2. Mapa de Calor de Ventas
Se generó un `heatmap` para visualizar la concentración de ventas. Un insight clave es que la categoría **"Muebles"** es el motor de ventas en todas las sucursales, seguida de **"Electrónicos"**.

### 3. Satisfacción vs. Costos
Aunque la **Tienda 3** tiene la mejor valoración de clientes (4.04), la **Tienda 4** destaca por tener los costos de envío más bajos, lo cual no es suficiente para compensar sus bajas ventas totales.

### 4. Recomendación Final
El informe concluye que la **Tienda 4** debe ser la elegida para la venta, ya que presenta el nivel de facturación más bajo del grupo, a pesar de sus ventajas logísticas.

##  Instrucciones de Ejecución

Para ejecutar este análisis en tu entorno local o en la nube, sigue estos pasos:

1.  **Requisitos Previos:**
    * Tener instalado Python 3.x.
    * Contar con las librerías: `pandas`, `numpy`, `matplotlib`, `seaborn`.

2.  **Instalación de dependencias:**
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```

3.  **Ejecución:**
    * Abre el archivo `Challenge_Alura_FundamentDataScience.ipynb` en **Jupyter Notebook** o **Google Colab**.
    * Ejecuta las celdas en orden secuencial. 
    * *Nota: El notebook descarga los archivos CSV automáticamente desde GitHub, por lo que se requiere conexión a internet.*

---
**Autor:** Gian Carlos Quezada Marceliano  
**Contexto:** Desafío Data Science - Alura Latam
