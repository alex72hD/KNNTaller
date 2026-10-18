# Taller KNN - Clasificación de riesgo académico

Este proyecto ejecuta un notebook de machine learning para clasificar el riesgo académico de estudiantes usando el algoritmo K-Nearest Neighbors (KNN).

## Requisitos

- Python 3.10 o superior
- pip actualizado
- Jupyter / VS Code con soporte para notebooks

## Librerías necesarias

Las dependencias principales del proyecto son:

- pandas
- scikit-learn
- jupyter
- ipykernel

## Instalación

1. Abre una terminal en la carpeta del proyecto.
2. Crea un entorno virtual (opcional, pero recomendado):

```bash
python -m venv .venv
```

3. Activa el entorno virtual:

Windows (PowerShell):
```powershell
.\.venv\Scripts\Activate.ps1
```

Windows (CMD):
```cmd
.venv\Scripts\activate.bat
```

Linux/macOS:
```bash
source .venv/bin/activate
```

4. Instala las librerías:

```bash
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

## Ejecutar el notebook

Desde la raíz del proyecto, puedes abrir el notebook con Jupyter:

```bash
jupyter notebook
```

Luego abre el archivo `KNN.ipynb`.

También puedes abrirlo directamente desde VS Code y ejecutar las celdas con el kernel de Python configurado.

## Dataset

El proyecto usa el archivo:

```text
archive (2)\student_data_100000.csv
```

La variable objetivo es `risk_category`, con las categorías `Safe`, `At-Risk` y `High-Risk`. El notebook procesa columnas numéricas y categóricas, imputa valores faltantes, escala las variables numéricas y codifica las categóricas antes de entrenar el modelo.

Abre y ejecuta `KNN.ipynb` desde la carpeta raíz del proyecto para que la ruta relativa del dataset funcione.
