# 🛠️ 1. Análisis de Inventario - Ferretería Industrial

## 📋 Descripción del Proyecto
Este proyecto surge de la necesidad de optimizar la gestión de stock en una ferretería con más de 1,000 SKUs (productos). El objetivo es identificar productos críticos por agotarse y calcular el valor total del capital inmovilizado en el almacén.

## 🚀 Tecnologías Utilizadas
* **Python 3** (Ejecutado en entorno Cloud / Google Colab)
* **Pandas**: Para la manipulación y limpieza de datos.
* **NumPy**: Para la generación de datasets sintéticos.

## 📊 Análisis Realizados
1. **Detección de Quiebre de Stock:** Filtro avanzado para identificar productos con menos de 5 unidades disponibles.
2. **Valoración de Inventario:** Cálculo dinámico del valor total de la mercadería basado en `Stock * Precio`.
3. **Generación de Reportes:** Creación de archivos CSV listos para ser consumidos por herramientas de BI como Excel o Power BI.

## 📂 Archivos en este repositorio
* `Ferreteria.ipynb`: Notebook con todo el código documentado.
* `inventario.csv`: Dataset generado para el análisis.

# 📊 2. Análisis de Pareto (20/80) - Optimización de Inversión

## 📋 Descripción del Proyecto
Este análisis aplica la Ley de Pareto para jerarquizar el inventario de la ferretería. El objetivo es identificar el 20% de los productos que representan el 80% del valor monetario total, optimizando el flujo de caja y priorizando el control de los activos de mayor impacto financiero.

## 🚀 Tecnologías Utilizadas
* **Python 3** (Ejecutado en entorno Cloud / Google Colab)
* **Pandas**: Para cálculos de sumas acumuladas y ordenamiento de datos.
* **Matplotlib**: Para la generación del gráfico de curva de inversión.

## 📊 Análisis Realizados
1. **Cálculo de Inversión por SKU:** Multiplicación de `Stock * Precio` para determinar el peso económico de cada producto.
2. **Clasificación ABC:** Segmentación de productos mediante el cálculo del porcentaje acumulado sobre la inversión total.
3. **Identificación de Productos Críticos:** Selección del grupo "A" (productos de alta rotación y valor) para vigilancia de stock permanente.

## 📂 Archivos en este repositorio
* `Analisis_Pareto_Ferreteria.ipynb`: Notebook con el desarrollo matemático y visualización.
* `valor_acumulado.csv`: Reporte con la clasificación final de cada SKU.

# 📈 3. Análisis de Tendencia de Ventas - Proyección Mensual

## 📋 Descripción del Proyecto
Este análisis busca identificar los patrones de demanda estacional en la ferretería. El objetivo es predecir los meses de mayor rotación de inventario para planificar compras anticipadas y evitar el desabastecimiento en temporadas de alta demanda.

## 🚀 Tecnologías Utilizadas
* **Python 3** (Ejecutado en entorno Cloud / Google Colab)
* **NumPy**: Para la generación de tendencias y ruidos estadísticos en los datos.
* **Matplotlib**: Para la creación de diagramas de líneas y barras temporales.

## 📊 Análisis Realizados
1. **Simulación de Ventas Anuales:** Creación de un modelo de datos con fluctuaciones mensuales para representar la realidad comercial.
2. **Detección de Estacionalidad:** Identificación de picos de demanda (meses de mayor venta) mediante agregaciones temporales.
3. **Planificación de Stock:** Cálculo de niveles de inventario necesarios basados en la proyección de salida de mercancía.

## 📂 Archivos en este repositorio
* `Pronostico_de_ventas.ipynb`: Notebook con el análisis temporal y proyecciones.
* `proyeccion_mensual.csv`: Dataset con los resultados del modelo de demanda.
---

**Analista:** José Escalante - Data Analyst
