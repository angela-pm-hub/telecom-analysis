# telecom-analysis

Este repositorio contiene el análisis realizado durante el Sprint 7 del caso ConnectaTel, donde se busca entender cómo los clientes usan los servicios móviles en una empresa de telecomunicaciones en México y Colombia.

Los datasets utilizados presentan valores faltantes, sentinels, outliers y problemas de calidad diseñados para simular datos reales del comportamiento de uso de clientes.
- plans.csv: los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
- users_latam.csv: información de clientes: edad, ciudad, fecha de registro, plan contratado.
- usage.csv: el detalle de uso real: llamadas (duración) y mensajes (longitud).

## 📂 Contenido del repositorio

- `notebooks/telecom-analysis.ipynb`
  1. Carga y exploración
  2. Identificación de problemas de calidad
  3. Limpieza de datos (reemplazo de sentinels, conversión de fechas, imputación de NA)
  4. Revisión de medidas clave (media, mediana, percentiles)
  5. Visualización de outliers (histogramas y boxplots)
  6. Visualización de la segmentacióon de clientes
  7. Insight ejecutivo

## 📘 Cómo reproducir el análisis

1. Abre `notebooks/telecom-analysis.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

## 🧠 Objetivo del análisis

- Identificar problemas de calidad de datos
- Aplicar reglas de limpieza de datos
- Analizar comportamientos, distribuciones y outliers
- Generar insights accionables para el negocio, enfocadas en segmentación, patrones de uso y oportunidades comerciales 
