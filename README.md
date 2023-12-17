# Comparativa de Algoritmos para el Problema del Viajante de Comercio (TSP)
Este repositorio contiene informes detallados sobre la implementación y evaluación de cuatro algoritmos para abordar el Problema del Viajante de Comercio (TSP): Temple Simulado, Búsqueda Tabú, Algoritmo Genético y Algoritmo de Colonias de Hormigas (ACS).

## Comparativa Final
En la sección final del informe del ACS, se presenta una comparativa con los otros tres algoritmos. Se analizan métricas como el tiempo de ejecución, la calidad de las soluciones encontradas y la estabilidad del rendimiento. Esta comparativa ofrece una visión integral de la eficacia de cada algoritmo en distintas instancias del TSP.

## Cómo Ejecutar los Experimentos con Docker y Jupyter Notebook
Clona este repositorio a tu máquina local:
``` bash
git clone https://github.com/davidpacios/Problema-Viajante-Comercio-TSP.git
cd Problema-Viajante-Comercio-TSP
```

Ejecuta el contenedor de Docker con Jupyter Notebook:

```bash
docker run -p 8888:8888 -v $(pwd):/home/jovyan/work jupyter/base-notebook
```
