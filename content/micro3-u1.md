---
title: "U1: Excedente del consumidor / Demanda del mercado"
description: "Capitulos 14 y 15 de Varian: excedente del consumidor, variaciones compensatoria y equivalente, demanda de mercado, elasticidad y curva de Laffer"
---

# U1: Excedente del consumidor / Demanda del mercado (Capitulos 14-15)

```{tableofcontents}
```

## Parte I. Excedente del consumidor (Capitulo 14)

### 1. Excedente del consumidor

El **excedente del consumidor** (EC) mide el beneficio neto que obtiene un comprador: la diferencia entre lo que estaria dispuesto a pagar y lo que efectivamente paga.

$$
EC = \text{area bajo la demanda inversa} - \text{gasto}
$$

Con demanda discreta, es la suma de los precios de reserva menos el precio pagado por cada unidad; con demanda continua, es el area bajo la curva de demanda inversa hasta $p$.

```{admonition} Concepto clave
:class: tip
El area bajo la curva de demanda mide la utilidad bruta (disposicion total a pagar); el excedente del consumidor resta el gasto realizado.
```

### 2. Variacion del excedente

Si el precio sube de $p'$ a $p''$, el excedente cambia en:

$$
\Delta EC = -\int_{p'}^{p''} x(t)\,dt
$$

Esta area puede descomponerse en efecto renta y efecto sustitucion; para preferencias cuasilineales coincide exactamente con la variacion de utilidad.

### 3. Variaciones compensatoria y equivalente

Cuando el excedente no basta (bienes con grandes efectos renta), se usan medidas hicksianas:

| Medida | Definicion |
|:-------|:-----------|
| Variacion compensatoria (VC) | Dinero necesario para compensar al consumidor tras un cambio de precios |
| Variacion equivalente (VE) | Cambio de renta que afectaria tanto como el cambio de precios |

Para un alza del precio: VC $\geq |\Delta EC| \geq$ VE cuando el bien es normal.

### 4. Excedente del productor

Analogamente, el **excedente del productor** es el area sobre la curva de oferta hasta el precio de mercado: ingresos menos coste variable.

## Parte II. Demanda del mercado (Capitulo 15)

### 5. De la demanda individual a la de mercado

La **demanda de mercado** es la suma horizontal de las demandas individuales:

$$
X(p) = \sum_{i=1}^{n} x_i(p)
$$

A cada precio se suman las cantidades que cada consumidor desea comprar.

### 6. Elasticidad precio

La **elasticidad precio de la demanda** mide la sensibilidad de la cantidad ante cambios de precio:

```{math}
:label: eq-elasticidad
\varepsilon = \frac{\Delta q/q}{\Delta p/p} = \frac{d\ln q}{d\ln p}
```

Clasificacion:

| Valor | Tipo de demanda |
|:------|:----------------|
| $\varepsilon < -1$ | Elastica |
| $\varepsilon = -1$ | Unitaria |
| $-1 < \varepsilon < 0$ | Inelastica |

### 7. Elasticidad e ingreso

El ingreso total es $R=pq$. Su derivada respecto al precio:

$$
\frac{dR}{dp} = q\left(1 + \varepsilon\right)
$$

- Demanda elastica ($|\varepsilon|>1$): subir el precio reduce el ingreso.
- Demanda inelastica ($|\varepsilon|<1$): subir el precio aumenta el ingreso.
- Elasticidad unitaria: ingreso maximo.

```{admonition} Concepto clave
:class: tip
El ingreso total se maximiza donde la elasticidad es unitaria ($\varepsilon=-1$), resultado clave tambien para el monopolio.
```

### 8. Elasticidades cruzadas y renta

- **Elasticidad cruzada**: $\varepsilon_{12}=\frac{\Delta q_1/q_1}{\Delta p_2/p_2}$; positiva para sustitutivos, negativa para complementarios.
- **Elasticidad renta**: $\eta=\frac{\Delta q/q}{\Delta m/m}$; positiva para bienes normales, negativa para inferiores.

### 9. La curva de Laffer

Si la recaudacion tributaria es $T(p)=t\cdot q(t)$, subir el tipo impositivo $t$ puede reducir la recaudacion cuando la base (cantidad) cae lo suficiente. La **curva de Laffer** grafica esta relacion no monotona: existe un tipo maximo de recaudacion mas alla del cual aumentar el impuesto la disminuye.

## 10. Resumen

| Concepto | Formula / Idea |
|:---------|:---------------|
| Excedente del consumidor | Area bajo la demanda menos gasto |
| VC / VE | Medidas hicksianas de bienestar |
| Demanda de mercado | Suma horizontal de demandas individuales |
| Elasticidad precio | $\varepsilon=\frac{d\ln q}{d\ln p}$ |
| Ingreso maximo | $|\varepsilon|=1$ |
| Curva de Laffer | Recaudacion no monotona en el tipo impositivo |

## 11. Preguntas de practica

**1.** Si la demanda es inelastica, una subida del precio:

(A) Reduce el ingreso total
(B) Aumenta el ingreso total
(C) No altera el ingreso
(D) Hace infinito el ingreso

```{admonition} Respuesta
:class: dropdown
**B.** Con $|\varepsilon|<1$ la caida de cantidad es proporcionalmente menor que la subida del precio.
```

**2.** El excedente del consumidor es:

(A) El area bajo la demanda hasta el precio
(B) El area sobre la oferta
(C) El ingreso total
(D) La utilidad marginal

```{admonition} Respuesta
:class: dropdown
**A.** Disposicion a pagar menos gasto efectivo.
```

**3.** En la curva de Laffer, aumentar el tipo impositivo mas alla del maximo de recaudacion:

(A) Aumenta siempre la recaudacion
(B) Reduce la recaudacion
(C) No tiene efectos
(D) Elimina el impuesto

```{admonition} Respuesta
:class: dropdown
**B.** La contraccion de la base gravable domina al aumento del tipo.
```
