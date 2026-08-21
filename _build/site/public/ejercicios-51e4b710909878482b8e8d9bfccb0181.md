---
title: "Ejercicios resueltos"
description: "Ejercicios resueltos basados en los problemas de Varian, Microeconomia intermedia"
---

# Ejercicios Resueltos

Ejercicios tipo tomados y adaptados de los problemas de fin de capitulo de **Varian, *Microeconomia intermedia*** (soluciones segun el *Instructor's Manual*, 8a ed.).

## Ejercicio 1 - Micro I, Cap. 1-2

### Costo de oportunidad y restriccion presupuestaria

**Enunciado**: Laura tiene una renta mensual de $\$1{,}200{,}000$ y puede comprar comida a $\$8{,}000$ el plato o transportarse a $\$2{,}000$ el viaje.

**(a)** Escriba la restriccion presupuestaria.

**Solucion**:

```{math}
8000A + 2000T = 1{,}200{,}000 \quad\Rightarrow\quad T = 600 - 4A
```

- Intercepto $T$: $600$
- Intercepto $A$: $150$
- Pendiente: $-4$ (precio relativo)

**(b)** Si la renta sube a $\$1{,}600{,}000$, como cambia la restriccion?

Se **desplaza paralelamente hacia afuera**: mismo precio relativo, mayor poder adquisitivo (Varian, cap. 2).

## Ejercicio 2 - Micro I, Cap. 3-4

### Utilidad, RMS y transformacion monotona

**Enunciado**: $U = x^{0.4} y^{0.6}$.

**(a)** Demuestre que $W = \ln U$ representa las mismas preferencias.

$$
W = \ln(x^{0.4}y^{0.6}) = 0.4\ln x + 0.6\ln y
$$

Como $\ln$ es creciente, $W$ es una transformacion monotona positiva de $U$: **mismas preferencias**.

**(b)** Calcule la RMS y demuestre que es decreciente.

```{math}
RMS = \frac{MU_x}{MU_y} = \frac{0.4y}{0.6x} = \frac{2y}{3x}
```

Al aumentar $x$ sobre la curva de indiferencia, $y$ disminuye y la RMS **decrece**.

**(c)** Calcule la RMS en $(4,9)$.

```{math}
RMS = \frac{2(9)}{3(4)} = 1.5
```

## Ejercicio 3 - Micro I, Cap. 5

### Maximizacion de utilidad con Lagrange

**Enunciado**: Max $U=xy$ s.a. $p_x=4$, $p_y=2$, $m=120$.

**(a)** Lagrangiana y condiciones de primer orden:

```{math}
\mathcal{L} = xy + \lambda(120 - 4x - 2y)
```

- $\partial \mathcal{L}/\partial x = y - 4\lambda = 0$
- $\partial \mathcal{L}/\partial y = x - 2\lambda = 0$
- $\partial \mathcal{L}/\partial \lambda = 120 - 4x - 2y = 0$

**(b)** Solucion: de las dos primeras, $y=2x$; sustituyendo, $x^*=15$, $y^*=30$.

**(c)** Verificacion con las demandas Cobb-Douglas de Varian (cap. 5): cada bien recibe la mitad de la renta:

```{math}
x^* = \frac{1}{2}\cdot\frac{120}{4} = 15, \qquad y^* = \frac{1}{2}\cdot\frac{120}{2} = 30
```

## Ejercicio 4 - Micro II, Cap. 8

### Descomposicion de Slutsky

**Enunciado**: $u=xy$, $m=120$, $p_1=p_2=1$. El precio $p_1$ sube a $4$. Descomponga el efecto total por el metodo de Slutsky.

**Solucion**:

**(a)** Optimo inicial (Cobb-Douglas con $a=b$): $x_0=\frac{1}{2}\frac{120}{1}=60$, $y_0=60$.

**(b)** Nuevo optimo: $x_1=15$, $y_1=30$. Efecto total: $\Delta x=-45$.

**(c)** Ajuste de Slutsky: renta compensada para permitir la cesta original al nuevo precio:

```{math}
m' = m + \Delta p_1 \cdot x_0 = 120 + 3\times 60 = 300
```

Optimo compensado: $x_c = m'/(2p_1') = 300/8 = 37.5$.

- **Efecto sustitucion**: $37.5 - 60 = -22.5$
- **Efecto renta**: $15 - 37.5 = -22.5$
- **Total**: $-45$

Ambos efectos son negativos porque $x$ es un bien normal (ley de la demanda).

## Ejercicio 5 - Micro III, Caps. 18-21

### Minimizacion de costos con Cobb-Douglas

**Enunciado**: $Q=K^{0.5}L^{0.5}$, $w=4$, $r=1$, $Q=100$.

**(a)** Formulacion:

```{math}
\min\; 4L + K \quad \text{s.a.} \quad K^{0.5}L^{0.5} = 100
```

**(b)** Tangencia isocuanta-isocoste: $TMST=w/r$:

```{math}
\frac{K}{L} = 4 \quad\Rightarrow\quad K = 4L
```

Sustituyendo: $2L=100$, luego $L=50$, $K=200$.

**(c)** Coste minimo: $C=4(50)+200=400$; coste medio $C/Q=4$.

## Ejercicio 6 - Micro III, Caps. 16 y 24

### Equilibrio competitivo, monopolio y excedentes

**Enunciado**: $Q^d=100-2P$, $Q^s=3P-10$.

**(a)** Equilibrio competitivo: $P^*=22$, $Q^*=56$.

**(b)** Excedentes:

```{math}
EC = \frac{1}{2}(50-22)(56) = 784
```

**(c)** Si este mercado lo atiende un monopolista con coste marginal $CMg=(Q+10)/3$, maximiza $IMg=CMg$:

Demanda inversa $P=50-Q/2$, ingreso marginal $IMg=50-Q$. Igualando:

```{math}
50 - Q = \frac{Q+10}{3} \quad\Rightarrow\quad Q_m = 35,\quad P_m = 32.5
```

El monopolista produce menos ($35<56$) y cobra mas ($32.5>22$), generando perdida irrecuperable de eficiencia.
