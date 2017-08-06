---
layout: P-Post
title: Equilibrio de ácidos y bases débiles
date: 2017-02-13 20:00:00
author: rivel_co
tags: [pH, pKa]
universidad: [Semestre-2, Parcial-1]
olimpiada: [ONB, ONQ]
subject: [Bioquímica]
---

Se pueden definir los ácidos como dadores de protones y las bases como aceptores de protones. Un dador de protón y su correspondiente aceptor forman un ***par ácido-base conjugado***. 

Cada ácido tiene una tendencia característica a perder su protón en disolución acuosa. Cuanto más fuerte sea el ácido mayor será la tendencia a perder su protón. La tendencia de cualquier ácido (HA) a perder un protón y formar su base conjugada (A<sup>-</sup>) se define mediante la constante de equilibrio (K<sub>eq</sub>) para la reacción reversible:

$$
HA \rightleftharpoons H^+ + A^-
$$

Para la que

$$
K_{eq} = \frac{[H^+][A^-]}{[HA]} = K_a
$$

Las constantes de equilibrio de las reacciones de ionización se suelen denominar ***constantes de ionización*** o ***constantes ácidas de disociación***, a menudo designadas como K<sub>a</sub>.

La expresión de ***pK<sub>a</sub>*** es análoga a la de pH por lo que se define mediante la ecuación:

$$
\begin{align}
pK_a & = log\frac{1}{K_a}
& = -log K_a
\end{align}
$$

Cuanto más fuerte sea la tendencia a disociar un protón más fuerte es el ácido y menor es su pK<sub>a</sub>.

## Curvas de titulación

La titulación se usa para determinar la cantidad de un ácido en una disolución dada. Un volumen determinado de ácido se titula con una disolución de concentración conocida de una base fuerte, normalmente hidróxido sódico (NaOH). Se añade NaOH en pequeñas cantidades hasta que se ha consumido (neutralizado) el ácido según se determina mediante un colorante indicador o con un aparato medidor de pH. Se puede calcular la concentración de ácido en la disolución original a partir del volumen y la concentración de NaOH obtenido.

De la gráfica que representa el pH frente a la cantidad de NaOH añadido (***curva de titulación***) se deduce el pK<sub>a</sub> del ácido débil.

Curva de titulación del ácido acético:

[![Curva de titulación ácido acético]({{ site.iP-Sources }}/Multimedia/Apuntes/BQB/CTAac.jpg")]({{ site.iP-Sources }}/Multimedia/Apuntes/BQB/CTAac.jpg){: data-lightbox="image-1"}

## Amortiguamiento contra cambios de pH

Casi todos los procesos biológicos son dependientes del pH, un pequeño cambio en el pH induce un gran cambio en la velocidad del proceso. Esto no sólo es cierto para muchas de las reacciones en las que el ión H<sup>+</sup> es un participante directo, sino también para aquellas en las que aparentemente no juegan ningún papel.

Las enzimas que catalizan las reacciones celulares y muchas de las moléculas sobre las que actúan, contienen grupos ionizables con valores de pK<sub>a</sub> característicos. Los grupos amino y carboxilo protonados de los aminoácidos y el grupo fosfato de los nucleótidos, por ejemplo, funcionan como ácidos débiles, su estado iónico depende del pH del medio que los rodea.

Las células y organismos mantienen un pH citosólico específico y constante, normalmente cerca de pH 7, que mantiene las biomoléculas en su estado iónico óptimo. El pH se mantiene constante principalmente gracias a los amortiguadores biológicos, que son mezclas de ácidos débiles y de sus bases conjugadas.

## Los amortiguadores son mezclas de ácidos débiles y sus bases conjugadas

Amortiguadores de pH
 : Sistemas acuosos que tienden a resistir cambios en su pH cuando se añaden pequeñas cantidades de ácido (H<sup>+</sup>) o base (OH<sup>-</sup>).
 : Consiste en un ácido débil (dador de protones) y su base conjugada (aceptor de protones).

Analizando la curva de titulación del ácido acético, es fácil notar que tiene una zona relativamente plana que se extiende alrededor de 1 unidad de pH a cada lado del pH de su punto medio. Dentro de esa zona una cierta cantidad de H<sup>+</sup> o OH<sup>-</sup> añadida al sistema tiene un efecto mucho menor sobre el pH que la misma cantidad añadida fuera de ella.

Esta zona relativamente plana es la ***región de amortiguamiento*** del par acético-acetato.

## Ecuación de Henderson-Hasselbalch

La curva de titulación de cualquier ácido débil está expresada por la ecuación de Henderson-Hsselbalch, que es importante para comprender la acción de los amortiguadores y el equilibrio ácido-base en la sangre y tejidos de los vertebrados.

En el caso de la ionización de un ácido débil HA, la ecuación de Henderson-Hasselbalch puede deducirse de la siguiente forma:

$$
K_a = \frac{[H^+][A^-]}{[HA]}
$$

Despejando primero [H<sup>+</sup>]:

$$
[H^+] = K_a \frac{[HA]}{[A^-]}
$$

Tomando el logaritmo negativo en ambos lados de la igualdad:

$$
-log [H^+] = -log K_a - log\frac{[HA]}{[A^-]}
$$

Sustituyendo los -log[H<sup>+</sup>] por pH y -log[K<sub>a</sub>] por pK<sub>a</sub>:

$$
pH = pK_a - log\frac{[HA]}{[A]}
$$

Invirtiendo ahora -log[HA]/[A<sup>-</sup>], lo que implica un cambio de signo, se obtiene la ***ecuación de Henderson-Hasselbalch***:

$$
pH = pK_a + log\frac{[A^-]}{[HA]}
$$

Esta ecuación se ajusta a la curva de titulación de todos los ácidos débiles y nos permite deducir una serie de relaciones cuantitativas importantes, por ejemplo, muestra por qué el pK<sub>a</sub> de un ácido débil es igual al pH de la solución en el punto medio de su titulación, en ese punto [HA] = [A^-] y de ahí:
$$
\begin{align}
pH & = pK_a + log\frac{[A^-]}{[HA]}
& = pK_a + log 1
& = pK_a + 0
& = pK_a
\end{align}
$$

La ecuación de Henderson-Hasselbalch también permite:

- Calcular el pK<sub>a</sub> a partir del pH y la relación molar entre dador y aceptor de protones.
- Calcular el pH a partir del pK<sub>a</sub> y la relación molar entre dador y aceptor de protones.
- Calcular la relación molar entre dador y aceptor de protones conocidos el pH y el pK<sub>a</sub>.

