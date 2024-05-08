# desafio_ingdatos_3
demostración rápida de cómo implementar un proceso ETL con Python para el dataset de títulos de Netflix

Para hacer un proceso ETL en un archivo de notebook de Visual Studio Code, usaremos la extensión de Jupyter en VS Code.

Base de datos: https://www.kaggle.com/datasets/rahulvyasm/netflix-movies-and-tv-shows?resource=download

### Estructura del Proyecto

1. **`desafio_ingdatos_3/`**
   - `etl_notebook.ipynb`: Archivo de notebook con el código ETL.
   - `.env`: Archivo para almacenar las credenciales de la base de datos.
   - `requirements.txt`: Lista de dependencias necesarias para el proyecto.

### Contenido de `etl_notebook.ipynb`

Para el código en el notebook, dividiremos el proceso en celdas que permitan ejecutar cada paso (extracción, transformación y carga)


### Cómo Usar el Notebook

1. Asegúrate de que tienes la extensión de Jupyter instalada en VS Code.
2. Instala las dependencias listadas en `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```
3. Configura las credenciales de la base de datos en el archivo `.env`.
4. Abre el archivo `etl_notebook.ipynb` en Visual Studio Code.
5. Ejecuta cada celda individualmente para observar el flujo ETL.

