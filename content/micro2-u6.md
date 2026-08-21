---
title: "U6: Los activos inciertos"
description: "Capitulo 13 de Varian: media y varianza, recta presupuestaria de activos, eleccion de cartera y valor medio-desviacion tipica"
---

# U6: Los activos inciertos (Capitulo 13)

```{tableofcontents}
```

## 1. Medias y varianzas

Un **activo riesgoso** se caracteriza por su rendimiento aleatorio $R$. Dos estadisticos resumen su atractivo:

- **Media (rendimiento esperado)**:
$$
\mu = E[R]
$$
- **Varianza** y desviacion tipica ($\sigma$):
$$
\sigma^2 = E[(R-\mu)^2]
$$

La media mide la recompensa; la varianza mide el riesgo.

## 2. Carteras con dos activos

Suponga una fraccion $x$ de la riqueza en el activo riesgoso con rendimiento $R_1$ y $(1-x)$ en el activo libre de riesgo con rendimiento fijo $R_f$. El rendimiento de la cartera:

$$
R = x R_1 + (1-x) R_f = R_f + x(R_1 - R_f)
$$

Su media y varianza:

$$
\mu = R_f + x(\mu_1 - R_f), \qquad \sigma^2 = x^2 \sigma_1^2
$$

Despejando, la relacion media-desviacion tipica es lineal:

$$
\mu = R_f + \frac{\mu_1 - R_f}{\sigma_1}\,\sigma
$$

```{admonition} Concepto clave
:class: tip
Combinando un activo riesgoso con uno libre de riesgo, las carteras posibles forman una recta en el plano $(\sigma,\mu)$: mas riesgo solo se acepta si viene acompanado de mas rendimiento esperado.
```

## 3. La recta presupuestaria de activos

En el plano (riesgo $\sigma$, rendimiento $\mu$), la **recta presupuestaria** tiene pendiente igual al precio del riesgo:

$$
p = \frac{\mu_m - R_f}{\sigma_m}
$$

donde $\mu_m$ es el rendimiento esperado del activo riesgoso de mercado y $\sigma_m$ su desviacion tipica. El intercepto es $R_f$, el precio del tiempo.

- Pendiente: cuanta recompensa extra por unidad de riesgo.
- Intercepto: recompensa por esperar (rendimiento sin riesgo).

## 4. Eleccion de cartera

El inversor elige el punto de la recta que toca su curva de indiferencia mas alta en el espacio $(\sigma,\mu)$:

- Un inversor muy adverso al riesgo elige poco $x$: cartera casi toda libre de riesgo.
- Un inversor menos adverso toma mas riesgo.

## 5. Valor medio - desviacion tipica

Las preferencias pueden representarse con funciones de utilidad crecientes en $\mu$ y decrecientes en $\sigma$:

$$
U = U(\mu, \sigma), \qquad \frac{\partial U}{\partial \mu} > 0,\quad \frac{\partial U}{\partial \sigma} < 0
$$

Este criterio es exacto cuando la utilidad depende solo de los dos primeros momentos de la distribucion (por ejemplo con utilidad cuadratica o rendimientos normales).

## 6. Contramedidas: diversificacion y riesgo de mercado

Al combinar muchos activos, el riesgo total se divide en:

- **Riesgo idiosincratico**: propio de cada activo; se elimina con diversificacion.
- **Riesgo sistematico (de mercado)**: correlacionado entre todos los activos; no puede eliminarse diversificando.

Solo el riesgo sistematico recibe compensacion en equilibrio.

## 7. Resumen

| Concepto | Formula / Idea |
|:---------|:---------------|
| Media | Rendimiento esperado $\mu=E[R]$ |
| Varianza | Medida de riesgo $\sigma^2$ |
| Cartera | $\mu=R_f+x(\mu_1-R_f)$, $\sigma=x\sigma_1$ |
| Precio del riesgo | Pendiente $(\mu_m-R_f)/\sigma_m$ |
| Diversificacion | Elimina riesgo idiosincratico, no el sistematico |

## 8. Preguntas de practica

**1.** Si la fraccion invertida en el activo riesgoso se duplica, la varianza de la cartera:

(A) Se duplica
(B) Se cuadruplica
(C) No cambia
(D) Se reduce a la mitad

```{admonition} Respuesta
:class: dropdown
**B.** $\sigma^2=x^2\sigma_1^2$: duplicar $x$ multiplica la varianza por 4.
```

**2.** El intercepto de la recta presupuestaria de activos es:

(A) El precio del riesgo
(B) El rendimiento libre de riesgo
(C) La varianza del mercado
(D) Cero

```{admonition} Respuesta
:class: dropdown
**B.** Con riesgo cero, el rendimiento disponible es $R_f$.
```

**3.** El riesgo que NO puede eliminarse mediante diversificacion es:

(A) El idiosincratico
(B) El sistematico
(C) El especifico de cada empresa
(D) Ninguno: todo riesgo se elimina

```{admonition} Respuesta
:class: dropdown
**B.** El riesgo sistematico afecta a todos los activos simultaneamente.
```
