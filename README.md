# Simulación — Entregable 1

Simulación de Monte Carlo para estimar la probabilidad de obtener Yahtzee y comparar
dos estrategias de lanzamiento de dados.

## Contenido

| Archivo | Descripción |
| --- | --- |
| `simulacion_01_probabilidad_yahtzee.ipynb` | Notebook con el desarrollo completo de la simulación. |

## Descripción del experimento

Se comparan dos formas de lanzar cinco dados con un máximo de tres tiradas por intento:

1. **Sin estrategia:** se vuelven a lanzar los cinco dados en cada tirada.
2. **Con estrategia sencilla:** se conservan los dados que muestran la cara más repetida
   y se relanzan los demás.

Se repite el experimento para 10, 50, 100, 500, 1.000 y 5.000 intentos, con el fin de
observar la Ley de los Grandes Números al comparar la probabilidad estimada con el
número de intentos.

La semilla está fijada (`SEMILLA = 42`) para que los resultados sean reproducibles.

## Requisitos

- Python 3.9 o superior
- `matplotlib`
- `pandas`

```bash
pip install matplotlib pandas
```

## Cómo ejecutar

```bash
jupyter notebook simulacion_01_probabilidad_yahtzee.ipynb
```

O abrir el archivo directamente en Google Colab.
