# Optimización de Supermercados con Algoritmos Genéticos
Este proyecto permite encontrar ubicaciones óptimas para instalar 10 supermercados en la ciudad de Lima, maximizando la cobertura poblacional y la dispersión entre ellos. Se han utilizado dos enfoques evolutivos: (I) Un algoritmo genético mono-objetivo (II) Un algoritmo genético multiobjetivo NSGA-II. Los resultados se visualizan de forma interactiva mediante mapas HTML y gráficos.

## Requisitos

### Librerías necesarias 📚
1. numpy: Para manipulación de datos y cromosomas
2. pandas: Para el manejo de los datasets y resultados
3. matplotlib y seaborn: Para visualización de resultados
4. folium: Para generar mapas interactivos de ubicación
5. scipy: Para cálculo de distancias con Haversine
6. haversine: Cálculo de distancias geográficas
7. openpyxl: Para guardar resultados en Excel

### Instalación

Se debe crear un entorno virtual con **conda** y luego instalar los requisitos utilizando el archivo `env_supermercados.yml`.

```bash
# Crear el entorno
conda create --name supermercados-evo python=3.10
# Activarlo
conda activate supermercados-evo
# Instalar las dependencias desde el archivo de entorno
conda env update --file env_supermercados.yml --prune
