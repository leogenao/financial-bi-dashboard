# Sistema Integrado de BI Financiero (P&L y Flujos de Caja)

## 📌 Situación y Problema de Negocio
La alta dirección necesitaba supervisar de manera eficiente y en tiempo real el rendimiento operativo global y regional Los reportes estáticos dificultaban el análisis de escenarios predictivos ante condiciones volátiles del mercado o variaciones en los tipos de interés.

## 🎯 Acciones e Hitos Técnicos

### 1. Arquitectura de Datos Eficiente (Esquema en Estrella)
*Transformación de tablas planas en un **Star Schema** optimizado en Power BI
* Separación estricta entre tablas de hechos (*Fact Tables* de transacciones y flujos de caja) y tablas de dimensiones (*Dimension Tables* de fechas, regiones y productos) para garantizar la velocidad de filtrado de datos.

### 2. Modelado de Métricas Avanzadas (DAX)
* Diseño de un repositorio de **Medidas en DAX**, evitando el uso de columnas calculadas para optimizar el rendimiento y peso del archivo `.pbix`.
* Implementación de lógica de *Time Intelligence* para evaluar variaciones Año contra Año (YoY), márgenes operativos móviles (*rolling forecasts*) y métricas de inversión como el **VAN (NPV)** y la **TIR (IRR).
## 📊 Resultados e Impacto de Negocio
]Entrega de un cuadro de mando interactivo que redujo el tiempo de preparación de reportes ejecutivos, permitiendo a los stakeholders identificar de inmediato ineficiencias operativas y los principales motores de ingresos por región.

---

## 📁 Estructura del Repositorio
* `dashboard/financial_reporting_tool.pbix`: Archivo del proyecto de Power BI 
* `docs/dax_measures.md`: Documentación de las principales fórmulas DAX desarrolladas.
