# Python Data Analytics

Repositorio de formación y práctica orientado al desarrollo de las competencias necesarias para trabajar como **Junior Data Analyst**.

El proyecto reúne la documentación de estudio, ejercicios guiados y prácticas de análisis de datos utilizando Python y sus principales librerías.

## Objetivos

- Aprender y consultar los fundamentos de Python aplicados al análisis de datos.
- Comprender y utilizar librerías como NumPy, Pandas, Matplotlib y Seaborn.
- Practicar la exploración, limpieza, transformación y análisis de datos.
- Resolver ejercicios progresivos con situaciones y datos de contexto empresarial.
- Mantener un entorno de trabajo reproducible y una documentación organizada.

## Estructura del proyecto

```text
python_data_analytics/
│
├── README.md
│
├── documentacion/
│   ├── 01_entorno_de_trabajo.ipynb
│   └── 02_librerias_de_python.ipynb
│
├── practice/
│   ├── python/
│   │   ├── 01_fundamentos/
│   │   │   └── python_fundamentos.ipynb
│   │   ├── 02_condicionales_y_bucles/
│   │   ├── 03_estructuras_de_datos/
│   │   └── 04_funciones/
│   │
│   ├── numpy/
│   │   ├── arrays_y_operaciones/
│   │   └── estadistica_basica/
│   │
│   ├── pandas/
│   │   ├── 01_fundamentos/
│   │   ├── 02_consulta_y_seleccion/
│   │   ├── 03_limpieza_de_datos/
│   │   ├── 04_transformacion_de_datos/
│   │   ├── 05_agrupaciones_y_agregaciones/
│   │   └── 06_analisis_exploratorio/
│   │
│   ├── matplotlib/
│   └── seaborn/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── reports/
│
├── src/
│
├── tests/
│
├── requirements.txt
└── .gitignore
```

La estructura podrá ampliarse a medida que avancemos en el temario. No es necesario crear desde el principio todos los notebooks o subdirectorios: se añadirán cuando exista contenido que lo justifique.

## Organización del contenido

### `documentacion/`

Contiene los notebooks de referencia que explican los conceptos y herramientas.

Cada notebook combina explicaciones, sintaxis, ejemplos y pequeñas tablas de datos cuando ayudan a entender el concepto. Su objetivo es servir como material de consulta y estudio.

### `practice/`

Contiene ejercicios y prácticas para aplicar lo aprendido.

Cada notebook plantea un problema o una serie de ejercicios y desarrolla la resolución mediante código. Los ejercicios se organizan por tecnología y temática para facilitar su consulta y ampliación.

### `data/`

Almacena los conjuntos de datos utilizados en los ejercicios y prácticas.

- `raw/`: datos originales, sin modificar.
- `processed/`: datos generados o transformados durante el trabajo.

Para ejemplos pequeños, los datos pueden definirse directamente dentro del notebook. Se utilizarán archivos externos cuando el volumen, la reutilización o la complejidad de los datos lo hagan conveniente.

### `src/`

Código Python reutilizable que, cuando tenga sentido, se extraiga de los notebooks para organizarlo en módulos.

### `reports/`

Resultados, conclusiones o informes derivados de las prácticas de análisis.

### `tests/`

Pruebas para comprobar el funcionamiento del código reutilizable.

## Tecnologías

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- VS Code
- Git y GitHub

## Forma de trabajo

1. Estudiar los conceptos en `documentacion/`.
2. Aplicarlos mediante ejercicios en `practice/`.
3. Utilizar tablas pequeñas directamente en los notebooks cuando sea suficiente.
4. Guardar en `data/raw/` los datasets externos originales.
5. Guardar en `data/processed/` los datos resultantes de los procesos de limpieza o transformación.
6. Documentar los resultados y conclusiones cuando la práctica lo requiera.

## Entorno de desarrollo

El proyecto utiliza un entorno virtual propio para instalar y mantener sus dependencias.

Para instalar las dependencias registradas en `requirements.txt`:

```bash
pip install -r requirements.txt
```

En VS Code, seleccionar el intérprete del entorno virtual y utilizarlo como kernel de los notebooks de Jupyter.

## Progresión de aprendizaje

El contenido se desarrollará progresivamente, desde los fundamentos de Python hasta el análisis de datos:

1. Entorno de trabajo y herramientas.
2. Fundamentos de Python.
3. NumPy.
4. Pandas.
5. Consulta, limpieza y transformación de datos.
6. Análisis exploratorio.
7. Visualización con Matplotlib.
8. Visualización estadística con Seaborn.

Los apartados se incorporarán conforme se estudien y practiquen. La estructura no implica que todo el temario esté completado.
