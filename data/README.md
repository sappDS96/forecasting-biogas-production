# Datos

Los datos proceden del conjunto público [Laboratory, operational, and SCADA datasets for anaerobic co-digestion at the Muscatine, IA Water Resource Recovery Facility](https://doi.org/10.25820/data.006715).

La carpeta `raw/` incluye LABS, los dos diccionarios y la documentación original. El archivo `SCADA-raw.csv` no se versiona porque ocupa aproximadamente 85 MB. Para reproducir el análisis completo:

1. Descarga los archivos desde la fuente original.
2. Copia `SCADA-raw.csv` en `data/raw/`.
3. Ejecuta el notebook principal desde `notebooks/` o desde la raíz del repositorio.

La carpeta `processed/` contiene las tablas generadas por el notebook para Power BI. Las tablas del subdirectorio `backtesting/` corresponden al anexo metodológico.

