---
title: "U3: Tecnologia, beneficio y costes"
description: "Capitulos 18 a 21 de Varian: funcion de produccion, isocuantas, rendimientos de escala, maximizacion del beneficio, minimizacion de costos y curvas de coste"
---

# U3: Tecnologia, beneficio y costes (Capitulos 18-21)

```{tableofcontents}
```

## Parte I. La tecnologia (Capitulo 18)

### 1. Funcion de produccion

La **funcion de produccion** describe la cantidad maxima de producto $y$ obtenible con cada combinacion de factores:

$$
y = f(x_1, x_2)
$$

donde $x_1$ y $x_2$ son factores (trabajo, capital). El conjunto de produccion factible son las combinaciones que permiten obtener al menos $y$.

### 2. Isocuantas

Una **isocuanta** reune las combinaciones de factores que producen la misma cantidad:

$$
f(x_1,x_2) = \bar{y}
$$

Es el anologo de la curva de indiferencia en la teoria de la empresa.

### 3. Propiedades de la tecnologia

| Propiedad | Significado |
|:----------|:------------|
| Monotonicidad | Mas factores no reducen el producto |
| Convexidad | Los metodos mixtos de produccion son viables |

### 4. Productos marginales y TMST

- **Producto marginal** del factor 1: $MP_1=\partial f/\partial x_1$: producto adicional por unidad extra del factor.
- **Producto marginal tecnico decreciente**: manteniendo fijo el otro factor, $MP_1$ eventualmente decrece.
- **Tasa marginal de sustitucion tecnica (TMST)**: pendiente de la isocuanta:

$$
TMST = -\frac{dx_2}{dx_1}\bigg|_{y=\bar{y}} = \frac{MP_1}{MP_2}
$$

### 5. Rendimientos de escala

Al multiplicar todos los factores por $t>1$:

| Caso | Condicion |
|:-----|:----------|
| Rendimientos crecientes | $f(tx_1,tx_2) > t\,f(x_1,x_2)$ |
| Rendimientos constantes | $f(tx_1,tx_2) = t\,f(x_1,x_2)$ |
| Rendimientos decrecientes | $f(tx_1,tx_2) < t\,f(x_1,x_2)$ |

Ejemplo tipico: Cobb-Douglas $y=x_1^{a}x_2^{b}$ tiene rendimientos crecientes si $a+b>1$, constantes si $a+b=1$, decrecientes si $a+b<1$.

## Parte II. Maximizacion del beneficio (Capitulo 19)

### 6. El problema del empresario

La empresa elige factores para maximizar beneficio con precios $(w_1,w_2)$ del factor y $p$ del producto:

$$
\max_{x_1,x_2}\; p\, f(x_1,x_2) - w_1 x_1 - w_2 x_2
$$

Condicion de primer orden interior:

$$
p\, MP_1 = w_1, \qquad p\, MP_2 = w_2
$$

**Valor del producto marginal = precio del factor.**

```{admonition} Concepto clave
:class: tip
En competencia, cada factor se contrata hasta que su producto marginal valorado a precios de mercado iguala su salario: $p\,MP_i=w_i$.
```

### 7. Propiedades de las demandas de factores

- Si sube $w_1$, la demanda de $x_1$ cae.
- Si sube $p$, la demanda de factores y la oferta de producto aumentan (con rendimientos constantes, la escala es indeterminada: beneficio cero).

## Parte III. Minimizacion de costos (Capitulo 20)

### 8. El problema de minimizacion

Para producir $\bar{y}$ al minimo coste:

$$
\min_{x_1,x_2}\; w_1 x_1 + w_2 x_2 \quad \text{s.a.} \quad f(x_1,x_2)=\bar{y}
$$

En el optimo interior, la isocuanta es tangente a la recta de isocoste:

$$
TMST = \frac{MP_1}{MP_2} = \frac{w_1}{w_2}
$$

### 9. La funcion de costes

Resolviendo para cada nivel de producto se obtienen las **demandas condicionales de factores** $x_1(w_1,w_2,y)$, $x_2(w_1,w_2,y)$ y la **funcion de costes**:

$$
c(w_1,w_2,y) = w_1 x_1(w_1,w_2,y) + w_2 x_2(w_1,w_2,y)
$$

## Parte IV. Curvas de coste (Capitulo 21)

### 10. Costes fijos, variables y medios

Con un factor fijo (capital) a corto plazo:

- **Coste variable**: $c_v(y)=w_a x_a(y)$
- **Coste fijo**: $F$
- **Coste total**: $c(y)=c_v(y)+F$

Medias:

$$
CAV(y)=\frac{c_v(y)}{y}, \qquad CFM(y)=\frac{F}{y}, \qquad CMe(y)=\frac{c(y)}{y}=CAV+CFM
$$

### 11. Coste marginal

El **coste marginal** es el coste de producir una unidad adicional:

$$
CMg(y) = \frac{dc(y)}{dy} = \frac{dc_v(y)}{dy}
$$

```{admonition} Concepto clave
:class: tip
El CMg corta a las curvas de coste medio variable y coste medio total exactamente en sus puntos minimos.
```

### 12. Formas tipicas

- Con producto marginal primero creciente y luego decreciente, CMg tiene forma de U.
- A largo plazo todos los factores son variables; la curva de costes a largo plazo es la envolvente inferior de las curvas de coste a corto plazo.

## 13. Resumen

| Concepto | Formula / Idea |
|:---------|:---------------|
| Isocuanta | $f(x_1,x_2)=\bar{y}$ |
| TMST | $MP_1/MP_2$ |
| Optimo del productor | $p\,MP_i=w_i$ |
| Minimizacion de costos | $TMST=w_1/w_2$ |
| Coste marginal | $dc/dy$ |
| Minimos de medias | Donde $CMg=CAV$ y $CMg=CMe$ |

## 14. Preguntas de practica

**1.** La condicion de tangencia entre isocuanta e isocoste es:

(A) $MP_1=MP_2$
(B) $TMST=w_1/w_2$
(C) $w_1=w_2$
(D) $x_1=x_2$

```{admonition} Respuesta
:class: dropdown
**B.** La tasa de sustitucion tecnica debe igualar al precio relativo de los factores.
```

**2.** Para $y=x_1^{0.4}x_2^{0.5}$ los rendimientos de escala son:

(A) Crecientes
(B) Constantes
(C) Decrecientes
(D) Indeterminados

```{admonition} Respuesta
:class: dropdown
**C.** $a+b=0.9<1$: rendimientos decrecientes.
```

**3.** El coste marginal corta al coste medio total:

(A) En su maximo
(B) En su minimo
(C) Nunca se cruzan
(D) Cuando $y=0$

```{admonition} Respuesta
:class: dropdown
**B.** Propiedad clasica de las curvas de coste.
```
