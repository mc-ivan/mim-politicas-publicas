![banner](mod14-banner.png)

# Trabajo Final - Evaluación de Políticas Públicas

Este repositorio contiene el desarrollo completo del **Trabajo Final del Módulo 14: Modelos para Análisis Cuantitativo de Políticas Públicas**, correspondiente a la **Maestría en Ingeniería Matemática**.

En este trabajo se aplican metodologías econométricas avanzadas para la **evaluación causal de intervenciones públicas**, combinando modelos estructurales y técnicas de identificación cuasi-experimental.

## 🎯 **Objetivo**

Analizar el impacto de programas públicos mediante herramientas cuantitativas, respondiendo a preguntas clave de política pública:

- ¿Qué factores explican la participación en un programa?
- ¿Cuál es el impacto de una intervención sobre resultados relevantes?
- ¿Cómo influye la intensidad del tratamiento?
- ¿Es posible identificar efectos causales en contextos no experimentales?

## 📚 **Contenido del trabajo**

El proyecto está dividido en dos partes principales:

### Parte 1: Programa de prevención del abandono escolar

Se analiza un programa orientado a reducir la deserción en estudiantes de secundaria mediante:

- Tutorías personalizadas  
- Seguimiento familiar  
- Apoyo académico  

#### Métodos aplicados:

- **Modelo Logit (MLE)**  
  Identificación de determinantes de participación

- **Análisis de supervivencia (Kaplan-Meier)**  
  Evaluación del tiempo hasta el abandono

- **Heterogeneidad por intensidad**  
  Análisis del efecto de distintos niveles de intervención

#### Objetivos específicos:

- Explicar la participación en el programa  
- Evaluar la permanencia en el sistema educativo  
- Analizar si mayor intensidad reduce el abandono  

### Parte 2: Programa "Salud Mayor" (Fuzzy RDD)

Se evalúa un programa de salud preventiva dirigido a adultos mayores, cuya elegibilidad depende de la edad (65 años), pero con cumplimiento imperfecto.

#### Métodos aplicados:

- **Regresión Discontinua Difusa (Fuzzy RDD)**  
- **Variables Instrumentales (2SLS)**  
- **Pruebas de robustez (Placebo Cut-off Test)**  

#### Objetivos específicos:

- Validar la existencia de discontinuidad en el tratamiento  
- Estimar el efecto causal del programa sobre la salud  
- Evaluar la robustez del diseño  

## 📗 **Notebooks**

Los análisis fueron desarrollados en Google Colab:

### 1. Prevención del abandono escolar

Aplicación de modelos estructurales para analizar participación, permanencia y efectos de intensidad del tratamiento.

[![Open In Colab](https://img.shields.io/badge/Open%20in-Colab-F9AB00?logo=googlecolab&logoColor=white)](https://colab.research.google.com/github/mc-ivan/mim-politicas-publicas/blob/main/notebooks/1_PrevencionAbandonoEscolar.ipynb)

### 2. Salud Mayor — Fuzzy RDD

Evaluación causal mediante regresión discontinua difusa y variables instrumentales.

[![Open In Colab](https://img.shields.io/badge/Open%20in-Colab-F9AB00?logo=googlecolab&logoColor=white)](https://colab.research.google.com/github/mc-ivan/mim-politicas-publicas/blob/main/notebooks/2_SaludMayor_FuzzyRDD.ipynb)


## 📄 **Documento final**

El informe completo del trabajo se encuentra en:

📄 **TrabajoFinal-Grupal.pdf**

[![View PDF](https://img.shields.io/badge/Ver-Informe_PDF-red?logo=adobeacrobatreader&logoColor=white)](TrabajoFinal-Grupal.pdf)

Incluye:

- Resultados  
- Indicadores  
- Gráficos  
- Interpretaciones  
- Conclusiones por ejercicio  

## 🧠 Metodologías utilizadas

- Modelos de elección discreta (Logit)  
- Análisis de supervivencia  
- Regresión discontinua difusa (RDD)  
- Variables instrumentales (2SLS)  
- Evaluación de impacto causal  

## ⚙️ Herramientas

- Python  
- Google Colab  
- Pandas  
- NumPy  
- Statsmodels  
- Matplotlib / Seaborn  

## Autores

- Ivan Mamani  
- Giovanni Ortis  
- Gimena Javier  

## 📌 Notas finales

Este repositorio busca no solo presentar resultados, sino también demostrar la aplicación de metodologías rigurosas para la evaluación de políticas públicas en contextos reales, donde los datos observacionales requieren enfoques de identificación causal.
