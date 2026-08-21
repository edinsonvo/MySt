---
title: "U3: Compra y venta / Eleccion intertemporal"
description: "Capitulos 9 y 10 de Varian: dotaciones, demanda bruta y neta, oferta de trabajo, restriccion intertemporal, tipo de interes y valor actual"
---

# U3: Compra y venta / Eleccion intertemporal (Capitulos 9-10)

```{tableofcontents}
```

## Parte I. Compra y venta (Capitulo 9)

### 1. Dotacion neta y demanda bruta

Hasta ahora la renta era fija. Ahora el consumidor posee una **dotacion** inicial de bienes $(\omega_1,\omega_2)$ que puede vender en el mercado.

- **Demanda bruta**: cantidad total del bien que el consumidor acaba consumiendo.
- **Demanda neta**: diferencia entre demanda bruta y dotacion:

$$
d_1 = x_1 - \omega_1
$$

Si $d_1>0$ el consumidor es **comprador neto**; si $d_1<0$ es **vendedor neto**.

### 2. La restriccion presupuestaria con dotacion

El valor de lo comprado debe igualar al valor de lo vendido:

$$
p_1 x_1 + p_2 x_2 = p_1 \omega_1 + p_2 \omega_2
$$

La recta presupuestaria **siempre pasa por la dotacion**: $(\omega_1,\omega_2)$ es asequible para cualquier precio.

```{admonition} Concepto clave
:class: tip
Con dotaciones, un cambio de precios tiene un efecto renta adicional: si sube el precio de un bien que usted vende, su renta real aumenta.
```

### 3. Cambios en el equilibrio

- Si $p_1$ baja, el consumidor vendedor neto de 1 queda peor y puede pasar a comprador.
- Un consumidor optimizador nunca cambia de lado del mercado por un pequeno movimiento de precios: si es comprador neto y $p_1$ sube, sigue siendo comprador (o indiferente).

### 4. Oferta de trabajo

Aplicacion central: el consumidor ofrece horas de trabajo $\bar{L}-L$ (dotacion de tiempo $\bar{L}$) y consume ocio $L$ con precio igual al salario $w$. La restriccion:

$$
c = m + w(\bar{L} - L)
$$

donde $c$ es consumo y $m$ renta no laboral. El precio de ocio es $w$: subir el salario tiene efecto sustitucion (ocio mas caro, se trabaja mas) y efecto renta (mas rico, se desea mas ocio). Por eso la curva de oferta de trabajo puede tener tramos con pendiente negativa (efecto renta dominante).

## Parte II. La eleccion intertemporal (Capitulo 10)

### 5. La restriccion intertemporal

Consumos presentes y futuros: $(c_1,c_2)$ con rentas $(m_1,m_2)$ y tipo de interes $r$. Con posibilidad de prestar y pedir prestado:

$$
c_1 + \frac{c_2}{1+r} = m_1 + \frac{m_2}{1+r}
$$

El termino $1/(1+r)$ es el **valor actual** de un peso manana.

```{admonition} Concepto clave
:class: tip
Valor actual: $PV = FV/(1+r)$. A tipo de interes positivo, un peso futuro vale menos que uno presente.
```

### 6. Comparacion de flujos

Para comparar flujos de ingreso se descuenta cada pago a valor actual:

$$
PV = M_1 + \frac{M_2}{1+r} + \frac{M_3}{(1+r)^2} + \cdots
$$

Alternativamente puede capitalizarse todo al periodo final (valor futuro).

### 7. Tipos de interes reales y nominales

Si la inflacion es $\pi$, el tipo real aproxima:

$$
r_{real} \approx r_{nominal} - \pi
$$

La restriccion intertemporal relevante usa el tipo real.

### 8. Preferencias y eleccion

Con preferencias convexas sobre $(c_1,c_2)$, el optimo tangencia la restriccion intertemporal. Clasificacion:

| Situacion | Condicion |
|:----------|:----------|
| Prestatario | $c_1 > m_1$ |
| Prestamista | $c_1 < m_1$ |

Estatica comparativa: si sube $r$, un prestamista permanece prestamista y mejora su bienestar; un prestatario tiende a reducir $c_1$.

## 9. Resumen

| Concepto | Formula / Idea |
|:---------|:---------------|
| Demanda neta | $x_i - \omega_i$ |
| Restriccion con dotacion | Valor del consumo = valor de la dotacion |
| Oferta de trabajo | Efecto sustitucion vs renta ante cambios de $w$ |
| Restriccion intertemporal | $c_1+\frac{c_2}{1+r}=m_1+\frac{m_2}{1+r}$ |
| Valor actual | $FV/(1+r)$ |
| Tipo real | $r - \pi$ |

## 10. Preguntas de practica

**1.** Un consumidor vendedor neto de petroleo queda, tras una caida del precio del petroleo:

(A) Mejor
(B) Peor
(C) Igual
(D) Depende solo de sus preferencias

```{admonition} Respuesta
:class: dropdown
**B.** El valor de su dotacion cae; ademas puede cambiar de lado del mercado.
```

**2.** Si $r=10\%$ y la inflacion esperada es $4\%$, el tipo real aproximado es:

(A) 14%
(B) 6%
(C) 10%
(D) 4%

```{admonition} Respuesta
:class: dropdown
**B.** $r_{real}\approx 10\%-4\%=6\%$.
```

**3.** El aumento del salario reduce las horas trabajadas cuando:

(A) Domina el efecto sustitucion
(B) Domina el efecto renta
(C) El ocio es un bien inferior
(D) Nunca ocurre

```{admonition} Respuesta
:class: dropdown
**B.** Si domina el efecto renta, se demanda mas ocio y la oferta de trabajo cae.
```
