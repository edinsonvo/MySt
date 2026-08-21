---
title: "U4: La utilidad"
description: "Capitulo 4 de Varian: utilidad ordinal y cardinal, funciones de utilidad, utilidad marginal, RMS y preferencias Cobb-Douglas"
---

# U4: La utilidad (Capitulo 4)

```{tableofcontents}
```

## 1. Utilidad cardinal y ordinal

- **Utilidad cardinal**: interpretacion antigua en la que la utilidad es una medida fisica del placer, con unidades concretas.
- **Utilidad ordinal**: interpretacion moderna. La utilidad solo sirve para **ordenar** cestas: si $u(A) > u(B)$, entonces $A$ se prefiere a $B$. El nivel numerico no tiene significado propio.

```{admonition} Concepto clave
:class: tip
Solo importan las diferencias de orden: la utilidad es un instrumento para representar preferencias, no una medida de felicidad comparable entre personas.
```

## 2. Construccion de la funcion de utilidad

Dadas las curvas de indiferencia, se construye una funcion de utilidad asignando numeros crecientes a curvas mas alejadas del origen: $u(x_1,x_2)$ etiqueta cada curva de indiferencia.

## 3. Transformaciones monotonas positivas

Si $u(x_1,x_2)$ representa unas preferencias, entonces $v(x_1,x_2) = f(u(x_1,x_2))$ tambien las representa siempre que $f$ sea **monotona creciente** ($f'(u) > 0$).

Ejemplo: si $u = x_1 x_2$, entonces

$$
v = u^2 = x_1^2 x_2^2, \qquad w = \ln u = \ln x_1 + \ln x_2
$$

representan exactamente las mismas preferencias: ordenan las cestas igual.

```{admonition} Concepto clave
:class: tip
Una transformacion monotona positiva de la utilidad no altera las preferencias representadas ni la forma de las curvas de indiferencia.
```

## 4. Funciones de utilidad tipicas

| Preferencias | Funcion de utilidad |
|:-------------|:--------------------|
| Sustitutivos perfectos | $u(x_1,x_2)=a x_1 + b x_2$ |
| Complementarios perfectos | $u(x_1,x_2)=\min\{a x_1,\, b x_2\}$ |
| Cobb-Douglas | $u(x_1,x_2)=x_1^{c} x_2^{d}$ |
| Cuasilineal | $u(x_1,x_2)=v(x_1)+x_2$ |

## 5. Utilidad marginal

La **utilidad marginal** del bien $i$ mide el cambio de utilidad ante un pequeno incremento de $x_i$, manteniendo fijo el otro bien:

$$
MU_i = \frac{\partial u}{\partial x_i}
$$

## 6. Utilidad marginal y RMS

Considere un desplazamiento sobre la misma curva de indiferencia. El cambio total de utilidad debe ser cero:

$$
MU_1\,\Delta x_1 + MU_2\,\Delta x_2 = 0
$$

Despejando la pendiente:

$$
RMS = -\frac{\Delta x_2}{\Delta x_1} = \frac{MU_1}{MU_2}
$$

```{admonition} Concepto clave
:class: tip
La tasa marginal de sustitucion es el cociente de utilidades marginales: $RMS = MU_1/MU_2$. Este resultado se usa constantemente para resolver el problema del consumidor.
```

## 7. Preferencias Cobb-Douglas

Para $u(x_1,x_2)=x_1^{c}x_2^{d}$:

$$
MU_1 = c\,x_1^{c-1}x_2^{d}, \qquad MU_2 = d\,x_1^{c}x_2^{d-1}
$$

$$
RMS = \frac{MU_1}{MU_2} = \frac{c}{d}\cdot\frac{x_2}{x_1}
$$

Propiedades:

- Las curvas de indiferencia son suaves, convexas y nunca cortan los ejes.
- La RMS depende solo del cociente $x_2/x_1$: al multiplicar ambos bienes por $t$, la RMS no cambia (homogeneidad de grado uno).
- Una transformacion monotona util es $v = c\ln x_1 + d \ln x_2$.

## 8. Resumen

| Concepto | Formula / Idea |
|:---------|:---------------|
| Utilidad ordinal | Solo ordena cestas |
| Transformacion monotona | $f(u)$ con $f'>0$ representa las mismas preferencias |
| Utilidad marginal | $MU_i = \partial u/\partial x_i$ |
| RMS | $MU_1/MU_2$; pendiente de la curva de indiferencia |
| Cobb-Douglas | $u=x_1^c x_2^d$; $RMS=\frac{c}{d}\frac{x_2}{x_1}$ |

## 9. Preguntas de practica

**1.** Si $U = x^{0.5}y^{0.5}$ y $W = 2U + 5$, entonces $W$:

(A) Representa preferencias diferentes
(B) Representa las mismas preferencias
(C) No es una funcion de utilidad valida
(D) Cambia la forma de las curvas de indiferencia

```{admonition} Respuesta
:class: dropdown
**B.** $W=f(U)$ con $f'>0$ es una transformacion monotona positiva.
```

**2.** Para $u(x_1,x_2)=x_1 x_2$, la RMS en $(x_1,x_2)=(4,2)$ vale:

(A) $2$
(B) $1/2$
(C) $8$
(D) $1$

```{admonition} Respuesta
:class: dropdown
**B.** $RMS = \frac{x_2}{x_1} = 2/4 = 1/2$.
```

**3.** La utilidad marginal de un bien:

(A) Es constante siempre
(B) Mide el cambio de utilidad por unidad adicional del bien, ceteris paribus
(C) Es igual a la renta
(D) Nunca puede decrecer

```{admonition} Respuesta
:class: dropdown
**B.** $MU_i=\partial u/\partial x_i$ con el resto de cantidades fijado.
```
