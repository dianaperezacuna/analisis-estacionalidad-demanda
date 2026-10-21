# Análisis de Estacionalidad, Demanda y Factores Climáticos en un Negocio de Postres

## Descripción del proyecto

Proyecto de análisis de datos desarrollado sobre un dataset sintético que representa dos años de operación de un negocio de postres en Santiago de Chile.

El objetivo fue identificar patrones estacionales de demanda y explorar cómo variables como la temperatura, las precipitaciones, la categoría de producto, la sucursal y el canal de venta se relacionan con el comportamiento de las ventas.

## Problema de negocio

El negocio presenta variaciones de demanda a lo largo del año. Se busca entender qué factores están asociados con esos cambios para apoyar decisiones de inventario, producción, mix de productos y estrategia de canal.

### Pregunta principal

¿Qué factores están asociados con los cambios de demanda durante los distintos períodos del año y qué acciones podrían ayudar a estabilizar los ingresos?

## Dataset

- Período analizado: 2024–2025
- Registros: 35.088
- Moneda: CLP
- Sucursales: Ñuñoa, Providencia y Las Condes
- Canales: Tienda y Delivery
- Categorías: Postres fríos, Postres calientes y Bebidas calientes

El dataset es sintético y fue construido exclusivamente con fines de aprendizaje, análisis y portafolio. Los resultados representan el escenario simulado y no deben interpretarse como evidencia causal sobre un negocio real.

## Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- Tableau Public

## Proceso de análisis

1. Revisión de estructura, tipos de datos y calidad general.
2. Validación de valores nulos y registros duplicados.
3. Creación de variables temporales para año, mes, día de semana y temporada.
4. Análisis de la evolución mensual de ingresos.
5. Comparación de demanda por temporada y categoría.
6. Evaluación del comportamiento de las categorías según rangos de temperatura.
7. Comparación del canal Tienda vs. Delivery en días con y sin lluvia.
8. Construcción de un dashboard interactivo en Tableau.

## Principales hallazgos

- Los **postres fríos** presentan mayor demanda durante períodos cálidos.
- Las **bebidas calientes** aumentan su participación cuando disminuye la temperatura.
- Los **postres calientes** muestran un comportamiento más estable durante el año.
- En días de lluvia se observa un desplazamiento de la demanda desde **Tienda** hacia **Delivery** dentro del escenario simulado.
- La estacionalidad afecta principalmente la **composición de la demanda**, más que provocar una caída uniforme de todas las categorías.

## Recomendaciones de negocio

- Ajustar inventario y producción según la temporada y la categoría.
- Reforzar visibilidad y comunicación del canal Delivery en días de lluvia.
- Utilizar las categorías de comportamiento más estable como soporte durante períodos de menor demanda de otras líneas.
- Incorporar datos reales de ventas y clima en una siguiente versión para validar si los patrones observados se mantienen.

## Dashboard

El dashboard incluye:

- KPI de **Ingreso total**
- KPI de **Clientes atendidos**
- KPI de **Unidades vendidas**
- Filtros interactivos por **Sucursal** y **Canal**
- Análisis de ingresos por **Temporada y Categoría**
- Comparación de la **Evolución mensual de ingresos 2024 vs. 2025**
- Interacción entre gráficos y KPI

### Dashboard interactivo en Tableau Public

[Ver dashboard en Tableau Public](https://public.tableau.com/app/profile/diana.stefania.perez.acu.a/viz/EstacionalidadDemandayVentas20242025/DashboardEstacionalidadyDemanda)

## Conclusión

El análisis muestra que la demanda cambia de composición de acuerdo con la estacionalidad y las condiciones climáticas del escenario simulado. Comprender estas variaciones permite anticipar cambios en el mix de productos, planificar inventario y producción con mayor criterio y adaptar la estrategia de canal según el contexto.

Este proyecto demuestra un flujo completo de trabajo analítico: definición del problema, preparación de datos, análisis exploratorio, interpretación de resultados, generación de recomendaciones y construcción de un dashboard interactivo para comunicar hallazgos.
