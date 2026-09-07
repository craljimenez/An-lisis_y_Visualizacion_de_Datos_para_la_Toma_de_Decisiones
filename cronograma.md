# Cronograma — Análisis y Visualización de Datos para la Toma de Decisiones

**Fuente:** [`Plan te trabajo Cursos.xlsx`](../Plan%20te%20trabajo%20Cursos.xlsx), hoja **"Analítica"**.
**Periodo:** 20262 · Sep 1 – Dic 13 · **15 semanas · 89 horas totales**.

> ⚠️ **Nota de revisión** (ver detalle al final del documento): las dos
> sesiones de "Bootcamp" (semanas 8 y 14) no tienen tema explícito en su
> segundo bloque de 3 h. Revisar antes de dar por cerrado el cronograma.

## Resumen por módulo

| Módulo | Semanas | Enfoque | Herramientas |
|---|---|---|---|
| 1. Explorar | 1–4 | Fundamentos de estadística descriptiva, Python básico y SQL | Google Colab, DBeaver, SQLite |
| 2. Construir | 5–8 | Limpieza y gestión de datos con Pandas | Python, Pandas, Jupyter/Colab |
| 3. Experimentar | 9–10 | Business Intelligence con Power BI | Power BI Desktop |
| 4. Innovar | 11–14 | Analítica predictiva y storytelling | Scikit-Learn, Canva/Slides |
| 5. Transformar | 15 | Cierre: dashboard empresarial aplicado | Power BI, Python, GitHub (opcional) |

## Tabla rápida de sesiones

| Sem. | Fecha | Clase | Tema | Modalidad | Horas |
|---|---|---|---|---|---|
| 1 | Sep 1 al 7 | 1 | Encuentro Inicial (Refrigerio) | Híbrido | 3 |
| 2 | Sep 8 al 13 | 2 | MasterClass (Nivelación): panorama del ecosistema de datos | Presencial | 3 |
| 2 | Sep 8 al 13 | 3 | Fundamentos de estadística descriptiva | Virtual | 3 |
| 3 | Sep 15 al 20 | 4 | Python para análisis de datos: fundamentos | Virtual | 3 |
| 3 | Sep 15 al 20 | 5 | Python aplicado a datos y preparación para SQL | Virtual | 3 |
| 4 | Sep 22 al 27 | 6 | Bases de datos relacionales y SQL básico | Virtual | 3 |
| 4 | Sep 22 al 27 | 7 | MasterClass (Recapitulación) | Presencial | 3 |
| 5 | Sep 29 al 4 Oct | 8 | Pandas: DataFrames y diagnóstico de calidad | Virtual | 3 |
| 5 | Sep 29 al 4 Oct | 9 | Transformación y enriquecimiento de datos | Virtual | 3 |
| 6 | Oct 6 al 11 | 10 | Agrupaciones y análisis con groupby | Virtual | 3 |
| 6 | Oct 6 al 11 | 11 | Merge, concatenación e integración de fuentes | Virtual | 3 |
| 7 | Oct 13 al 18 | 12 | Principios de visualización y comunicación de datos | Virtual | 3 |
| 7 | Oct 13 al 18 | 13 | MasterClass (Recapitulación y prep. bootcamp) | Presencial | 3 |
| 8 | Oct 20 al 25 | 14 | Bootcamp | Presencial | 3 |
| 8 | Oct 20 al 25 | 15 | Bootcamp (bloque 2, ⚠️ sin tema en el Excel) | Presencial | 3 |
| 9 | Oct 27 al 1 Nov | 16 | Power BI: carga, transformación y modelo de datos | Virtual | 3 |
| 9 | Oct 27 al 1 Nov | 17 | Dashboard e identificación de insights | Virtual | 3 |
| 10 | Nov 3 al 8 | 18 | Identificación de insights (cont.) | Virtual | 3 |
| 10 | Nov 3 al 8 | 19 | MasterClass (Recapitulación y prep. bootcamp) | Presencial | 3 |
| 11 | Nov 10 al 15 | 20 | De la analítica descriptiva a la predictiva | Virtual | 3 |
| 11 | Nov 10 al 15 | 21 | Regresión lineal con Python | Virtual | 3 |
| 12 | Nov 17 al 22 | 22 | Storytelling con datos: del hallazgo a la decisión | Virtual | 3 |
| 12 | Nov 17 al 22 | 23 | Diseño del argumento ejecutivo y métricas de impacto | Virtual | 3 |
| 13 | Nov 24 al 29 | 24 | Clínica de analítica predictiva y storytelling | Virtual | 3 |
| 13 | Nov 24 al 29 | 25 | MasterClass (Recapitulación y prep. bootcamp) | Presencial | 3 |
| 14 | Dic 1 al 6 Dic | 26 | Bootcamp | Presencial | 3 |
| 14 | Dic 1 al 6 Dic | 27 | Bootcamp (bloque 2, ⚠️ sin tema en el Excel) | Presencial | 3 |
| 15 | Dic 7 al 13 | 28 | Semana de la Innovación Multidisciplinar (cierre) | Presencial | 8 |

