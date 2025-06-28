Optimización y Visualización de Funciones Multivariables
(Google Colab / Jupyter Notebook)

Este proyecto presenta el análisis simbólico y visual de funciones de dos variables utilizando Python, con enfoque en el cálculo de derivadas parciales, gradiente, matriz Hessiana y visualización de puntos críticos.

La ejecución está diseñada para entornos interactivos como Google Colab o Jupyter Notebook, donde cada bloque de código se acompaña de comentarios y visualizaciones dinámicas (incluyendo animaciones 3D).

Objetivo
Aplicar herramientas del cálculo diferencial multivariable para analizar funciones de dos variables y comprender cómo estos conceptos se aplican a problemas de optimización, incluyendo su conexión con técnicas de Machine Learning.

Contenido del Notebook
Definición simbólica de la función
Ejemplo:

𝑔
(
𝑥
,
𝑦
)
=
𝑥
2
+
3
𝑦
2
−
4
𝑥
+
2
𝑦
+
1
g(x,y)=x 
2
 +3y 
2
 −4x+2y+1
Cálculo del gradiente y matriz Hessiana

Derivadas parciales:
∂
𝑔
∂
𝑥
,
∂
𝑔
∂
𝑦
∂x
∂g
​
 , 
∂y
∂g
​
 

Gradiente: 
∇
𝑔
(
𝑥
,
𝑦
)
∇g(x,y)

Matriz Hessiana:

𝐻
𝑔
(
𝑥
,
𝑦
)
=
[
∂
2
𝑔
∂
𝑥
2
∂
2
𝑔
∂
𝑥
∂
𝑦
∂
2
𝑔
∂
𝑦
∂
𝑥
∂
2
𝑔
∂
𝑦
2
]
H 
g
​
 (x,y)=[ 
∂x 
2
 
∂ 
2
 g
​
 
∂y∂x
∂ 
2
 g
​
 
​
  
∂x∂y
∂ 
2
 g
​
 
∂y 
2
 
∂ 
2
 g
​
 
​
 ]
Determinación y clasificación de puntos críticos

Se resuelve 
∇
𝑔
=
(
0
,
0
)
∇g=(0,0)

Se evalúan los valores propios de la matriz Hessiana para clasificar los puntos:

Mínimo local

Máximo local

Punto de silla

Visualización de resultados

Superficie 3D de la función con el punto crítico marcado

Mapa de contorno (2D)

Animación rotatoria 3D del gráfico usando matplotlib.animation (para mejor comprensión geométrica)

Discusión: Conexión con Machine Learning

El cálculo del gradiente es la base del descenso de gradiente, el algoritmo más común para minimizar funciones de pérdida en el entrenamiento de modelos.

El análisis del comportamiento local mediante la Hessiana permite entender la curvatura de la superficie y la convergencia del modelo.

Requisitos
Este proyecto se ejecuta en Google Colab o Jupyter Notebook.
Bibliotecas necesarias (pueden instalarse vía pip si es necesario):

bash
Copiar
Editar
pip install sympy numpy matplotlib ipython
¿Cómo usar este código?
Abre el notebook en Google Colab.

Ejecuta cada celda de código secuencialmente.

Observa los resultados simbólicos, los gráficos y la animación rotatoria generada.

Capturas sugeridas (para documentación)
Gradiente simbólico y Hessiana

Evaluación en el punto crítico

Clasificación automática basada en valores propios

Visualización 3D con punto crítico marcado

Animación 3D rotatoria

Autor
Julián Gómez Brizuela
Miembro fundador del Proyecto Fénix, junto al Sr. Pikerton
🧠 Explorador de ideas, calculadora simbólica humana, amante del jurel y de los relojes retro.
