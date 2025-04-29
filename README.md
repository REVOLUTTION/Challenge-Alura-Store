# Alura Store: Análisis de Ventas

## Propósito del Análisis

El propósito de este análisis es examinar las ventas de varias tiendas en línea para identificar patrones de comportamiento, áreas de mejora y obtener información valiosa que pueda ayudar a las tiendas a optimizar sus operaciones y aumentar la satisfacción del cliente. A través de la exploración de los datos de ventas, calificaciones, productos más vendidos y costos de envío, buscamos obtener insights que faciliten la toma de decisiones informadas.

## Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

1. **AluraStoreLatam.ipynb**: Este es el notebook principal donde se realiza el análisis. Contiene todas las secciones, desde la importación de datos hasta la visualización de resultados y gráficos.
   
2. **Datos de Tienda**:
   - El proyecto utiliza los siguientes archivos CSV para analizar las ventas de diferentes tiendas:
     - Tienda 1: `tienda_1.csv`
     - Tienda 2: `tienda_2.csv`
     - Tienda 3: `tienda_3.csv`
     - Tienda 4: `tienda_4.csv`
   
3. **Resultados y Gráficos**: Se incluyen gráficos que muestran ventas por categoría, calificaciones promedio de las tiendas, y más. Estos gráficos nos permiten visualizar las métricas clave de una manera más comprensible.

## Ejemplos de Gráficos e Insights Obtenidos

- **Gráfico de Ventas por Categoría**: Permite identificar qué categorías de productos son más populares en cada tienda.
- **Gráfico de Calificación Promedio por Tienda**: Ayuda a ver cómo se comparan las tiendas en cuanto a la satisfacción del cliente.
- **Gráfico de Productos Más Vendidos**: Muestra cuáles son los productos que más se venden en cada tienda.

## Instrucciones para Ejecutar el Notebook en Google Colab

1. **Abrir Google Colab**:
   - Ve a [Google Colab](https://colab.research.google.com).
   
2. **Subir el Notebook**:
   - Haz clic en `Archivo` → `Subir notebook` y selecciona el archivo `AluraStoreLatam.ipynb`.

3. **Cargar los Archivos CSV**:
   - Los archivos CSV deben ser cargados en Google Colab. Si usas los archivos de ejemplo proporcionados, puedes hacerlo con los siguientes comandos:
     ```python
     from google.colab import files
     uploaded = files.upload()
     ```
   - Luego de cargar los archivos CSV, ejecútalos dentro del notebook para que los datos se importen correctamente.

4. **Ejecutar las Celdas**:
   - Simplemente ejecuta las celdas del notebook, comenzando por la importación de bibliotecas, hasta la visualización de gráficos.

5. **Visualizar los Resultados**:
   - Los gráficos y tablas generados aparecerán directamente en el notebook, proporcionándote los insights relevantes.

## Autor

Este proyecto fue realizado por **Antonio Rojas** como parte del desafío de Ciencia de Datos **Alura Store**.