---

## Módulo 1: Explorar (Fundamentos y Consulta de Datos)

**Descripción:** Introducción al ecosistema de los datos y la estadística descriptiva. Aprendizaje de la sintaxis básica de Python y fundamentos de bases de datos relacionales mediante consultas SQL básicas.
**Conceptos clave:** Media, mediana, desviación estándar, variables, tipos de datos, SELECT, WHERE, JOINs.
**Herramientas:** Python (vía Google Colab), DBeaver, SQLite.

### Semana 1 — Sep 1 al 7
- **Clase 1 — Encuentro Inicial (Refrigerio)** · Híbrido · 3 h

### Semana 2 — Sep 8 al 13
- **Clase 2 — MasterClass (Nivelación): Encuentro inicial y panorama del desarrollo web** · Presencial · 3 h
  - *Contenido:* Panorama del ecosistema de datos; datos estructurados y no estructurados; ciclo de vida del dato; fuentes internas y externas; datos personales y calidad de datos; formulación de un problema de negocio que pueda abordarse con datos.
  - *Actividad/Producto:* Diagnóstico de conocimientos y mapa de fuentes de datos del caso integrador. Producto: problema y pregunta analítica inicial.
- **Clase 3 — Fundamentos de estadística descriptiva** · Virtual · 3 h
  - *Contenido:* Tipos de variables; población y muestra; frecuencias; media, mediana y moda; rango, varianza y desviación estándar; percentiles y lectura de distribuciones; interpretación de indicadores sin sobreinterpretarlos.
  - *Actividad/Producto:* Taller con un conjunto de datos real: cálculo e interpretación de estadísticos y detección inicial de valores atípicos.

### Semana 3 — Sep 15 al 20
- **Clase 4 — Python para análisis de datos: fundamentos** · Virtual · 3 h
  - *Contenido:* Google Colab; notebooks; variables y tipos de datos; operadores; listas; funciones; condicionales y ciclos; lectura básica de errores y buenas prácticas de organización del notebook.
  - *Actividad/Producto:* Laboratorio guiado: cargar, inspeccionar y transformar datos simples en Python.
- **Clase 5 — Python aplicado a datos y preparación para SQL** · Virtual · 3 h
  - *Contenido:* Importación de archivos CSV; exploración de columnas y tipos; operaciones básicas; filtros; conteos y resúmenes; introducción al pensamiento tabular y a la lógica consulta–resultado.
  - *Actividad/Producto:* Reto: responder preguntas de negocio mediante operaciones básicas de Python sobre un dataset.

### Semana 4 — Sep 22 al 27
- **Clase 6 — Bases de datos relacionales y SQL básico** · Virtual · 3 h
  - *Contenido:* Conceptos de tabla, registro, campo, clave primaria y relación; esquema relacional; SELECT, FROM, WHERE, ORDER BY, LIMIT; operadores lógicos y de comparación.
  - *Actividad/Producto:* Práctica en SQLite/DBeaver: consultas de extracción y filtrado sobre una base de datos empresarial.
- **Clase 7 — MasterClass (Recapitulación)** · Presencial · 3 h

---

## Módulo 2: Construir (Limpieza y Gestión de Datos)

**Descripción:** Manipulación avanzada de datos con Python. Uso intensivo de la librería Pandas para el diagnóstico de calidad de datos, tratamiento de valores nulos, duplicados y transformación de formatos.
**Conceptos clave:** DataFrames, imputación de nulos, agrupaciones (groupby), merge, concatenación, tipos de variables.
**Herramientas:** Python, Pandas, Jupyter Notebooks (vía Google Colab).

### Semana 5 — Sep 29 al 4 Oct
- **Clase 8 — Pandas: DataFrames y diagnóstico de calidad** · Virtual · 3 h
  - *Contenido:* Series y DataFrames; lectura de CSV/Excel; shape, columns, dtypes, info y describe; selección por columnas y filas; identificación de nulos, duplicados, tipos incorrectos y problemas de consistencia.
  - *Actividad/Producto:* Laboratorio: auditoría rápida de calidad de un dataset y formulación de reglas de limpieza.
