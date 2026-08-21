---
title: "U3: Las preferencias"
description: "Capitulo 3 de Varian: axiomas de las preferencias, curvas de indiferencia, casos tipicos y tasa marginal de sustitucion"
---

# U3: Las preferencias (Capitulo 3)

```{tableofcontents}
```

## 1. Preferencias del consumidor

La teoria del consumidor describe el comportamiento de eleccion mediante **preferencias**: relaciones que ordenan las cestas de consumo segun su deseabilidad.

- $x_1, x_2 \succ y_1, y_2$: la cesta $(x_1,x_2)$ es **estrictamente preferida** a $(y_1,y_2)$.
- $\sim$: el consumidor es **indiferente** entre ambas cestas.
- $\succeq$: **preferencia debil**, al menos tan buena como.

## 2. Axiomas de las preferencias

Para poder construir curvas de indiferencia se suponen dos axiomas:

1. **Completitud**: ante dos cestas cualesquiera, el consumidor puede ordenarlas: prefiere una, o es indiferente.
2. **Transitividad**: si $A \succ B$ y $B \succ C$, entonces $A \succ C$. Sin transitividad no existen ciclos de preferencia y el comportamiento no seria consistente.

```{admonition} Concepto clave
:class: tip
Completitud y transitividad garantizan que las preferencias son un orden racional sobre las cestas de consumo.
```

## 3. Curvas de indiferencia

Una **curva de indiferencia** contiene todas las cestas entre las que el consumidor es indiferente. Propiedades para preferencias "normales" (monotonas):

1. **Pasando por cada cesta pasa exactamente una curva de indiferencia** (por transitividad las curvas no pueden cruzarse).
2. **Cuanto mas arriba a la derecha, mejor** (por monotonicidad: mas cantidad es preferible).
3. **Son decrecientes**: si se reduce un bien debe aumentarse el otro para mantener la utilidad.
4. **Son convexas respecto al origen**: los promedios se prefieren a los extremos (diversificacion).

## 4. Casos tipicos de preferencias

### 4.1 Sustitutivos perfectos

El consumidor esta dispuesto a sustituir siempre a la misma tasa; por ejemplo, lapices rojos y azules:

$$
u(x_1, x_2) = x_1 + x_2
$$

Las curvas de indiferencia son rectas paralelas con pendiente constante.

### 4.2 Complementarios perfectos

Los bienes se consumen siempre juntos en proporciones fijas; por ejemplo, zapatos izquierdos y derechos:

$$
u(x_1, x_2) = \min\{x_1, x_2\}
$$

Las curvas de indiferencia tienen forma de L con vertice en la linea $x_1 = x_2$.

### 4.3 Bienes neutrales

Un bien neutral no afecta la utilidad:

$$
u(x_1, x_2) = x_1
$$

Las curvas de indiferencia son lineas verticales.

### 4.4 Bienes males

Un bien mal reduce la utilidad; las curvas de indiferencia tienen pendiente positiva.

### 4.5 Saciedad

Existe un punto ideal $(\bar{x}_1, \bar{x}_2)$; alejarse de el en cualquier direccion reduce la utilidad.

```{admonition} Concepto clave
:class: tip
La forma de las curvas de indiferencia codifica toda la informacion relevante sobre las preferencias: rectas (sustitutivos perfectos), L (complementarios perfectos), convexas suaves (caso tipico).
```

## 5. Bienes normales, inferiores y saciedad

- Un **bien normal** es aquel del que se desea mas.
- Un **bien mal** es aquel del que se desea menos.
- La **saciedad** implica un punto optimo independiente de precios.

## 6. La tasa marginal de sustitucion (RMS)

La **tasa marginal de sustitucion** (en ingles MRS) es la pendiente de la curva de indiferencia en un punto: la cantidad de bien 2 que el consumidor esta dispuesto a ceder a cambio de una unidad adicional de bien 1 manteniendo la utilidad constante:

$$
RMS = -\frac{\Delta x_2}{\Delta x_1}\bigg|_{u=\bar{u}}
$$

Para preferencias convexas la RMS disminuye al aumentar $x_1$: cuanto mas de un bien se tiene, menos unidades del otro se esta dispuesto a sacrificar por una unidad adicional.

Casos extremos:

| Preferencias | RMS |
|:-------------|:----|
| Sustitutivos perfectos | Constante |
| Complementarios perfectos | Indefinida en el vertice (salto de 0 a $\infty$) |
| Convexas suaves | Decreciente |

## 7. Resumen

| Concepto | Idea central |
|:---------|:-------------|
| Preferencias | Ordenacion de cestas ($\succ$, $\sim$, $\succeq$) |
| Axiomas | Completitud y transitividad |
| Curva de indiferencia | Conjunto de cestas con igual utilidad |
| Monotonicidad | Mas es mejor; curvas decrecientes |
| Convexidad | Los promedios se prefieren a los extremos |
| Sustitutivos perfectos | $x_1 + x_2$; curvas rectas |
| Complementarios perfectos | $\min\{x_1,x_2\}$; curvas en L |
| RMS | Pendiente de la curva de indiferencia; decreciente en el caso convexo |

## 8. Preguntas de practica

**1.** Si un consumidor prefiere $A$ a $B$ y $B$ a $C$, la transitividad implica:

(A) Prefiere $C$ a $A$
(B) Prefiere $A$ a $C$
(C) Es indiferente entre $A$ y $C$
(D) No se puede determinar

```{admonition} Respuesta
:class: dropdown
**B.** Transitividad: $A \succ B$ y $B \succ C \Rightarrow A \succ C$.
```

**2.** Dos curvas de indiferencia NO pueden cruzarse porque:

(A) Los bienes son escasos
(B) Violaria la transitividad de las preferencias
(C) La utilidad es cardinal
(D) La RMS es constante

```{admonition} Respuesta
:class: dropdown
**B.** En un cruce, una misma cesta perteneceria a dos niveles distintos de utilidad, contradiciendo la transitividad.
```

**3.** Para preferencias $u(x_1,x_2)=\min\{x_1,2x_2\}$, el consumidor consume siempre en la proporcion:

(A) $x_1 = x_2$
(B) $x_1 = 2x_2$
(C) $x_2 = 2x_1$
(D) $x_1 + x_2 = k$

```{admonition} Respuesta
:class: dropdown
**B.** El vertice de la L ocurre donde $x_1 = 2x_2$: por cada unidad de $x_2$ se necesitan dos unidades de $x_1$.
```
