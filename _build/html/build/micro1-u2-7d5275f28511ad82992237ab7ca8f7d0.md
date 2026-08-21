---
title: "U2: La restriccion presupuestaria"
description: "Capitulo 2 de Varian: cesta de consumo, recta presupuestaria, bienes numerario, impuestos, subvenciones y racionamiento"
---

# U2: La restriccion presupuestaria (Capitulo 2)

```{tableofcontents}
```

## 1. La cesta de consumo

La teoria del consumidor parte de la idea de que el consumidor elige una **cesta de consumo**: una lista de cantidades de los bienes. Con dos bienes:

$$
(x_1, x_2)
$$

donde $x_1$ es la cantidad del bien 1 y $x_2$ la del bien 2. A veces conviene pensar en $x_2$ como dinero gastado en todas las demas cosas.

## 2. La recta presupuestaria

Si el consumidor tiene una renta monetaria $m$ y enfrenta precios $(p_1, p_2)$, el **conjunto presupuestario** es el conjunto de cestas asequibles:

$$
p_1 x_1 + p_2 x_2 \leq m
$$

La **recta presupuestaria** es la frontera del conjunto: las cestas que agotan exactamente la renta,

$$
p_1 x_1 + p_2 x_2 = m
$$

Despejando $x_2$:

$$
x_2 = \frac{m}{p_2} - \frac{p_1}{p_2} x_1
$$

```{admonition} Concepto clave
:class: tip
- Intercepto vertical: $m/p_2$, cantidad maxima del bien 2.
- Pendiente: $-p_1/p_2$, el precio relativo o tasa a la que el mercado permite sustituir el bien 2 por el bien 1.
```

## 3. Propiedades de la recta presupuestaria

| Cambio | Efecto grafico |
|:-------|:---------------|
| Aumenta $m$ | Desplazamiento paralelo hacia afuera (misma pendiente) |
| Disminuye $m$ | Desplazamiento paralelo hacia adentro |
| Aumenta $p_1$ | Rotacion hacia adentro alrededor del intercepto vertical |
| Disminuye $p_1$ | Rotacion hacia afuera |
| Duplican $p_1$, $p_2$ y $m$ | Nada cambia (invariabilidad nominal) |

El ultimo punto es importante: solo importan los **precios relativos** y la **renta real**. Si todos los precios y la renta se multiplican por $t$:

$$
t\,p_1 x_1 + t\,p_2 x_2 = t\,m \iff p_1 x_1 + p_2 x_2 = m
$$

## 4. El bien numerario

Podemos fijar uno de los precios en 1 tomandolo como **numerario**. Dividiendo entre $p_2$:

$$
\frac{p_1}{p_2} x_1 + x_2 = \frac{m}{p_2}
$$

Ahora $x_2$ mide dinero gastado en el resto de bienes, su precio es 1, y la pendiente de la restriccion es $-p_1/p_2$: el precio relativo del bien 1 medido en unidades del numerario.

## 5. Impuestos, subvenciones y racionamiento

### 5.1 Impuesto sobre la cantidad

Un impuesto $t$ por unidad comprada eleva el precio al consumidor:

$$
(p_1 + t)\,x_1 + p_2 x_2 = m
$$

### 5.2 Impuesto sobre el valor (ad valorem)

Una tasa $\tau$ multiplica el precio: el consumidor paga $(1+\tau)p_1$:

$$
(1+\tau)\,p_1 x_1 + p_2 x_2 = m
$$

### 5.3 Subvencion

Una subvencion $s$ por unidad reduce el precio efectivo:

$$
(p_1 - s)\,x_1 + p_2 x_2 = m
$$

### 5.4 Impuesto de suma fija (lump-sum)

Reduce la renta sin alterar precios:

$$
p_1 x_1 + p_2 x_2 = m - T
$$

### 5.5 Racionamiento

Se limita la cantidad consumida del bien 1 a un maximo $\bar{x}_1$. El conjunto presupuestario queda truncado: la parte con $x_1 > \bar{x}_1$ deja de ser asequible.

```{admonition} Ejemplo: cupones de alimentacion
En Estados Unidos, los cupones de alimentacion otorgan una subvencion para comprar comida. Si el subsidio depende de cuanto se gaste en comida (tasa de subvencion), la recta presupuestaria tiene un tramo mas plano en la zona subsidiada; si el subsidio es una suma fija condicionada a gastar un minimo, la recta presenta una discontinuidad (salto).
```

## 6. Resumen

| Concepto | Formula / Idea |
|:---------|:---------------|
| Conjunto presupuestario | $p_1 x_1 + p_2 x_2 \leq m$ |
| Recta presupuestaria | $p_1 x_1 + p_2 x_2 = m$ |
| Pendiente | $-p_1/p_2$ (precio relativo) |
| Bien numerario | Bien cuyo precio se fija en 1 |
| Impuesto sobre cantidad | Precio efectivo $p_1 + t$ |
| Impuesto ad valorem | Precio efectivo $(1+\tau)p_1$ |
| Racionamiento | Cantidad maxima $\bar{x}_1$ |

## 7. Preguntas de practica

**1.** Si $m = 120$, $p_1 = 4$ y $p_2 = 6$, la pendiente de la recta presupuestaria es:

(A) $-4/6$
(B) $-6/4$
(C) $-20$
(D) $-30$

```{admonition} Respuesta
:class: dropdown
**A.** Pendiente $= -p_1/p_2 = -4/6$.
```

**2.** Si se duplican simultaneamente todos los precios y la renta:

(A) El conjunto presupuestario se contrae
(B) El conjunto presupuestario se expande
(C) El conjunto presupuestario no cambia
(D) La recta rota alrededor del origen

```{admonition} Respuesta
:class: dropdown
**C.** Por invariabilidad nominal, multiplicar todo por el mismo factor no altera la restriccion real.
```

**3.** Un impuesto ad valorem de 10% sobre el bien 1 hace que la recta presupuestaria sea:

(A) $(1+0.1)p_1 x_1 + p_2 x_2 = m$
(B) $p_1 x_1 + (1+0.1)p_2 x_2 = m$
(C) $p_1 x_1 + p_2 x_2 = m - 0.1m$
(D) $0.9\,p_1 x_1 + p_2 x_2 = m$

```{admonition} Respuesta
:class: dropdown
**A.** El impuesto ad valorem eleva el precio pagado a $(1+\tau)p_1$.
```