- **Clase 9 — Transformación y enriquecimiento de datos** · Virtual · 3 h
  - *Contenido:* Columnas calculadas; funciones sobre columnas; renombrar variables; categorización; fechas y periodos; operaciones vectorizadas; principios de un pipeline reproducible de preparación.
  - *Actividad/Producto:* Ejercicio: crear variables analíticas que permitan segmentar clientes, productos o servicios.

### Semana 6 — Oct 6 al 11
- **Clase 10 — Agrupaciones y análisis con groupby** · Virtual · 3 h
  - *Contenido:* groupby; agregaciones múltiples; tablas resumen; ordenamiento; porcentajes y participaciones; comparación por categorías y periodos; lectura de resultados agregados.
  - *Actividad/Producto:* Reto: construir un cuadro de indicadores segmentado y explicar los hallazgos principales.
- **Clase 11 — Merge, concatenación e integración de fuentes** · Virtual · 3 h
  - *Contenido:* merge y sus tipos de unión; concatenación vertical y horizontal; llaves de integración; detección de registros no emparejados; control de cardinalidad; consistencia antes y después de unir fuentes.
  - *Actividad/Producto:* Laboratorio: integrar al menos dos fuentes de datos y validar la calidad del resultado.

### Semana 7 — Oct 13 al 18
- **Clase 12 — Principios de visualización y comunicación de datos** · Virtual · 3 h
  - *Contenido:* Qué hace efectiva una visualización; selección del gráfico según la pregunta; comparación, composición, distribución y relación; escalas; etiquetas; color; reducción de ruido visual; errores comunes y gráficos engañosos.
  - *Actividad/Producto:* Taller: rediseñar visualizaciones deficientes y justificar la elección del gráfico.
- **Clase 13 — MasterClass (Recapitulación y preparación de bootcamp)** · Presencial · 3 h

### Semana 8 — Oct 20 al 25
- **Clase 14 — Bootcamp** · Presencial · 3 h
- **Clase 15 — Bootcamp (bloque 2)** · Presencial · 3 h — ⚠️ sin tema/contenido especificado en el Excel (ver notas).

---

## Módulo 3: Experimentar (Visualización e Insights)

**Descripción:** Introducción al Business Intelligence. Conexión de datos limpios a Power BI, creación de modelos de datos simples (Tablas de Hechos y Dimensiones) y diseño de gráficos interactivos eficaces.
**Conceptos clave:** Modelo estrella, relaciones, filtros, KPIs, gráficos de barras, líneas, dispersión y mapas.
**Herramientas:** Power BI Desktop.

### Semana 9 — Oct 27 al 1 Nov
- **Clase 16 — Power BI: carga, transformación y modelo de datos** · Virtual · 3 h
  - *Contenido:* Power BI Desktop; importar datos; Power Query básico; tablas y campos; relaciones; cardinalidad; conceptos de tabla de hechos y dimensiones; modelo estrella.
  - *Actividad/Producto:* Laboratorio: cargar el dataset del proyecto y construir un modelo sencillo con relaciones correctas.
- **Clase 17 — Dashboard e identificación de insights** · Virtual · 3 h
  - *Contenido:* Gráficos de barras, líneas, dispersión y mapas; comparación temporal; anomalías; tendencias; selección de insights accionables; validación de cifras y coherencia entre visuales.
  - *Actividad/Producto:* Taller integrador: tablero exploratorio y ficha de 3–5 insights con evidencia visual y recomendación.

### Semana 10 — Nov 3 al 8
- **Clase 18 — Identificación de insights (cont.)** · Virtual · 3 h
  - *Contenido:* Medidas y cálculos básicos; KPIs; segmentadores; filtros de página y de visual; jerarquías; interacción entre visuales; diseño de una página orientada a preguntas de negocio.
  - *Actividad/Producto:* Construcción de la primera página del tablero con indicadores y filtros funcionales.
- **Clase 19 — MasterClass (Recapitulación y preparación de bootcamp)** · Presencial · 3 h

---

## Módulo 4: Innovar (Analítica Predictiva y Storytelling)

**Descripción:** Evolución del análisis descriptivo al predictivo mediante modelos sencillos de Machine Learning. Técnicas narrativas para presentar datos de forma persuasiva a audiencias de negocio.
**Conceptos clave:** Regresión lineal, tendencias, audiencias, estructura narrativa, carga cognitiva visual.
**Herramientas:** Scikit-Learn (vía Google Colab), Canva / Google Slides (para storytelling).

### Semana 11 — Nov 10 al 15
- **Clase 20 — De la analítica descriptiva a la predictiva** · Virtual · 3 h
  - *Contenido:* Diferencia entre descripción, diagnóstico y predicción; variable objetivo y variables explicativas; correlación vs. causalidad; entrenamiento y prueba; idea general de Machine Learning supervisado.
  - *Actividad/Producto:* Actividad: formular una pregunta predictiva y seleccionar variables relevantes para el caso.
