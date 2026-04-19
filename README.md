# Herramientas de Grandes Volúmenes de Datos

Repositorio de prácticas y proyectos desarrollados para la clase de Herramientas de Grandes Volúmenes de Datos.

## Índice de contenidos

- [Práctica 1: MNIST con NumPy](#práctica-1-mnist-con-numpy)
- [Recursos y datos](#recursos-y-datos)
- [Cómo ejecutar los notebooks](#cómo-ejecutar-los-notebooks)
- [Estructura del repositorio](#estructura-del-repositorio)

## Práctica 1: MNIST con NumPy

Implementación de análisis y manipulación de datos utilizando NumPy con el conjunto de datos MNIST, un repositorio de imágenes de dígitos escritos a mano.

Ver carpeta `numpy_practica`

### Archivos:

- **numpy_mnist.ipynb** — Análisis de datos, visualización de dígitos, cálculo de promedios por clase y construcción de un clasificador basado en distancias euclidianas.
- **mnist_train_small.csv** — Versión reducida del conjunto de datos MNIST (20,000 ejemplos).

## Recursos y datos

- **mnist_train_small.csv**: Archivo CSV que contiene las etiquetas y los píxeles (28x28) de las imágenes de dígitos.

## Cómo ejecutar los notebooks

1. Clona este repositorio o descarga el ZIP.
2. Crea y activa un entorno (opcional pero recomendado), por ejemplo con conda o venv.
3. Instala Jupyter y las dependencias necesarias:
   ```bash
   pip install numpy matplotlib
   ```
4. Inicia Jupyter Lab o Notebook:
   ```bash
   jupyter notebook
   ```
5. Navega hasta la carpeta `numpy_practica`, abre el notebook `numpy_mnist.ipynb` y ejecuta las celdas.

## Estructura del repositorio

```text
herramientas-de-grandes-vol-de-datos/
├── numpy_practica/                 # Práctica con NumPy y MNIST
│   ├── mnist_train_small.csv       # Dataset reducido de MNIST
│   └── numpy_mnist.ipynb           # Notebook con la resolución de la práctica
└── README.md
```

## Notas

- Los nombres de archivos y carpetas están organizados para mantener la secuencia de la materia.
- Asegúrate de tener las librerías instaladas para evitar errores de importación al ejecutar las celdas de código.

**Autor:** Yael Gonzalez
