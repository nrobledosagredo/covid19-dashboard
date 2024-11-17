# Dashboard interactivo COVID-19

![Python](https://img.shields.io/badge/language-Python-blue)
![Data Visualization](https://img.shields.io/badge/topic-Data%20Visualization-green)

Dashboard interactivo para visualizar la evolución de los casos confirmados, recuperados y decesos por COVID-19 en distintos países, utilizando gráficos dinámicos.
Este proyecto utiliza **Jupyter Notebooks** y **Voila** para crear un dashboard interactivo que permite comparar la evolución de la pandemia en diferentes países. Los usuarios pueden elegir entre mostrar **casos acumulados** o **casos nuevos**.

## Funcionalidades

- Visualización interactiva de **casos confirmados**, **recuperados** y **decesos**.
- Comparación de datos entre dos países.
- Opciones de visualización por **casos acumulados** o **casos nuevos**.
- Basado en datos de COVID-19 de diversas fuentes.

## Requisitos

- **Python 3.8.5** o superior.
- Dependencias incluidas en `requirements.txt`:
   ```text
   pytest
   numpy
   matplotlib
   ipympl
   pandas
   voila
   voila-material
   mplcursors
  ```

## Ejecución

Para ejecutar el dashboard en tu máquina local, usa el siguiente comando:

```bash
voila --port=8866 --Voila.ip=0.0.0.0 --no-browser --template=material notebooks/tu_archivo.ipynb
```

El dashboard estará disponible en http://localhost:8866.