---
title: "U4: Los mercados de activos"
description: "Capitulo 11 de Varian: rendimientos, arbitraje, activos con y sin riesgo, modelo de Hotelling"
---

# U4: Los mercados de activos (Capitulo 11)

```{tableofcontents}
```

## 1. Los rendimientos de los activos

Un **activo** es un bien que proporciona un flujo de servicios o dinero a lo largo del tiempo. El **rendimiento** de un activo entre hoy y manana es la tasa de retorno:

$$
r = \frac{A_1 - A_0}{A_0}
$$

donde $A_0$ es el precio actual y $A_1$ el valor futuro esperado.

```{admonition} Concepto clave
:class: tip
En equilibrio, todos los activos con caracteristicas identicas (riesgo, liquidez) deben ofrecer el mismo rendimiento ajustado. Si no, el **arbitraje** elimina las diferencias.
```

## 2. Arbitraje

El **arbitraje** consiste en comprar y vender simultaneamente activos para obtener una ganancia segura sin invertir nada.

- **Arbitraje puro**: ganancia garantizada sin riesgo ni desembolso; en mercados eficientes desaparece al instante.
- **Arbitraje con riesgo**: operaciones casi seguras pero sujetas a riesgo residual.

### 2.1 La condicion de no arbitraje

Si existe un activo libre de riesgo con rendimiento $r$, todo activo sin riesgo debe rendir $r$. Para un activo que paga $A_1$ manana:

$$
A_0 = \frac{A_1}{1+r}
$$

El precio de hoy es el valor actual del pago futuro.

## 3. Activos con pagos ciertos

Ejemplos:

| Activo | Condicion de no arbitraje |
|:-------|:--------------------------|
| Bonos y cuentas bancarias | $A_0(1+r)=A_1$ |
| Activos que pagan dividendos | Rendimiento total = apreciacion + dividendo |
| Activos agotables | Precio crece al tipo de interes |

Si un activo rinde ademas un flujo $D$, la condicion se convierte en:

$$
\frac{A_1 + D}{A_0} = 1 + r
$$

## 4. Propiedades de los mercados de activos

Bajo no arbitraje:

1. **Activos homogeneos rinden lo mismo**: diferencias de rendimiento reflejan diferencias de riesgo, impuestos o liquidez.
2. **Principio de valor actual**: el precio de un activo es el valor presente de sus flujos futuros.
3. **Aplicaciones**: valoracion de bonos perpetuos ($PV = D/r$), acciones como derecho sobre dividendos futuros.

## 5. El modelo de Hotelling

Varian aplica la condicion de no arbitraje a recursos naturales agotables (petroleo). Si extraer una unidad cuesta cero, el precio neto del recurso sube al tipo de interes:

$$
p_{t+1} = (1+r)\,p_t
$$

Si el precio creciera mas rapido que $r$, convendria dejar el recurso bajo tierra; si creciera mas lento, convendria extraerlo todo hoy. Solo $p_t=(1+r)^t p_0$ es consistente con el equilibrio.

```{admonition} Concepto clave
:class: tip
Regla de Hotelling: el precio de un recurso agotable con coste de extraccion nulo crece al tipo de interes. Con costes de extraccion positivos, es el precio neto (renta de escasez) el que crece a $r$.
```

## 6. Resumen

| Concepto | Idea central |
|:---------|:-------------|
| Rendimiento | Tasa de retorno del activo |
| Arbitraje | Ganancia sin riesgo; su existencia es incompatible con el equilibrio |
| No arbitraje | Todos los activos comparables rinden lo mismo |
| Valor actual | $A_0 = A_1/(1+r)$ |
| Regla de Hotelling | Precio del recurso agotable crece a $(1+r)$ |

## 7. Preguntas de practica

**1.** Un activo paga 110 manana y el tipo de interes es 10%. Su precio de equilibrio hoy es:

(A) 100
(B) 99
(C) 121
(D) 110

```{admonition} Respuesta
:class: dropdown
**A.** $A_0=110/1.10=100$.
```

**2.** En el modelo de Hotelling con coste de extraccion nulo, si el precio del recurso creciera menos que el tipo de interes:

(A) Los propietarios extraerian todo inmediatamente
(B) Lo dejarian bajo tierra
(C) El precio caeria
(D) Nada cambiaria

```{admonition} Respuesta
:class: dropdown
**A.** Extraer hoy e invertir al tipo $r$ rinde mas que esperar la revalorizacion del recurso.
```

**3.** La existencia de oportunidades de arbitraje puro indica que:

(A) El mercado esta en equilibrio
(B) El mercado no esta en equilibrio
(C) Los agentes son adversos al riesgo
(D) El activo es caro

```{admonition} Respuesta
:class: dropdown
**B.** El arbitraje puro solo puede existir fuera del equilibrio; las operaciones lo eliminan rapidamente.
```
