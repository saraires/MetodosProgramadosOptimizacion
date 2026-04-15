# Taller 1 — Métodos de Optimización

Taller práctico de métodos numéricos aplicados a la optimización de funciones y localización de raíces, desarrollado en Python con Jupyter Notebook.

## Integrantes

- Santiago Palacio Cárdenas
- Dayana Ramírez Areiza
- Sarai Restrepo Rodríguez

## Contenido

| Ejercicio | Tema | Función |
|-----------|------|---------|
| 1 | Multiplicadores de Lagrange | $f(x,y) = 4x + 3y$ sujeta a $g(x,y) = 2x^2 + 4y^2 - x + 4y = 0$ |
| 2 | Localización de raíces (Bisección, Falsa Posición, Newton-Raphson) | $f(x) = x^{10} - 3x^4$ |
| 3 | Optimización con función elegida (Sección Dorada, Newton, Interp. Cuadrática) | $f(x) = x^4 - 4x^3 + 2x^2 + 4x + 1$ |
| 4 | Optimización y localización de raíces | $f(x) = -1.5x^3 - 2x^2 + 12x - 3$ |
| 5 | Función trigonométrica — raíces y optimización | $f(x) = 2\sin(x) - x/4$ |
| 6 | Función hiperbólica — raíces y optimización | $f(x) = \tanh(x^2 - 7)$ |
| 7 | Polinomio de cuarto grado — análisis de tolerancia | $f(x) = 3 + 6x + 5x^2 + 3x^3 + 4x^4$ |
| 8 | Función exponencial — comportamiento sin extremos | $f(x) = 3e^x - 7/3$ |
| 9 | Optimización multivariable (búsqueda aleatoria, gradiente) | $f(x,y) = 4x + 2y + x^2 - 2x^4 + 2xy - 3y^2$ |

## Métodos implementados

- **Localización de raíces:** Bisección, Falsa Posición, Newton-Raphson
- **Optimización univariable:** Sección Dorada, Newton para optimización, Interpolación Cuadrática
- **Optimización con restricciones:** Multiplicadores de Lagrange
- **Optimización multivariable:** Búsqueda Aleatoria, análisis de Ascenso por Gradiente

## Tecnologías

- Python 3
- NumPy
- SymPy
- Matplotlib