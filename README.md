# Cotizador de Seguro Médico

Este proyecto es una aplicación web que permite calcular el costo estimado de un seguro médico utilizando un modelo de regresión lineal entrenado con datos históricos.

## Estructura del proyecto

- `app.py`: Script principal de la aplicación web (Flask).
- `ml-test.py`: Script para pruebas relacionadas con el modelo de machine learning.
- `model/`: Carpeta que contiene los archivos del modelo entrenado (`insurance-ml.pkl`, `scaler_x.pkl`, `scaler_y.pkl`).
- `notebook/`: Incluye el notebook de entrenamiento y análisis del modelo (`insurace_ml.ipynb`).
- `templates/`: Archivos HTML para la interfaz web (`index.html`).
- `requirements.txt`: Dependencias necesarias para ejecutar el proyecto.
- `.gitignore`: Archivos y carpetas ignorados por git.

## Instalación

1. Clona el repositorio.
2. Instala las dependencias:
   ```sh
   pip install -r requirements.txt
   ```
3. Ejecuta la aplicación:
   ```sh
   python app.py
   ```

## Uso

Accede a la aplicación web en tu navegador. Ingresa tu edad en el formulario para obtener una estimación del costo mensual del seguro médico.

## Entrenamiento del modelo

El modelo fue entrenado usando regresión lineal simple con la variable `age` para predecir el costo (`charges`). El proceso de entrenamiento y evaluación se encuentra documentado en el notebook [`notebook/insurace_ml.ipynb`](notebook/insurace_ml.ipynb).

## Licencia

Este proyecto es solo para fines educativos.

## Autor

Gabriel Grados Machado.
