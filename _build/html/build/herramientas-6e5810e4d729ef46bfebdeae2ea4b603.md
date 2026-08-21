---
title: "Herramientas y recursos"
description: "Herramientas adicionales"
---

# Herramientas y Recursos

## Herramientas recomendadas

### Calculo matematico

- **Wolfram Alpha** (https://www.wolframalpha.com): Calculo simbolico y numerico
- **GeoGebra** (https://www.geogebra.org): Graficas interactivas de optimizacion
- **Desmos** (https://www.desmos.com): Graficador de funciones

### Cuadernos Jupyter

- **Google Colab** (https://colab.research.google.com): Ejecucion de notebooks en la nube
- **JupyterHub** (https://jupyter.org): Entorno local de notebooks

### Datos economicos

- **DANE** (https://www.dane.gov.co): Estadisticas nacionales de Colombia
- **Banco de la Republica** (https://www.banrep.gov.co): Datos macroeconomicos
- **FMI** (https://www.imf.org): Datos internacionales
- **World Bank** (https://data.worldbank.org): Indicadores de desarrollo

---

## Cursos complementarios

- [MIT OCW 14.01 - Principles of Microeconomics](https://ocw.mit.edu/courses/14-01sc-principles-of-microeconomics-fall-2011/)
- [Coursera - Microeconomics](https://www.coursera.org/learn/microeconomics-part1)
- [Khan Academy - Microeconomics](https://es.khanacademy.org/economia-macroeconomia/microeconomia-basica)

---

## Software de graficas economicas

### Para graficas del consumidor y la empresa

```python
import matplotlib.pyplot as plt
import numpy as np

# Ejemplo: Restriccion presupuestaria
I = 120
Px, Py = 4, 6
x = np.linspace(0, I/Px, 100)
y = (I - Px*x) / Py

plt.figure(figsize=(8, 6))
plt.plot(x, y, 'b-', linewidth=2, label='Restriccion presupuestaria')
plt.xlabel('X')
plt.ylabel('Y')
plt.title('Restriccion Presupuestaria')
plt.grid(True, alpha=0.3)
plt.legend()
plt.show()
```

---

## Contacto

- **Soporte**: soporte.micro.unal@gmail.com
- **Universidad Nacional de Colombia**
