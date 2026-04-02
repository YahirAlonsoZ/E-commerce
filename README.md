# Proyecto: Limpieza y Análisis de Datos de E-commerce

## Flujo de Trabajo

### 1. Limpieza de Datos
- Eliminación de duplicados y filas con datos críticos faltantes
- Corrección de formatos: fechas a ISO (YYYY-MM-DD), números con dos decimales
- Unificación de categorías: electronics, home, sports, books, clothing
- Recalculo de totales inconsistentes

### 2. Exploración de Datos (EDA)
- Análisis de distribución de ventas por categoría y estado
- Identificación de patrones temporales y métodos de pago
- Detección de outliers y anomalías lógicas

### 3. Modelado con IA
- Regresión: predicción de valor de órdenes (Random Forest, XGBoost)
- Clasificación: predicción de estado de órdenes
- Clustering: segmentación de clientes por comportamiento
- Series temporales: proyección de ventas

### 4. Estrategia de Negocio
- Identificación de clientes de alto valor (top 10%)
- Productos estrella vs problemáticos
- Optimización de métodos de pago y logística
- Recomendaciones accionables con respaldo cuantitativo

### 5. Comunicación de Resultados
- Reporte ejecutivo en formato .md
- Narrativa estructurada con métricas clave
- Visualizaciones descriptivas para stakeholders

## Entregables Principales
| Fase | Objetivo | Formato |
|------|----------|---------|
| Limpieza | Dataframe normalizado | CSV / Tabla |
| EDA | Patrones y tendencias | Gráficos + Insights |
| Modelado | Predicciones y clusters | Código Python + Métricas |
| Estrategia | Acciones de negocio | Recomendaciones + KPIs |
| Comunicación | Reporte ejecutivo | Markdown |

## Tecnologías Utilizadas
- Python: pandas, numpy, scikit-learn, xgboost, prophet
- Visualización: matplotlib, seaborn
- Documentación: Markdown

---

*Pipeline completo desde datos crudos a decisiones de negocio.*
