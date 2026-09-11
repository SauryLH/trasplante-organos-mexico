# Trasplante de Órganos en México — Informes 2024-2025

Análisis de patrones, tendencias y posibles factores asociados a la participación en la donación de órganos en México.

**Proyecto académico — Coderhouse** · Autora: Ana Luisa Herrera Hernández

## Objetivo

Comprender los patrones, tendencias y factores que influyen en la participación ciudadana en la donación de órganos en México, identificando oportunidades de mejora y fortalecimiento del sistema nacional de donación y trasplante.

## Hipótesis central

El análisis sistemático de los datos de donación de órganos revela disparidades significativas en la distribución y recepción de órganos a nivel nacional — evidenciando la necesidad urgente de fortalecer las políticas públicas existentes en materia de donación y trasplante.

## Fuente y estructura de datos

Base de datos organizada en 3 módulos principales: **donantes**, **órganos**, y **resumen anual**, integrando variables demográficas, médicas, y administrativas del periodo **2024-2025**.

Modelo relacional de 6 tablas en Power BI (esquema estrella):
- `Fact_Transplantes` — registros individuales de trasplantes (fecha, órgano, resultado a 24h)
- `Dim_EntidadFederativa` — catálogo de estados de la república
- `Dim_Institucion` — instituciones médicas responsables
- `Dim_Organo` — clasificación por tipo de órgano
- `Fact_Organo_Mapping` — vínculo entre trasplante y órgano
- `Calendario` — jerarquía temporal (año, mes, día)

## Herramientas

- **Excel** — preprocesamiento y validación inicial de datos
- **Power BI** — modelado relacional, medidas DAX, y dashboard interactivo

## 📊 Estructura del dashboard

El dashboard se organiza en 7 solapas, guiando al usuario desde una visión global hasta el detalle:

1. Portada
2. Glosario
3. Indicadores Principales
4. Tendencia Temporal
5. Trasplante por Órgano
6. Mapa por Institución
7. Trasplantes por Sexo

## Hallazgos principales

- Se registraron **6,451 trasplantes** en total durante 2024-2025, con una tasa de éxito a 24 horas del 39%
- **Córnea y riñón** son, por mucho, los órganos más trasplantados a nivel nacional
- **2024** fue el año con mayor número de trasplantes, con una tendencia a la baja hacia finales de 2025
- Existe una **fuerte concentración geográfica** de trasplantes en el centro del país, evidenciando disparidades regionales

## Líneas futuras

- Ampliar el horizonte temporal con datos históricos adicionales
- Integrar variables sociodemográficas (nivel socioeconómico, comorbilidades)
- Desarrollar indicadores avanzados de desempeño (complicaciones postoperatorias, tiempo en lista de espera, supervivencia anual)

## 🔗 Ver el proyecto completo

El caso de estudio completo, con capturas del dashboard interactivo, está disponible en mi portafolio:
**[saurylhstudio.com/data/trasplante-de-organos-mexico](https://saurylhstudio.com/data/trasplante-de-organos-mexico)**
