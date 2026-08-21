---
title: "U5: La eleccion"
description: "Capitulo 5 de Varian: eleccion optima del consumidor, demandas para sustitutivos y complementarios perfectos, bienes discretos, Cobb-Douglas e impuestos"
---

# U5: La eleccion (Capitulo 5)

```{tableofcontents}
```

## 1. La eleccion optima

El consumidor elige la cesta **mas preferida** dentro de su conjunto presupuestario. Combinando preferencias (curvas de indiferencia) y restriccion presupuestaria:

$$
\max_{x_1,x_2}\; u(x_1,x_2) \quad \text{s.a.} \quad p_1 x_1 + p_2 x_2 = m
$$

```{admonition} Condicion de tangencia
:class: tip
En el optimo interior, la curva de indiferencia es tangente a la recta presupuestaria:

$$RMS = -\frac{\Delta x_2}{\Delta x_1} = \frac{p_1}{p_2}$$

junto con la restriccion $p_1x_1+p_2x_2=m$. Dos ecuaciones, dos incognitas.
```

Intuicion: la tasa a la que el consumidor esta dispuesto a sustituir ($RMS$) debe igualar a la tasa a la que el mercado permite sustituir ($p_1/p_2$).

## 2. Demanda del consumidor

La solucion del problema anterior son las **funciones de demanda**:

$$
x_1 = x_1(p_1,p_2,m), \qquad x_2 = x_2(p_1,p_2,m)
$$

que expresan la cantidad optima en funcion de precios y renta.

## 3. Casos particulares

### 3.1 Sustitutivos perfectos

Con $u=x_1+x_2$, se compra solo el bien mas barato:

$$
x_1 =
\begin{cases}
m/p_1 & \text{si } p_1 < p_2\\
0 & \text{si } p_1 > p_2
\end{cases}
$$

Si $p_1=p_2$ cualquier cesta sobre la recta es optima.

### 3.2 Complementarios perfectos

Con $u=\min\{x_1,x_2\}$, el optimo se situa en el vertice $x_1=x_2$. Sustituyendo en la restriccion:

$$
x_1 = x_2 = \frac{m}{p_1+p_2}
$$

Se gasta siempre la mitad de la renta en cada bien, sea cual sea su precio relativo.

### 3.3 Bienes discretos

Si el bien 1 solo se consume en unidades enteras, se compara la utilidad de comprar $0,1,2,\dots$ unidades y se elige la mejor cesta asequible. El consumidor compra una unidad adicional si su precio de reserva supera a $p_1$.

### 3.4 Preferencias Cobb-Douglas

Para $u=x_1^{a}x_2^{b}$, la condicion $RMS=p_1/p_2$ da $\frac{a}{b}\frac{x_2}{x_1}=\frac{p_1}{p_2}$; combinada con la restriccion:

```{math}
:label: eq-cd-demanda
x_1^* = \frac{a}{a+b}\cdot\frac{m}{p_1}, \qquad x_2^* = \frac{b}{a+b}\cdot\frac{m}{p_2}
```

```{admonition} Concepto clave
:class: tip
Con Cobb-Douglas cada bien recibe una fraccion fija de la renta: $\frac{a}{a+b}m$ al bien 1 y $\frac{b}{a+b}m$ al bien 2, independientemente de los precios relativos.
```

## 4. Implicaciones de la teoria

- Si la renta aumenta, la demanda de un bien normal aumenta.
- Si $p_1$ baja, por lo general $x_1$ aumenta (se formaliza en los capitulos 7-8).
- Los impuestos distorsionan la eleccion: ver abajo.

## 5. Eleccion de impuestos: ingreso vs impuesto al consumo

Supongos que el gobierno necesita recaudar una cantidad fija. Dos alternativas:

1. **Impuesto sobre la cantidad** $t$ del bien 1: restriccion $(p_1+t)x_1+p_2x_2=m$.
2. **Impuesto de suma fija** equivalente $T=t x_1^*$: restriccion $p_1x_1+p_2x_2=m-T$.

Ambos recaudan lo mismo si el consumidor mantuviera su cesta original, pero bajo el impuesto de suma fija el consumidor puede elegir libremente y alcanza una curva de indiferencia mas alta.

```{admonition} Resultado clave
:class: tip
Un impuesto de suma fija recauda lo mismo que un impuesto al consumo pero deja al consumidor mejor: el impuesto al consumo introduce una distorsion de precios (la RMS deja de igualar al precio relativo bruto).
```

## 6. Resumen

| Preferencias | Demandas optimas |
|:-------------|:-----------------|
| Generales (optimo interior) | $RMS = p_1/p_2$ y $p_1x_1+p_2x_2=m$ |
| Sustitutivos perfectos | Solo el bien mas barato |
| Complementarios perfectos | $x_1=x_2=m/(p_1+p_2)$ |
| Cobb-Douglas | $x_1=\frac{a}{a+b}\frac{m}{p_1}$, $x_2=\frac{b}{a+b}\frac{m}{p_2}$ |

## 7. Preguntas de practica

**1.** Para $U = x^{a}y^{b}$, la demanda optima de $x$ es:

(A) $x^* = \frac{a}{a+b}\frac{m}{p_x}$
(B) $x^* = \frac{b}{a+b}\frac{m}{p_x}$
(C) $x^* = \frac{a}{b}\frac{m}{p_y}$
(D) $x^* = \frac{m}{p_x}$

```{admonition} Respuesta
:class: dropdown
**A.** Con Cobb-Douglas, $x^*=\frac{a}{a+b}\frac{m}{p_x}$.
```

**2.** Con $u=\min\{x_1,x_2\}$, $m=100$, $p_1=2$, $p_2=8$, el consumo optimo es:

(A) $x_1=10, x_2=10$
(B) $x_1=50, x_2=12.5$
(C) $x_1=10, x_2=10$ con gasto desigual
(D) $x_1=25, x_2=6.25$

```{admonition} Respuesta
:class: dropdown
**A.** $x_1=x_2=m/(p_1+p_2)=100/10=10$.
```

**3.** En el optimo interior del consumidor:

(A) $MU_1=MU_2$
(B) $RMS=p_1/p_2$
(C) $p_1=p_2$
(D) $x_1=x_2$

```{admonition} Respuesta
:class: dropdown
**B.** Tangencia entre curva de indiferencia y recta presupuestaria.
```
