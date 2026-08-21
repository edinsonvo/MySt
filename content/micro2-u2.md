---
title: "U2: La ecuacion de Slutsky"
description: "Capitulo 8 de Varian: efecto sustitucion, efecto renta, variacion total, tasas de variacion y ley de la demanda"
---

# U2: La ecuacion de Slutsky (Capitulo 8)

```{tableofcontents}
```

## 1. El problema

Cuando baja el precio de un bien, la cantidad demandada cambia por dos razones:

1. **Efecto sustitucion**: el bien se vuelve relativamente mas barato frente a los demas.
2. **Efecto renta**: con el precio menor, la renta del consumidor compra mas: su poder adquisitivo aumenta.

La **ecuacion de Slutsky** descompone la variacion total de la demanda en estos dos efectos.

## 2. El experimento mental de Slutsky

Ante una caida de $p_1$:

1. **Paso 1 (ajuste Slutsky)**: ajustar la renta $m'$ para que el consumidor pueda seguir comprando exactamente la cesta antigua:
$$
m' = m + \Delta p_1 \cdot x_1
$$
con $\Delta p_1 < 0$, la renta compensada disminuye.

2. **Paso 2 (efecto sustitucion)**: el cambio de demanda entre la cesta original y la cesta optima al nuevo precio con la renta compensada. Se mueve sobre la recta presupuestaria que pasa por la cesta original.

3. **Paso 3 (efecto renta)**: devolver la renta a su nivel original; el cambio restante es efecto renta.

## 3. Efecto sustitucion

El **efecto sustitucion** $\Delta x_1^s$ es siempre de signo opuesto al cambio de precio: si $p_1$ baja, $x_1^s$ sube, y viceversa. Esto se debe a la convexidad de las preferencias: la recta presupuestaria compensada rota alrededor de la cesta original y la nueva eleccion debe estar en el lado donde $x_1$ aumenta cuando $p_1$ cae.

```{admonition} Concepto clave
:class: tip
El efecto sustitucion tiene signo definido: $\Delta x_1 \cdot \Delta p_1 \leq 0$. Es la ley de la demanda compensada.
```

## 4. Efecto renta

El **efecto renta** $\Delta x_1^n$ depende del tipo de bien:

| Tipo de bien | Ante aumento de renta | Signo del efecto renta cuando $p_1$ baja |
|:-------------|:----------------------|:------------------------------------------|
| Normal | La demanda sube | Positivo |
| Inferior | La demanda baja | Negativo |

## 5. Variacion total y ecuacion de Slutsky

La variacion total de la demanda es la suma de ambos efectos:

$$
\Delta x_1 = \Delta x_1^s + \Delta x_1^n
$$

En terminos de tasas de variacion:

```{math}
:label: eq-slutsky
\frac{\Delta x_1}{\Delta p_1} =
\underbrace{\frac{\Delta x_1^s}{\Delta p_1}}_{<0}
-
\underbrace{\frac{\Delta x_1^m}{\Delta m}\, x_1}_{\text{efecto renta}}
```

donde $\Delta x_1^m/\Delta m$ es como responde la demanda a la renta y $x_1$ convierte el cambio de precio en cambio equivalente de renta.

## 6. Casos particulares

### 6.1 Bien normal

Ambos efectos refuerzan la ley de la demanda: si $p_1$ baja, el efecto sustitucion aumenta $x_1$ y el efecto renta tambien. La demanda cae cuando el precio sube, sin ambiguedad.

### 6.2 Bien inferior

Los efectos se oponen: el efecto sustitucion empuja $x_1$ hacia arriba cuando $p_1$ baja, pero el efecto renta lo empuja hacia abajo. Si domina el efecto sustitucion, la demanda sigue siendo decreciente en el precio (bien inferior ordinario).

### 6.3 Bien de Giffen

Si el bien es inferior y el **efecto renta domina** al efecto sustitucion, entonces $\Delta x_1/\Delta p_1 > 0$: la curva de demanda tiene pendiente positiva.

```{admonition} Concepto clave
:class: tip
Bien de Giffen = bien inferior + efecto renta dominante. Por eso los bienes de Giffen deben ser muy importantes en el presupuesto del consumidor.
```

## 7. Tasas de variacion en elasticidades

Multiplicando {eq}`eq-slutsky` por $p_1/x_1$ se obtiene la version en elasticidades:

$$
\varepsilon_1 = \varepsilon_{1s} - s_1\,\eta_1
$$

donde $\varepsilon_1$ es la elasticidad precio total, $\varepsilon_{1s}$ la elasticidad de sustitucion, $\eta_1$ la elasticidad renta y $s_1$ la participacion del bien en el gasto.

## 8. Resumen

| Concepto | Idea central |
|:---------|:-------------|
| Efecto sustitucion | Cambio por rotacion de precios relativos; signo opuesto a $\Delta p$ |
| Efecto renta | Cambio por variacion del poder adquisitivo |
| Ajuste de Slutsky | Compensar renta para permitir la cesta original |
| Bien normal | Ambos efectos refuerzan la ley de la demanda |
| Bien inferior | Efectos opuestos; domina la sustitucion |
| Bien de Giffen | Inferior con efecto renta dominante |

## 9. Preguntas de practica

**1.** El efecto sustitucion ante una subida de $p_x$:

(A) Siempre reduce la cantidad de $X$
(B) Siempre aumenta la cantidad de $X$
(C) Puede ir en cualquier direccion
(D) No existe

```{admonition} Respuesta
:class: dropdown
**A.** El efecto sustitucion siempre opera en sentido contrario al cambio de precio.
```

**2.** En la ecuacion de Slutsky para un bien normal, el efecto total ante una subida del precio es:

(A) Positivo
(B) Negativo
(C) Cero
(D) Indeterminado

```{admonition} Respuesta
:class: dropdown
**B.** Sustitucion negativa y renta negativa se refuerzan.
```

**3.** Un bien de Giffen surge cuando:

(A) El bien es normal y el efecto renta domina
(B) El bien es inferior y el efecto renta domina al de sustitucion
(C) El bien es inferior y el efecto sustitucion domina
(D) Los bienes son sustitutivos perfectos

```{admonition} Respuesta
:class: dropdown
**B.** Inferioridad + dominancia del efecto renta producen demanda creciente en el precio.
```
