# 📊 Big Data Aplicada a los Negocios (UDLA)

Materiales del curso **Big Data Aplicada a los Negocios**. Cuatro semanas, cuatro casos de negocio ficticios (InvestAR Capital, Hospital San Martín, MercadoVoz y StreamAR/ModaIA), cada uno resuelto con datos reales y un pipeline completo de principio a fin.

Cada semana combina un **notebook de clase** (con datos y resultados reales, no simulados), una **guía de lectura teórica**, **dos tareas grupales** y un **examen de opción múltiple**. El objetivo no es solo correr modelos: es que el estudiante aprenda a leer resultados reales —incluidos los contraintuitivos— y traducirlos en una recomendación de negocio.

## 🎯 Objetivos del curso

Al finalizar el curso, el estudiante va a poder:

- Implementar y evaluar críticamente modelos de aprendizaje de máquina en contextos de negocio reales (forecasting, clasificación, NLP, sistemas de recomendación).
- Elegir la métrica correcta según el problema — y explicar por qué RMSE, F1-macro o Precision@K no siempre cuentan la misma historia.
- Detectar errores metodológicos comunes en reportes de Data Science (evaluación in-sample, sesgo de exclusión, métricas mal elegidas) — la mitad de las tareas del curso son justamente sobre encontrar esos errores en reportes ficticios de "la competencia".
- Comunicar resultados técnicos como una recomendación ejecutiva con impacto de negocio cuantificado.

## 📅 Estructura por semana

| Semana | Caso | Tema técnico |
|---|---|---|
| [1](#semana-1--forecasting) | InvestAR Capital | Forecasting: SES, Holt, ARIMA, XGBoost, Prophet |
| [2](#semana-2--árboles-random-forest-y-gradient-boosting) | Hospital San Martín | Árboles de Decisión, Random Forest, Gradient Boosting |
| [3](#semana-3--análisis-de-sentimientos) | MercadoVoz | NLP: VADER, TF-IDF, DistilBERT |
| [4](#semana-4--sistemas-de-recomendación) | StreamAR / ModaIA | Filtrado Colaborativo, SVD, Sistemas Híbridos |

Cada carpeta `semanaX/` sigue la misma lógica interna:

- **Notebook de encuentro** — la clase completa, con outputs reales.
- **Guía de lectura** — el marco teórico (papers y capítulos de referencia), sin resultados de corridas específicas.
- **Tarea 1** — notebook grupal: el mismo pipeline de la clase, aplicado a un caso o subconjunto propio.
- **Tarea 2** — análisis crítico de un reporte ficticio con errores metodológicos deliberados.
- **Examen** — cuestionario de opción múltiple sobre el caso de la semana.

---

## Semana 1 — Forecasting

**Caso:** InvestAR Capital · **Modelos:** SES, Holt, OLS, ARIMA, XGBoost, Prophet

| Archivo | Descripción |
|---|---|
| `Notebook_semana1.ipynb` | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Luis-Eduardo-P-Ch/udla-bigdata-negocios/blob/main/semana1/Notebook_semana1.ipynb) Notebook de la clase |
| `Guia_Lectura_Encuentro1.html` | Guía de lectura teórica |
| `tarea1_semana1.ipynb` | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Luis-Eduardo-P-Ch/udla-bigdata-negocios/blob/main/semana1/tarea1_semana1.ipynb) Tarea 1 — Notebook grupal |
| `indicaciones_tarea1_semana1.docx` | Indicaciones de la Tarea 1 |
| `tarea2_semana1.docx` | Tarea 2 — Análisis crítico de reporte |
| `indicaciones_tarea2_semana1.docx` | Indicaciones de la Tarea 2 |
| `Semana1_Examen.docx` | Examen |

> ⚠️ Carpeta pendiente de completar — ver `semana1/NOTA.md`.

---

## Semana 2 — Árboles, Random Forest y Gradient Boosting

**Caso:** Hospital San Martín · **Modelos:** Árbol de Decisión, Random Forest, Gradient Boosting / XGBoost

| Archivo | Descripción |
|---|---|
| `Notebook_semana2.ipynb` | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Luis-Eduardo-P-Ch/udla-bigdata-negocios/blob/main/semana2/Notebook_semana2.ipynb) Notebook de la clase |
| `Guia_Lectura_Encuentro2.html` | Guía de lectura teórica |
| `tarea1_semana2.ipynb` | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Luis-Eduardo-P-Ch/udla-bigdata-negocios/blob/main/semana2/tarea1_semana2.ipynb) Tarea 1 — Notebook grupal |
| `indicaciones_tarea1_semana2.docx` | Indicaciones de la Tarea 1 |
| `tarea2_semana2.docx` | Tarea 2 — Caso Hospital Regional del Norte |
| `indicaciones_tarea2_semana2.docx` | Indicaciones de la Tarea 2 |
| `Semana2_Examen.docx` | Examen |

