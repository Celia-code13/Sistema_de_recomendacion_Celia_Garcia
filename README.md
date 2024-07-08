# Sistema de Recomendación de Películas

Este proyecto consiste en desarrollar un sistema de recomendación de películas que proporciona sugerencias personalizadas a los usuarios basadas en sus calificaciones anteriores.

El sistema utiliza un enfoque de filtrado colaborativo basado en ítems para generar recomendaciones. Este método analiza las calificaciones dadas por los usuarios a diferentes películas y encuentra similitudes entre ellas para sugerir nuevas películas que podrían interesar al usuario.

## Estructura del Proyecto

El proyecto contiene los siguientes archivos y directorios:

- `Sistema_Recomendación.ipynb`: Un notebook de Jupyter que contiene el desarrollo completo del sistema de recomendación
- `sistema_recomendación.py`: Un archivo de Python que contiene el mismo código y lógica que el notebook.
- `Data/`:
  - `ratings.csv`: Calificaciones dadas por los usuarios a las películas.
  - `movies.csv`: Información sobre las películas, como título y género.
- `requirements.txt`

Puedes instalar todas las dependencias necesarias ejecutando:
```bash
pip install -r requirements.txt
