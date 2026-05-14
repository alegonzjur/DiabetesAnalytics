
# 🩺 Diabetes Analytics Dashboard

`![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)`

`![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)`

`![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-20BEFF?style=flat&logo=kaggle&logoColor=white)`

`![License](https://img.shields.io/badge/License-GPL--3.0-green?style=flat)`

## [Dataset](https://www.kaggle.com/datasets/aryanpatel0204/diabetes-dashboard-power-bi)

Dashboard interactivo desarrollado con Power BI para el análisis exploratorio del dataset **Pima Indians Diabetes**. El objetivo es identificar los principales factores de riesgo asociados a la diabetes tipo 2 en una población específica de mujeres adultas, apoyando la comprensión clínica y epidemiológica de la enfermedad.

![DemostraciónDashboard](image/dashboard.gif)

---

## 📋 Tabla de contenidos

- [Contexto clínico](#-contexto-clínico)
- [Dataset](#-dataset)
- [Preguntas analíticas](#-preguntas-analíticas)
- [Estructura del dashboard](#-estructura-del-dashboard)
- [Principales hallazgos](#-principales-hallazgos)
- [Decisiones de diseño](#-decisiones-de-diseño)
- [Estructura del repositorio](#-estructura-del-repositorio)
- [Tecnologías utilizadas](#-tecnologías-utilizadas)
- [Mejoras futuras](#-mejoras-futuras)

---

## 🏥 Contexto clínico

La diabetes de tipo 2 es una de las enfermedades crónicas más prevalentes a nivel mundial. con especial incidencia en poblaciones con predisposición genética y determinadas condiciones metabólicas. El dataset *Pima Indians Diabetes* ha sido recopilado por el Instituto Nacional de Diabetes y Enfermedades Digestivas y Renales de Estados Unidos. Registra variables clínicas de 768 mujeres de ascendencia PIMA con al menos 21 años de edad.

Este proyecto aborda el análisis desde una perspectiva descriptiva y exploratoria, buscando responder preguntas clínicamente relevantes sobre los factores que más se asocian al diagnóstico positivo.

---

## 📊 Dataset

**Fuente:** [Kaggle - Diabetes PIME](https://www.kaggle.com/datasets/aryanpatel0204/diabetes-dashboard-power-bi)

| Variable                   | Descripción                                                                           |
| -------------------------- | ------------------------------------------------------------------------------------- |
| `Age`                      | Edad en años                                                                          |
| `Pregnancies`              | Número de embarazos                                                                   |
| `Glucose`                  | Concentración de glucosa en plasma (mg/Dl) a las dos horas en test oral de tolerancia |
| `BloodPressure (mg/Dl)`    | Presión arterial diastólica (mm/Hg)                                                   |
| `SkinThickness`            | Grosor del pliegue cutáneo del tríceps (mm)                                           |
| `Insulin`                  | Nivel de insulina sérica a las 2 horas(mu U/ml)                                       |
| `BMI`                      | Índice de masa corporal                                                               |
| `DiabetesPedigreeFunction` | Puntuación de predisposición genética a la diabetes                                   |
| `Outcome`                  | Diagnóstico (1 = diabetes, 0 = sin diabetes)                                          |

---

## ❓ Preguntas analíticas

Antes de construir el dashboard, se plantearon las siguientes preguntas que guiaron el análisis:

1. ¿Cuál es la prevalencia de diabetes en esta población?

2. ¿En qué grupo de edad se concentra el mayor número de casos?

3. ¿Qué relación existe entre el IMC y los niveles de glucosa con el diagnóstico?

4. ¿Cómo influye el número de embarazos en la distribución de casos?

5. ¿Qué categorías de presión arterial e IMC presentan mayor recuento de diabetes?

6. ¿Existen diferencias clínicas relevantes entre grupos de edad?

---

## 📐 Estructura del dashboard

El dashboard se organiza en tres páginas interconectadas mediante la barra de navegación superior:

### Resumen Ejecutivo

Vista general de la población: métricas clave (total de pacientes, edad media, embarazos medios, riesgo promedio), distribución de diagnósticos, distribución por grupos de edad, y distribuciones de presiones arterial y glucosa.

![ExecutiveSummary]()


