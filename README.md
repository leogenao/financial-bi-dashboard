# Sistema Integrado de BI Financiero (P&L y Flujos de Caja)

## 📌 Situación y Problema de Negocio
[cite_start]La alta dirección necesitaba supervisar de manera eficiente y en tiempo real el rendimiento operativo global y regional[cite: 15]. [cite_start]Los reportes estáticos dificultaban el análisis de escenarios predictivos ante condiciones volátiles del mercado o variaciones en los tipos de interés[cite: 17].

## 🎯 Acciones e Hitos Técnicos

### 1. Arquitectura de Datos Eficiente (Esquema en Estrella)
* [cite_start]Transformación de tablas planas en un **Star Schema** optimizado en Power BI[cite: 15].
* [cite_start]Separación estricta entre tablas de hechos (*Fact Tables* de transacciones y flujos de caja) y tablas de dimensiones (*Dimension Tables* de fechas, regiones y productos) para garantizar la velocidad de filtrado de datos[cite: 15].

### 2. Modelado de Métricas Avanzadas (DAX)
* Diseño de un repositorio de **Medidas en DAX**, evitando el uso de columnas calculadas para optimizar el rendimiento y peso del archivo `.pbix`.
* [cite_start]Implementación de lógica de *Time Intelligence* para evaluar variaciones Año contra Año (YoY), márgenes operativos móviles (*rolling forecasts*) y métricas de inversión como el **VAN (NPV)** y la **TIR (IRR)**[cite: 17].

## 📊 Resultados e Impacto de Negocio
* [cite_start]Entrega de un cuadro de mando interactivo que redujo el tiempo de preparación de reportes ejecutivos, permitiendo a los stakeholders identificar de inmediato ineficiencias operativas y los principales motores de ingresos por región[cite: 15, 19].

---

## 📁 Estructura del Repositorio
* `dashboard/financial_reporting_tool.pbix`: Archivo del proyecto de Power BI (puedes incluir capturas de pantalla `.png` en el README si no quieres subir el archivo pesado).
* `docs/dax_measures.md`: Documentación de las principales fórmulas DAX desarrolladas.
