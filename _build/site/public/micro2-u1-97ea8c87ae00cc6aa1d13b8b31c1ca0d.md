---
title: "U1: La preferencia revelada"
description: "Capitulo 7 de Varian: preferencia revelada, axiomas debil y fuerte, numeros indices e indices de precios"
---

# U1: La preferencia revelada (Capitulo 7)

```{tableofcontents}
```

## 1. La idea de preferencia revelada

Hasta ahora las preferencias eran datos del modelo. Varian invierte el enfoque: si observamos las elecciones de un consumidor, podemos **inferir** sus preferencias. La teoria de la **preferencia revelada** establece que condiciones deben cumplir los datos observados para ser consistentes con la maximizacion de utilidad.

```{admonition} Concepto clave
:class: tip
Si un consumidor elige la cesta $(x_1,x_2)$ cuando podia comprar $(y_1,y_2)$, decimos que $(x_1,x_2)$ es **revelada preferida** a $(y_1,y_2)$. La eleccion revela informacion sobre las preferencias.
```

## 2. Preferencia revelada directa

La cesta $(x_1,x_2)$ es **revelada directamente preferida** a $(y_1,y_2)$ cuando:

$$
p_1 x_1 + p_2 x_2 \geq p_1 y_1 + p_2 y_2
$$

es decir, $(y_1,y_2)$ estaba dentro del conjunto presupuestario cuando se eligio $(x_1,x_2)$.

## 3. El axioma debil de la preferencia revelada

```{admonition} Axioma debil (WARP)
:class: tip
Si $(x_1,x_2)$ es revelada directamente preferida a $(y_1,y_2)$ y las cestas son distintas, entonces $(y_1,y_2)$ no puede ser revelada directamente preferida a $(x_1,x_2)$.
```

Formalmente: si $px \geq py$ y $py \geq px$ con $x \neq y$, el comportamiento viola WARP y no puede provenir de la maximizacion de unas preferencias transitivas.

## 4. Preferencia revelada indirecta y axioma fuerte

La cesta $x$ es **revelada indirectamente preferida** a $z$ si existe una cadena $x \to y \to z$ donde cada eslabon es una preferencia revelada directa.

```{admonition} Axioma fuerte (SARP)
:class: tip
Es imposible que $x$ sea revelada (directa o indirectamente) preferida a $z$ y a la vez $z$ sea revelada (directa o indirectamente) preferida a $x$, siendo $x \neq z$.
```

El axioma fuerte equivale a que la demanda sea consistente con la maximizacion de unas preferencias convexas monotonas. Ademas implica la ley de la demanda compensada: si se compensa al consumidor para mantener su utilidad, una subida de precio reduce la cantidad demandada.

## 5. Reconstruir las curvas de indiferencia

Observando suficientes elecciones a distintos precios se puede acotar el conjunto de cestas peor y mejor que la elegida:

- Las cestas compradas con presupuestos que contenian a la eleccion son **peores**.
- Las cestas elegidas cuando estaban disponibles son **mejores**.

Repitiendo el ejercicio se estrecha el area en que debe estar la curva de indiferencia.

## 6. Numeros indices

Comparando situaciones 0 y 1 (base y actual):

- **Numero indice de cantidades**: $I_q = \dfrac{w_1 x_1^1 + w_2 x_2^1}{w_1 x_0^1 + w_2 x_0^2}$... mas precisamente, con precios base $w$:

$$
I_q = \frac{w_1 x_1^1 + w_2 x_2^1}{w_1 x_1^0 + w_2 x_2^0}
$$

- **Numero indice de precios**: pondera precios con cantidades fijas:

$$
I_p = \frac{p_1^1 x_1^b + p_2^1 x_2^b}{p_1^0 x_1^b + p_2^0 x_2^b}
$$

donde $b=0$ da el indice de Laspeyres (cantidades base) y $b=1$ el indice de Paasche (cantidades actuales).

## 7. Indices de precios y bienestar

Sea $M_i$ la renta en la situacion $i$. Comparaciones utiles:

| Comparacion | Condicion | Conclusion |
|:------------|:----------|:-----------|
| Indice de Laspeyres vs renta | $\dfrac{M_1}{M_0} > I_L$ | El consumidor esta mejor en 1 |
| Indice de Paasche vs renta | $\dfrac{M_1}{M_0} < I_P$ | El consumidor esta peor en 1 |

```{admonition} Concepto clave
:class: tip
Si el indice de precios de Laspeyres supera al de Paasche, el nivel de vida ha caido; si ocurre lo contrario, ha subido. Cuando coinciden, el bienestar no cambia.
```

## 8. Resumen

| Concepto | Idea central |
|:---------|:-------------|
| Preferencia revelada | Inferir preferencias de elecciones observadas |
| WARP | No elegir $x$ sobre $y$ y luego $y$ sobre $x$ |
| SARP | Lo mismo con cadenas de comparaciones |
| Numero indice | Medida resumen de cambios de precios o cantidades |
| Laspeyres / Paasche | Ponderacion con cantidades base / actuales |

## 9. Preguntas de practica

**1.** Un consumidor compra $x$ cuando el presupuesto permite $y$, y mas tarde compra $y$ cuando el presupuesto permite $x$. Su comportamiento viola:

(A) El axioma debil
(B) El axioma fuerte solo
(C) Ningun axioma
(D) La completitud

```{admonition} Respuesta
:class: dropdown
**A.** Es una violacion directa del axioma debil (WARP); por extension tambien del fuerte.
```

**2.** Si el indice de precios de Laspeyres crece menos que la renta nominal, el consumidor:

(A) Esta peor que antes
(B) Esta mejor que antes
(C) Tiene el mismo bienestar
(D) No puede determinarse

```{admonition} Respuesta
:class: dropdown
**B.** Puede seguir comprando la cesta antigua y le sobra renta: esta mejor.
```

**3.** El indice de Paasche utiliza como ponderaciones:

(A) Las cantidades del periodo base
(B) Las cantidades del periodo actual
(C) Los precios del periodo base
(D) Cantidades arbitrarias

```{admonition} Respuesta
:class: dropdown
**B.** Paasche pondera con cantidades del periodo actual; Laspeyres con las del periodo base.
```
