---
layout: P-Post
title: Interacciones moleculares
date: 2017-02-14 18:00:00
author: rivel_co
tags: [Gases]
universidad: [Semestre-2, Parcial-1]
olimpiada: [ONB, ONQ, ONF]
subject: [Fisicoquímica biológica]
---

Los gases reales muestran desviaciones de la ley del gas ideal porque las moléculas interactúan unas con otras. Las fuerzas repulsivas entre moléculas intervienen en las expansiones y las atracciones en las compresiones.

## Influencia de las fuerzas moleculares

### Bajas presiones

La muestra ocupa un gran volumen, las moléculas están tan alejadas entre sí la mayoría del tiempo que las fuerzas intermoleculares no juegan un papel significativo, y el gas se comporta como un gas ideal.

### Presiones moderadas

La separación media de las moléculas es sólo unos pocos diámetros moleculares, las fuerzas atractivas dominan a las fuerzas repulsivas. En este caso, se espera que el gas sea más compresible que un gas ideal, porque las fuerzas ayudan a mantener las moléculas juntas.

### Presiones altas

La separación media de las moléculas es pequeña, las fuerzas repulsivas son dominantes y se espera que el gas sea menos compresible porque las fuerzas tienden a separar las moléculas.

## Factor de compresión

El factor de compresión $$ Z $$ de un gas, es el cociente entre su volumen molar medido $$ V_m = \frac{V}{\eta} $$ y el volumen molar de un gas ideal $$ V_m^\degree $$ a la misma presión y temperatura.

$$ Z = \frac{V_m}{V_m^\degree} $$

Dado que el volumen molar de un gas ideal es igual a $$ \frac{RT}{p} $$, podemos decir que:

$$
\begin{align}
Z & = \frac{V_m}{V_m^\degree} \\
  & = \frac{V_m}{\frac{RT}{p}}
  & = \frac{pV_m}{RT}
\end{align}
$$

Como para un gas ideal $$ Z = 1 $$ bajo cualquier condición, las desviaciones de $$ Z $$ del valor 1 constituyen una medida del apartamiento del comportamiento ideal.

De manera general, podemos decir que:

- A muy bajas presiones: Todos los gases tienen $$ Z = 1 $$ y se comportan casi como gases ideales.
- A altas presiones, todos los gases poseen $$ Z > 1 $$, lo que significa que poseen un volumen molar mayor que el de un gas ideal. Las fuerzas repulsivas en este caso son dominantes.
- A presiones intermedias, la mayoría de los gases tienen $$ Z < 1 $$ lo que significa que las fuerzas atractivas reducen el volumen molar por debajo del volumen de un gas ideal.

## Coeficientes del viral

Para mayores volúmenes molares y altas temperaturas, las isotermas del gas real no difieren en gran medida de las isotermas del gas ideal. Las pequeñas diferencias sugieren que la ley del gas ideal es de hecho el primer término de una expresión de la forma:

$$
PV_m = RT(1 + B'p + C'p^2 + \dotso)
$$

Esta expresión es un ejemplo de un procedimiento común en fisicoquímica, en el cual, una ley simple que es conocida como una buena primera aproximación (en este caso $$ pV_m = \eta RT) es considerada como en el primer término en una serie de potencias de una variable (en este caso $$ p $$). Una expresión más conveniente para muchas aplicaciones es:

$$
pV_m = RT(1 + \frac{B}{V_m} + \frac{C}{V_m^2} + \dotso)
$$

Estas dos expresiones son dos versiones de la ecuación de ***estado del virial***. Podemos ver que el término entre paréntesis puede ser identificado con el factor de compresión $$ Z $$.

Los coeficientes $$ B, C, ... $$ los cuales dependen de la temperatura, son el segundo, el tercero, ... ***coeficientes del virial***

## Ecuación del estado de van del Waals

Para sacar conclusiones de las ecuaciones de estado del virial es suficiente con especificar los coeficientes. Pero a menudo resulta útil tener una visión más amplia, aunque menos precisa de todos los gases, de modo que introducimos la ecuación de estado aproximada sugerida por J. D. van der Waals en 1873.

La ***ecuación de van der Waals*** es:

$$
p = \frac{\eta RT}{V - \eta b} - a(\frac{\eta}{V})^2
$$

A partir de esta podemos decir también que:

$$
(p + a \frac{\eta^2}{V^2})(V - \eta b) = \eta RT
$$

A menudo es escrita también en términos del volumen molar $$ V_m = \frac{V}{\eta} $$ como

$$
p = \frac{RT}{V_m - b} - \frac{a}{V_m^2}
$$

Las constantes $$ a $$ y $$ b $$ son llamadas los coeficientes de ***van der Waals***. Estos son característicos de cada gas, pero dependientes de la temperatura.

Tenemos a $$ a $$ en términos de $$ \frac{atmL^2}{\eta} $$ y a $$ b $$ en términos de $$ \frac{L}{\eta} $$.

En la ecuación segunda, podemos analizar la siguiente parte como sigue:

$$
a \frac{\eta^2}{V^2}
$$

> Reducción de la presión debida a la fuerza de atracción intermolecular

Y de la segunda parte podemos decir que:

$$
(V - \eta b)
$$

> Volumen realmente ocupado por \eta moles de gas