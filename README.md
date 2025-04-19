# Challenge-Alura-Robert
 El objetivo de este desafío es ayudar al señor Juan a decidir qué tienda debe vender para invertir en un nuevo negocio. Para ello, evaluaremos cuál de estas cuatro tiendas tiene un desempeño menor, permitiendo al señor Juan tomar la decisión de cuál de estas cuatro tiendas debe vender para invertir en un nuevo negocio.


# Desafío de Ciencia de Datos – Análisis de Ventas

Este proyecto consiste en un análisis exploratorio de datos aplicado a un conjunto de ventas de productos, con el objetivo de extraer métricas relevantes y visualizaciones claras que permitan comprender el comportamiento de los clientes y la performance comercial.

## Tecnologías utilizadas

- *Python*
- *Pandas*
- *Matplotlib*
- *Jupyter Notebook*

## Objetivo general

Unificar y analizar múltiples fuentes de datos con el fin de obtener información útil sobre ventas, preferencias de productos, desempeño de tiendas y satisfacción de los clientes.

## Dataset

Se trabajó con *cuatro tablas distintas, que fueron **unificadas en una sola* mediante técnicas de combinación (merge). Esto permitió disponer de una tabla consolidada para aplicar los cálculos y visualizaciones.

## Métricas calculadas y visualizaciones generadas

1. *Facturación total por tienda*  
   - Se calculó la suma de precios por tienda.  
   - Resultado presentado en un *gráfico de barras*.

2. *Categoría de producto más popular*  
   - Se analizó la frecuencia de compra por categoría.  
   - Visualización: *gráfico de barras ordenado*.

3. *Promedio de calificación de los clientes*  
   - Se calculó la media general de calificaciones.  
   - Resultado mostrado con un *print* por ser un único valor.

4. *Promedio de calificación por producto*  
   - Se agruparon las calificaciones por nombre de producto.  
   - Se graficaron los promedios con *barras ordenadas*.

5. *Promedio de calificación por vendedor*  
   - Similar al punto anterior, agrupado por nombre del vendedor.  
   - Representado también con un *gráfico de barras*.

6. *Productos más y menos vendidos*  
   - Se utilizó la frecuencia de aparición de cada producto.  
   - Se identificaron los más y menos vendidos con una *visualización comparativa*.

7. *Costo promedio de envío*  
   - Se calculó la media general del costo de envío.  
   - Resultado mostrado con print().

## Organización del código

- Todo el análisis está ordenado por secciones.
- Las visualizaciones se realizaron con Matplotlib.
- Las variables están nombradas de forma clara para facilitar la lectura.
- Se aplicaron funciones como groupby(), mean(), sum(), value_counts() y sort_values() para los cálculos agregados.

## Conclusiones

Este proyecto permite practicar análisis de datos reales utilizando herramientas de la ciencia de datos como limpieza, agrupamiento, cálculo de métricas clave y visualización, lo cual resulta esencial para cualquier perfil de analista o científico de datos.

---

*Autor:* Robert – Estudiante de Desarrollo de Software
