[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=GilGarate21212743/gemelosdigitales-regresionnolineal)

# Gemelos Digitales. Práctica 4: Modelizado Matemático [GilGarate-21212743]

## Autor
Gil Gárate Carlos Andrés 

Ingeniería Biomédica, Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: l21212743@tectijuana.edu.mx

## Resumen de la práctica
Esta práctica tiene como objetivo construir y analizar un modelo mecanicista basado en ecuaciones de Lotka-Volterra para estudiar la dinámica competitiva entre dos poblaciones biológicas: células tumorales (NT) y células normales (NN). Se emplean técnicas de regresión no lineal para ajustar los parámetros del modelo a datos experimentales, seguido de un análisis cualitativo de estabilidad mediante la evaluación de puntos de equilibrio y propiedades del Jacobiano.

El proceso inicia con la carga de datos experimentales que registran la evolución temporal de ambas poblaciones. Posteriormente, se implementa un algoritmo de regresión no lineal para estimar parámetros clave del modelo, como tasas de crecimiento (rho1, rho2), coeficientes de interacción (gamma1, gamma2) y capacidad de carga (beta). Con los parámetros ajustados, se calculan los puntos de equilibrio del sistema y se analiza su estabilidad local mediante los autovalores del Jacobiano. Finalmente, se visualizan los datos experimentales, las curvas ajustadas del modelo y la ubicación de los puntos de equilibrio, validando la concordancia entre las predicciones teóricas y los datos observados.

## Objetivos específicos
1. Cargar y procesar datos experimentales de series temporales que describen la dinámica de dos poblaciones celulares.
2. Formular el modelo de Lotka-Volterra para representar la interacción competitiva entre células tumorales y normales, incorporando términos de crecimiento y competencia.
3. Ajustar los parámetros del modelo mediante algoritmos de regresión no lineal, utilizando métodos numéricos como Runge-Kutta de segundo orden para resolver las ecuaciones diferenciales.
4. Determinar los puntos de equilibrio del sistema y evaluar su estabilidad local a través del cálculo del Jacobiano y sus valores propios.
5. Visualizar los resultados incluyendo datos experimentales, curvas ajustadas del modelo, y la ubicación de puntos de equilibrio en gráficos interpretables.

## Docente
Dr. Paul A. Valle

Posgrado en Ciencias de la Ingeniería [PCI] y Departamento de Ingeniería Eléctrica y Electrónica [DIEE], Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: paul.valle@tectijuana.edu.mx

## Lecturas
[1] Paul. A. Valle, Syllabus de Biomatemáticas para la asignatura de Gemelos Digitales, Tecnológico Nacional de México/IT Tijuana, Tijuana, B.C., México, 2025. Permalink: https://www.dropbox.com/s/6yf9afxzih9y458/Biomatematicas.pdf
[2] Dominik Wordaz & Natalia L. Komarova, Dynamics of Cancer: Mathematical Foundations of Oncology, University of California, Irvine, USA, 2014.
[3] Robert A. Gatenby & Thomas L. Vincent, "Application of quantitative models from population biology and evolutionary game theory to tumor therapeutic strategies," Molecular Cancer Therapeutics, vol. 2, no. 9, pp. 919–927, Jun 2003.
