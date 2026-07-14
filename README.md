# Algoritmos Bayesianos y de Reglas de Asociación

Este repositorio contiene una colección de notebooks de Jupyter que exploran distintos algoritmos relacionados con el aprendizaje automático, la estadística probabilística y la minería de datos. El proyecto está orientado a la comprensión práctica de métodos basados en el Teorema de Bayes, así como de técnicas de descubrimiento de patrones y reglas de asociación.

## Objetivo del proyecto

El propósito de este trabajo es mostrar, de forma didáctica y aplicada, cómo funcionan varios algoritmos importantes en el área de inteligencia artificial y análisis de datos. A través de notebooks interactivos, se presentan ejemplos, explicaciones conceptuales y pasos de implementación en Python.

## Contenido del repositorio

El proyecto incluye los siguientes notebooks:

- [naive_bayes/Algoritmo_naiveBayes.ipynb](naive_bayes/Algoritmo_naiveBayes.ipynb): implementación y explicación del algoritmo Naive Bayes para clasificación probabilística.
- [gaussian_naive_bayes/Gaussian_naiveBayes.ipynb](gaussian_naive_bayes/Gaussian_naiveBayes.ipynb): aplicación de Gaussian Naive Bayes para variables continuas.
- [multinomial_naive_bayes/Multinominal_naiveBayes.ipynb](multinomial_naive_bayes/Multinominal_naiveBayes.ipynb): uso de Multinomial Naive Bayes, especialmente útil en problemas de texto y conteos.
- [aode/aode.ipynb](aode/aode.ipynb): implementación de AODE (Averaged One-Dependence Estimators), una extensión de los clasificadores bayesianos simples.
- [bayessian_network/bayesian_network.ipynb](bayessian_network/bayesian_network.ipynb): introducción a las redes bayesianas y su representación gráfica.
- [bayessian_belief_network/bayessianbeliefnetwork.ipynb](bayessian_belief_network/bayessianbeliefnetwork.ipynb): estudio de Bayesian Belief Networks, inferencia y aprendizaje de parámetros con herramientas como PGMPY.
- [apriori_algorithm/A_priori_Algorithm.ipynb](apriori_algorithm/A_priori_Algorithm.ipynb): algoritmo Apriori para encontrar itemsets frecuentes y reglas de asociación.
- [eclat_algorithm/eclat_algorithm.ipynb](eclat_algorithm/eclat_algorithm.ipynb): implementación del algoritmo Eclat para minería de reglas de asociación de forma más eficiente que Apriori en algunos casos.
- [fp_growth/fp_growth.ipynb](fp_growth/fp_growth.ipynb): explicación y uso de FP-Growth, un algoritmo muy eficiente para encontrar patrones frecuentes.

## Temas principales

Este conjunto de notebooks abarca dos grandes líneas de estudio:

1. Modelos probabilísticos bayesianos
   - Naive Bayes
   - Gaussian Naive Bayes
   - Multinomial Naive Bayes
   - AODE
   - Redes Bayesianas y Bayesian Belief Networks

2. Minería de reglas de asociación
   - Apriori
   - Eclat
   - FP-Growth

## Requisitos

Para ejecutar los notebooks se recomienda tener instalado:

- Python 3.x
- Jupyter Notebook o JupyterLab
- Bibliotecas como pandas, numpy, matplotlib, seaborn, scikit-learn, mlxtend, pgmpy y otras indicadas en cada notebook

## Cómo usar este repositorio

1. Clona el repositorio en tu máquina local.
2. Abre la carpeta en Jupyter Notebook o JupyterLab.
3. Ejecuta los notebooks en el orden que te resulte más cómodo, según el algoritmo que quieras estudiar.
4. Revisa las explicaciones, el código y los resultados generados en cada celda.

## Notas

Los notebooks están diseñados con un enfoque educativo, por lo que combinan teoría, implementación y ejemplos prácticos. Son ideales para estudiantes, investigadores y personas interesadas en aprender sobre métodos probabilísticos y minería de datos.

## Autoría

Proyecto desarrollado como parte de un trabajo académico en el contexto de maestría, con enfoque en algoritmos bayesianos y técnicas relacionadas de análisis de datos.
