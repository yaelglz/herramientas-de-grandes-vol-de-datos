# Herramientas de Grandes Volúmenes de Datos

Repositorio de prácticas y proyectos desarrollados para la clase de Herramientas de Grandes Volúmenes de Datos.

## Índice de contenidos

- [Práctica 1: MNIST con NumPy](#práctica-1-mnist-con-numpy)
- [Práctica 2: PySpark](#práctica-2-pyspark)
- [Recursos y datos](#recursos-y-datos)
- [Cómo ejecutar los notebooks](#cómo-ejecutar-los-notebooks)
- [Estructura del repositorio](#estructura-del-repositorio)

## Práctica 1: MNIST con NumPy

Implementación de análisis y manipulación de datos utilizando NumPy con el conjunto de datos MNIST, un repositorio de imágenes de dígitos escritos a mano.

Ver carpeta `numpy_practica`

### Archivos:

- **numpy_mnist.ipynb** — Análisis de datos, visualización de dígitos, cálculo de promedios por clase y construcción de un clasificador basado en distancias euclidianas.
- **mnist_train_small.csv** — Versión reducida del conjunto de datos MNIST (20,000 ejemplos).

## Práctica 2: PySpark

Implementación de prácticas utilizando PySpark para el procesamiento y análisis de grandes volúmenes de datos.

Ver carpeta `pyspark`

### Archivos:

- **actividad_taxi_ny.ipynb** — Análisis de datos de viajes en taxi en Nueva York (lectura de archivos Parquet, inspección de esquemas, manejo de datos nulos).
- **lectura_escritura.ipynb** — Ejercicios de auditoría de calidad de datos, limpieza, manejo de duplicados, valores inválidos y generación de reportes.
- **practica_pyspark.ipynb** — Ejercicios básicos de PySpark (filtrado, transformación de columnas, agregaciones y agrupaciones).

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
├── pyspark/                        # Prácticas con PySpark
│   ├── actividad_taxi_ny.ipynb     # Análisis de datos NYC Taxi
│   ├── lectura_escritura.ipynb     # Auditoría y limpieza de datos
│   └── practica_pyspark.ipynb      # Uso básico de PySpark
└── README.md
```

## Notas

- Los nombres de archivos y carpetas están organizados para mantener la secuencia de la materia.
- Asegúrate de tener las librerías instaladas para evitar errores de importación al ejecutar las celdas de código.

**Autor:** Yael Gonzalez