- **Clase 21 — Regresión lineal con Python** · Virtual · 3 h
  - *Contenido:* Concepto de regresión lineal; ajuste de un modelo; predicción; error y residuales; R² como medida orientativa; interpretación de coeficientes; límites del modelo y riesgos de extrapolación.
  - *Actividad/Producto:* Laboratorio en Google Colab: entrenar un modelo sencillo y explicar sus resultados en lenguaje de negocio.

### Semana 12 — Nov 17 al 22
- **Clase 22 — Storytelling con datos: del hallazgo a la decisión** · Virtual · 3 h
  - *Contenido:* Audiencia; mensaje principal; estructura de una narrativa; contexto–tensión–evidencia–recomendación; jerarquía visual; reducción de carga cognitiva; uso responsable de datos en presentaciones ejecutivas.
  - *Actividad/Producto:* Transformar hallazgos del dashboard en una narrativa de 5–7 diapositivas para una audiencia directiva.
- **Clase 23 — Diseño del argumento ejecutivo y métricas de impacto** · Virtual · 3 h
  - *Contenido:* KPI vs. métrica; indicadores de resultado y de proceso; métricas de impacto; hipótesis de negocio; priorización de hallazgos; estimación básica de impacto/ROI cuando aplique.
  - *Actividad/Producto:* Taller: construir la matriz indicador–hallazgo–decisión–impacto del proyecto.

### Semana 13 — Nov 24 al 29
- **Clase 24 — Clínica de analítica predictiva y storytelling** · Virtual · 3 h
  - *Contenido:* Estructura del pitch; apertura con problema y contexto; evidencia; recomendaciones; impacto esperado; gestión de preguntas; comunicación clara de incertidumbre y limitaciones.
  - *Actividad/Producto:* Socialización: presentación corta del caso, modelo y recomendación, con retroalimentación estructurada.
- **Clase 25 — MasterClass (Recapitulación y preparación de bootcamp)** · Presencial · 3 h

### Semana 14 — Dic 1 al 6 Dic
- **Clase 26 — Bootcamp** · Presencial · 3 h
- **Clase 27 — Bootcamp (bloque 2)** · Presencial · 3 h — ⚠️ sin tema/contenido especificado en el Excel (ver notas).

---

## Módulo 5: Transformar (Dashboard Empresarial Aplicado)

**Descripción:** Módulo de cierre práctico estilo Bootcamp. Consolidación de todas las fases del proyecto integrador, optimización del tablero empresarial final y simulación de comités de toma de decisiones.
**Conceptos clave:** Reporte ejecutivo, indicadores de impacto (ROI), despliegue de tableros, oratoria corporativa.
**Herramientas:** Power BI Desktop, Python (GitHub para control de versiones opcional).

### Semana 15 — Dic 7 al 13
- **Clase 28 — Semana de la Innovación Multidisciplinar** · Presencial · 8 h (cierre del curso: sustentación del dashboard/proyecto integrador)

---

## Notas de revisión

1. **Filas ocultas del Excel — ignoradas.** La hoja "Analítica" tiene 5 filas ocultas (20, 31, 36, 49, 50). Todas están vacías salvo la 36, que traía un tema ajeno al curso ("Automatización de procesos: eventos, triggers y actions", de otra hoja del mismo libro). Como está oculta en el Excel — no aparece al abrir/mirar la hoja —, se excluyó del cronograma; la numeración de clases ya quedó ajustada (20 → 21 → 22... sin salto).
2. **Semanas 8 y 14 (Bootcamp):** cada semana de bootcamp trae dos bloques de 3 h en el Excel, pero el segundo bloque no tiene tema propio (fila casi vacía, solo con las horas, y esta sí es visible en la hoja). Probablemente ambos bloques comparten el mismo contenido de bootcamp (trabajo autónomo/asesoría sobre el proyecto integrador) — vale la pena confirmarlo para no dejar la sesión "en blanco" en la planeación de clase.
3. El total de horas (89) cuadra con la suma fila por fila del Excel, contando las filas visibles únicamente.

---

## Plantilla LaTeX

La plantilla de diapositivas para cada clase está en [`plantilla/`](./plantilla/):
- `beamerthemeesumer.sty` — tema Beamer con la identidad de Esumer/Estud-IA (colores, tipografía, portada, pie de página).
- `clase-template.tex` — plantilla de clase lista para copiar por sesión.
- `assets/` — logos institucionales.

Ver [`plantilla/README.md`](./plantilla/README.md) para el flujo de trabajo completo.
