# Taller KNN - Clasificación de riesgo crediticio

Este proyecto ejecuta un notebook de machine learning para clasificar riesgo crediticio usando el algoritmo K-Nearest Neighbors (KNN).

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
archive (1)\Financial Risk Classification Dataset.csv
```

Si aparece un error como `FileNotFoundError`, asegúrate de ejecutar el notebook desde la carpeta raíz del proyecto y que la ruta del dataset no haya sido movida.

## Nota

El notebook ya está preparado para trabajar con una base de datos de riesgo crediticio, donde la columna objetivo es `loan_default`.
