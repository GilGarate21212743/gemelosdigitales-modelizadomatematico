[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=GilGarate21212743/gemelosdigitales-regresionnolineal)

# Gemelos Digitales. Práctica 3: Algoritmos de Regresión No Lineal [GilGarate-21212743]

## Autor
Gil Gárate Carlos Andrés 

Ingeniería Biomédica, Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: l21212743@tectijuana.edu.mx

## Resumen de la práctica
Esta práctica tiene como objetivo construir y analizar un modelo mecanicista basado en ecuaciones diferenciales de primer orden para describir la dinámica entre dos variables biológicas. Se busca ajustar los parámetros del modelo mediante algoritmos de regresión no lineal y evaluar su capacidad predictiva con base en datos experimentales.

Para ello, se inicia con la carga de un conjunto de datos experimentales almacenados en un archivo CSV, donde se encuentran las mediciones de tiempo y las variables de interés. Posteriormente, se plantea un modelo matemático que considera un comportamiento sigmoidal y una capacidad de carga máxima para la variable dependiente. El modelo es ajustado utilizando varias leyes de crecimiento no lineales que reflejan distintos tipos de dinámicas biológicas. Se emplean algoritmos de regresión no lineal, como el basado en la ley de crecimiento logístico, que modela el crecimiento limitado de una población o sistema. Además, se utiliza la ley de crecimiento alométrico esférico, que es adecuada para sistemas con geometría esférica, y la ley de crecimiento alométrico fractal, que describe el crecimiento en sistemas con estructuras fractales. También se incorpora la ley de crecimiento de Gompertz, muy útil en el modelado del crecimiento de poblaciones y tumores, así como su versión simplificada para obtener un modelo más accesible.

Cada uno de estos algoritmos se implementa para ajustar los parámetros del modelo y minimizar la diferencia entre los valores modelados y los datos experimentales. Finalmente, se evalúa el ajuste del modelo mediante métricas estadísticas y visualización gráfica, con el fin de validar su capacidad predictiva y su aplicabilidad en la descripción de los datos biológicos analizados.

## Objetivos específicos
1. Cargar y preprocesar los datos experimentales.
2. Desarrollar un modelo matemático basado en ecuaciones diferenciales de primer orden.
3. Ajustar los parámetros del modelo utilizando algoritmos de regresión no lineal.
4. Evaluar la capacidad predictiva del modelo.
5. Visualizar y validar el ajuste del modelo.

## Docente
Dr. Paul A. Valle

Posgrado en Ciencias de la Ingeniería [PCI] y Departamento de Ingeniería Eléctrica y Electrónica [DIEE], Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: paul.valle@tectijuana.edu.mx

## Lecturas
[1] Paul. A. Valle, Syllabus de Biomatemáticas para la asignatura de Gemelos Digitales, Tecnológico Nacional de México/IT Tijuana, Tijuana, B.C., México, 2025. Permalink: https://www.dropbox.com/s/6yf9afxzih9y458/Biomatematicas.pdf
