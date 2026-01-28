# Stellar Luminosity — Regresión Lineal y Polinómica (desde cero)

Implementación introductoria de regresión **sin librerías de ML** (desde primeros principios: hipótesis, función de costo, gradientes y descenso por gradiente) usando únicamente:
- Python
- NumPy
- Matplotlib (gráficas inline)

No se usa: `scikit-learn`, `statsmodels`, TensorFlow/PyTorch ni librerías de optimización/regresión de alto nivel.

## Estructura del repositorio
- `01_part1_linreg_1feature.ipynb` — Regresión lineal con 1 característica (masa $M$)
- `02_part2_polyreg.ipynb` — Ingeniería de características (polinomios + interacción) con 2 entradas (masa $M$, temperatura $T$)
- `README.md`

## Descripción rápida
El problema modela una relación simplificada inspirada en estrellas de secuencia principal, donde la luminosidad $L$ crece rápidamente con la masa $M$.\
En la Parte I se prueba un modelo lineal simple y se analiza por qué es limitado; en la Parte II se agregan términos no lineales e interacción para mejorar el ajuste.

## Primeros pasos (Ejecución local)
Estas instrucciones te permiten ejecutar los notebooks localmente.

### Herramientas utilizadas 


- **Python 3**
- **Jupyter** (Jupyter Notebook o JupyterLab)
- Paquetes: `numpy`, `matplotlib`

Ejemplo (con `pip`):
```bash
python -m pip install -U pip
python -m pip install numpy matplotlib notebook
```

### Pasos para iniciar 
1) Clona/descarga este repositorio.

2) Abre una terminal en la carpeta del proyecto.

3) Inicia Jupyter:
```bash
jupyter notebook
```

4) Abre y ejecuta (Restart & Run All) cada notebook:
- `01_part1_linreg_1feature.ipynb`
- `02_part2_polyreg.ipynb`

## Ejecución 
No incluye pruebas automatizadas 
\
La “verificación” consiste en ejecutar **todas las celdas sin errores** y confirmar que:
- Se renderizan las gráficas solicitadas.
- Se imprimen pérdidas/parametros finales y se observa convergencia.

## Tecnologías usadas
- Python
- NumPy
- Matplotlib
- Jupyter Notebook

## Autor
- Angel Cuervo

## Licencia
Uso academico

