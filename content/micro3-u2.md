---
title: "U2: Equilibrio / Subastas"
description: "Capitulos 16 y 17 de Varian: oferta, equilibrio, impuestos, traslacion de impuestos, eficiencia, tipos de subastas y maldicion del ganador"
---

# U2: Equilibrio / Subastas (Capitulos 16-17)

```{tableofcontents}
```

## Parte I. El equilibrio (Capitulo 16)

### 1. La curva de oferta

La **oferta de mercado** es la suma horizontal de las ofertas individuales de las empresas:

$$
S(p) = \sum_{j=1}^{m} s_j(p)
$$

### 2. El equilibrio de mercado

El **equilibrio competitivo** $(p^*, q^*)$ satisface:

$$
D(p^*) = S(p^*)
$$

A $p^*$ no hay exceso de demanda ni de oferta: el mercado se vacia.

```{admonition} Concepto clave
:class: tip
Si $p>p^*$ hay exceso de oferta (presion a la baja del precio); si $p<p^*$ hay exceso de demanda (presion al alza). Solo en $p^*$ el precio es estacionario.
```

### 3. Impuestos

Con un impuesto por unidad $t$ sobre el bien aparecen dos precios: el que pagan los demandantes $p_D$ y el que reciben los ofertantes $p_S=p_D-t$.

El nuevo equilibrio cumple:

$$
D(p_D) = S(p_S)
$$

La **incidencia** del impuesto depende de las elasticidades:

| Situacion | Quien soporta el impuesto |
|:----------|:--------------------------|
| Demanda mas inelastica que la oferta | Mayor parte en los consumidores |
| Oferta perfectamente inelastica | Todo en los vendedores |
| Oferta perfectamente elastica | Todo en los compradores |

```{admonition} Concepto clave
:class: tip
No importa a quien se le cobre legalmente el impuesto: la incidencia economica depende solo de las elasticidades relativas.
```

### 4. Traslacion de impuestos

- **Oferta inelastica**: el impuesto se traslada poco al precio; lo absorbe el vendedor.
- **Oferta elastica**: el impuesto se traslada casi integramente al consumidor.

### 5. Eficiencia y perdida irrecuperable

El equilibrio competitivo maximiza el excedente total (consumidor + productor). Un impuesto genera una **perdida irrecuperable de eficiencia** (deadweight loss): el triangulo entre demanda y oferta para las unidades que dejan de intercambiarse.

Cuota de produccion y controles de precios tambien reducen el excedente total creando ineficiencia.

## Parte II. Las subastas (Capitulo 17)

### 6. Clasificacion de subastas

Segun el valor del objeto:

- **Valor privado**: cada postor tiene una valoracion propia (ejemplo: coleccionismo personal).
- **Valor comun**: el objeto vale lo mismo para todos pero su valor es incierto (ejemplo: yacimientos de petroleo).

Segun el mecanismo:

| Tipo | Regla |
|:-----|:------|
| Inglesa (ascendente) | Pujas crecientes; gana el ultimo postor |
| Holandesa (descendente) | Precio decreciente; gana quien acepte primero |
| Primera oferta sellada | Gana la puja mas alta; paga su puja |
| Segunda oferta sellada (Vickrey) | Gana la puja mas alta; paga la segunda |

### 7. Resultados de equivalencia

- La subasta inglesa y la de segunda oferta sellada generan el mismo resultado con valor privado: conviene pujar tu valoracion verdadera.
- La holandesa y la primera oferta sellada son estrategicamente equivalentes: conviene pujar por debajo de la valoracion (shading).

```{admonition} Concepto clave
:class: tip
En la subasta de segunda oferta (Vickrey), pujar la valoracion verdadera es una estrategia dominante: nunca puede perjudicarte.
```

### 8. La maldicion del ganador

En subastas de **valor comun**, ganar suele significar haber hecho la estimacion mas optimista del valor del objeto. El ganador tiende a pagar de mas si no corrige su puja anticipando esta seleccion adversa.

Estrategia racional: pujar como si supieras que tu senal es la mas alta de todas (ajustar a la baja).

## 9. Resumen

| Concepto | Idea central |
|:---------|:-------------|
| Equilibrio | $D(p^*)=S(p^*)$ |
| Incidencia fiscal | Depende de elasticidades, no de quien paga |
| Perdida irrecuperable | Triangulo de intercambios perdidos |
| Vickrey | Pagar la segunda puja induce sinceridad |
| Maldicion del ganador | Sobrepujar en valor comun |

## 10. Preguntas de practica

**1.** Si la oferta es perfectamente inelastica, un impuesto sobre el bien recae:

(A) Totalmente en los compradores
(B) Totalmente en los vendedores
(C) Mitad y mitad
(D) En el gobierno

```{admonition} Respuesta
:class: dropdown
**B.** Con oferta vertical, el precio neto recibido cae exactamente el importe del impuesto.
```

**2.** En una subasta de segunda oferta sellada, la estrategia optima es pujar:

(A) Menos que tu valoracion
(B) Mas que tu valoracion
(C) Exactamente tu valoracion
(D) Cero

```{admonition} Respuesta
:class: dropdown
**C.** Es estrategia dominante revelar la valoracion verdadera.
```

**3.** La maldicion del ganador surge en subastas de:

(A) Valor privado
(B) Valor comun
(C) Segunda oferta
(D) Formato ingles

```{admonition} Respuesta
:class: dropdown
**B.** Ganar revela que tu estimacion era la mas optimista entre todos los postores.
```