> ⚠️ Carpeta pendiente de completar — ver `semana2/NOTA.md`.

---

## Semana 3 — Análisis de Sentimientos

**Caso:** MercadoVoz (análisis de sentimientos para e-commerce) · **Modelos:** VADER, TF-IDF + Regresión Logística / Naive Bayes, DistilBERT

| Archivo | Descripción |
|---|---|
| `Notebook_semana3_sentiment_analysis.ipynb` | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Luis-Eduardo-P-Ch/udla-bigdata-negocios/blob/main/semana3/Notebook_semana3_sentiment_analysis.ipynb) Notebook de la clase |
| `Guia_Lectura_Encuentro3_Sentimientos.html` | Guía de lectura teórica (NLTK, VADER, BERT) |
| `tarea1_semana3_sentimientos.ipynb` | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Luis-Eduardo-P-Ch/udla-bigdata-negocios/blob/main/semana3/tarea1_semana3_sentimientos.ipynb) Tarea 1 — Notebook grupal por categoría de producto |
| `indicaciones_tarea1_semana3.docx` | Indicaciones de la Tarea 1 |
| `tarea1_semana3.docx` | Tarea 1 — versión imprimible |
| `tarea2_semana3_analisis_reporte.html` | Tarea 2 — Caso RetailBI Analytics (interactivo) |
| `tarea2_semana3.docx` | Tarea 2 — versión imprimible |
| `indicaciones_tarea2_semana3.docx` | Indicaciones de la Tarea 2 |
| `Semana3_Examen.docx` | Examen |

> ⚠️ Falta `Semana3_Examen.docx` — no estaba disponible en esta sesión de trabajo.

---

## Semana 4 — Sistemas de Recomendación

**Caso:** StreamAR (streaming) y ModaIA (e-commerce de moda) · **Modelos:** User/Item-Based CF, SVD, Content-Based, Sistema Híbrido Adaptativo

| Archivo | Descripción |
|---|---|
| `Notebook_recomendaciones_StreamAR.ipynb` | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Luis-Eduardo-P-Ch/udla-bigdata-negocios/blob/main/semana4/Notebook_recomendaciones_StreamAR.ipynb) Notebook de la clase |
| `Guia_Lectura_Encuentro4_Recomendacion.html` | Guía de lectura teórica (Ricci, Koren, Leskovec, Covington) |
| `tarea1_semana4_recomendaciones.ipynb` | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Luis-Eduardo-P-Ch/udla-bigdata-negocios/blob/main/semana4/tarea1_semana4_recomendaciones.ipynb) Tarea 1 — Notebook grupal por dominio |
| `indicaciones_tarea1_semana4.docx` | Indicaciones de la Tarea 1 |
| `tarea1_semana4.docx` | Tarea 1 — versión imprimible |
| `tarea2_semana4_analisis_reporte.html` | Tarea 2 — Caso ModaIA (interactivo) |
| `tarea2_semana4.docx` | Tarea 2 — versión imprimible |
| `indicaciones_tarea2_semana4.docx` | Indicaciones de la Tarea 2 |
| `Semana4_Examen.docx` | Examen |

> ⚠️ `Guia_Lectura_Encuentro4_Recomendacion.html` tiene una corrección pendiente de confirmar (ver `TODO.md`).

---

*Big Data Aplicada a los Negocios · UDLA · Material preparado por el equipo docente*
