# Jupyter Notebook Tutorial
[![Python Version](https://img.shields.io/badge/python-3.10%2B-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-%23F37626.svg?style=flat&logo=Jupyter&logoColor=white)](https://jupyter.org)

Este repositorio contiene una Jupyter Notebook con instructivos detallados para su ejecución.

[![Static Badge](https://img.shields.io/badge/Informe-blue?logo=google-docs&logoColor=white&labelColor=gray)](https://docs.google.com/document/d/1H-vcH9u7PSGkIGuk4LZ_umzvTlm-VURD1IMFDXtZObA/edit?tab=t.0)


## Requisitos Previos

Antes de comenzar, asegúrate de tener instalado:

1. Python 3.10 o superior
2. pip (gestor de paquetes de Python)

## Instalación

1. Clona este repositorio:
```bash
git clone https://github.com/tecdaz/tpCienciasDeDatos.git
cd tpCienciasDeDatos
```

2. Crea un entorno virtual (recomendado):
```bash
python -m venv venv

# En Windows
venv\Scripts\activate

# En macOS/Linux
source venv/bin/activate
```

3. Instala las dependencias necesarias:
```bash
pip install -r requirements.txt
```

## Uso

1. Inicia Jupyter Notebook:
```bash
jupyter notebook
```

2. En tu navegador, abre el archivo `nombre_notebook.ipynb`

3. Para ejecutar todas las celdas:
   - Utiliza el menú `Cell > Run All`
   - O usa el atajo de teclado `Shift + Enter` para ejecutar celda por celda


## Solución de Problemas Comunes

- **Error: No se puede abrir el notebook**
  - Verifica que Jupyter está instalado correctamente
  - Asegúrate de que el entorno virtual está activado

- **Error: Módulo no encontrado**
  - Ejecuta `pip install -r requirements.txt` nuevamente
  - Verifica que el entorno virtual está activado
