---
title: "U5: La incertidumbre"
description: "Capitulo 12 de Varian: consumo contingente, utilidad esperada, aversion al riesgo y diversificacion"
---

# U5: La incertidumbre (Capitulo 12)

```{tableofcontents}
```

## 1. Consumo contingente

Cuando el futuro es incierto, las "cestas" pasan a ser **consumos contingentes**: cantidades que se consumiran en cada estado de la naturaleza. Con dos estados (bueno $b$, malo $m$):

$$
(c_b, c_m)
$$

Un contrato de seguro es un intercambio de consumo contingente: se paga una prima en el buen estado para recibir una indemnizacion en el malo.

## 2. Probabilidades y utilidad esperada

Sea $\pi$ la probabilidad del estado bueno. La teoria de von Neumann-Morgenstern asigna a cada loteria una **utilidad esperada**:

```{math}
:label: eq-ue
U = \pi\, u(c_b) + (1-\pi)\, u(c_m)
```

donde $u(\cdot)$ es la utilidad sobre resultados ciertos.

```{admonition} Concepto clave
:class: tip
La hipotesis de la utilidad esperada dice que las probabilidades entran linealmente en la funcion de utilidad sobre loterias.
```

## 3. Actitudes frente al riesgo

La forma de $u$ determina la actitud ante el riesgo:

| Actitud | Forma de $u$ | Prefiere |
|:--------|:-------------|:---------|
| Adverso al riesgo | Concava ($u''<0$) | El valor esperado con certeza |
| Amante del riesgo | Convexa ($u''>0$) | La loteria |
| Neutral al riesgo | Lineal ($u''=0$) | Indiferente; solo mira el valor esperado |

### 3.1 Ejemplo numerico

Loteria: 50% de ganar 1000, 50% de ganar 0. Valor esperado: 500.

- Un agente adverso al riesgo con $u=\sqrt{c}$ obtiene utilidad esperada $\frac{1}{2}\sqrt{1000}+\frac{1}{2}\sqrt{0}\approx 15.8 < \sqrt{500}\approx 22.4$: prefiere 500 seguros.

## 4. Seguro y aversion al riesgo

Un consumidor adverso al riesgo con riqueza $W$ que puede perder $L$ con probabilidad $\pi$ comprara un seguro si su prima actuarialmente justa es $\pi L$. Estara dispuesto a pagar incluso algo mas que $\pi L$: la prima de riesgo.

Con prima justa, el seguro deja al consumidor con consumo cierto:

$$
c_b = c_m = W - \pi L
$$

y por concavidad esto domina quedarse sin asegurar.

```{admonition} Concepto clave
:class: tip
Los agentes adversos al riesgo siempre se benefician de asegurar a prima justa: la diversificacion elimina el riesgo sin reducir el consumo esperado.
```

## 5. Diversificacion

**No poner todos los huevos en la misma cesta**: repartir la riqueza entre activos cuyos rendimientos no esten perfectamente correlacionados reduce el riesgo total manteniendo el rendimiento esperado.

Ejemplo: invertir 50% en dos empresas independientes (sol y sombreros) da un rendimiento esperado igual pero varianza mucho menor que apostar todo a una.

## 6. Papel del mercado bursatil

El mercado de acciones permite **repartir el riesgo**: cada inversor lleva una pequena fraccion de muchos proyectos grandes, diversificando. Los mercados de riesgo completos mejoran el bienestar de los agentes adversos al riesgo.

## 7. Resumen

| Concepto | Idea central |
|:---------|:-------------|
| Consumo contingente | Planes de consumo por estado de la naturaleza |
| Utilidad esperada | $\pi u(c_b)+(1-\pi)u(c_m)$ |
| Aversion al riesgo | $u$ concava; se prefiere el valor esperado seguro |
| Prima justa | $\pi L$ |
| Diversificacion | Reducir riesgo combinando activos poco correlacionados |

## 8. Preguntas de practica

**1.** Un agente con utilidad $u=\sqrt{c}$ enfrenta 50% de ganar 4 y 50% de ganar 16. Su utilidad esperada es:

(A) 3
(B) 10
(C) 5
(D) 2.5

```{admonition} Respuesta
:class: dropdown
**A.** $0.5\sqrt{4}+0.5\sqrt{16}=1+2=3$.
```

**2.** Un agente neutral al riesgo elige entre loterias segun:

(A) Su varianza
(B) Su valor esperado monetario
(C) Su mediana
(D) Su moda

```{admonition} Respuesta
:class: dropdown
**B.** Con $u$ lineal, maximizar utilidad esperada equivale a maximizar el valor esperado.
```

**3.** La diversificacion reduce el riesgo cuando los rendimientos de los activos:

(A) Estan perfectamente correlacionados positivamente
(B) No estan perfectamente correlacionados
(C) Son identicos
(D) Son negativos

```{admonition} Respuesta
:class: dropdown
**B.** Solo hay beneficio diversificador si las fluctuaciones no son perfectamente sincronizadas.
```
