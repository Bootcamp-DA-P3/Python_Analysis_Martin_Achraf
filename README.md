# Python_Analysis_Martin_Achraf

Realizado por: Martín Fernández Crespo y Achraf Azzouz con asistencia de Google Gemini Pro 3.1

El notebook y el dataset se encuentran en el presente repositorio además de este enlace a la carpeta de Google Drive con el notebook y el dataset para ser añadido al Google Colab para su ejecución: https://drive.google.com/drive/folders/1044D0NvlskbilYTpTimh-6P4UhTT8yzs?usp=drive_link

Este proyecto aplica las mejores prácticas de limpieza, preparación y visualización de datos utilizando Python en Google Colab. El objetivo es transformar un conjunto de datos bruto de Kiva Crowdfunding en información estructurada y lista para su análisis.


Dataset Utilizado: Se ha trabajado con el archivo kiva_loans_42304_rows.csv, que contiene más de 42.000 registros sobre microcréditos de Kiva (importes, fechas, países, sectores y plazos).

Pasos Ejecutados en el Notebook: Importación y Exploración: Carga del archivo CSV y revisión inicial de dimensiones, tipos de datos y estadísticas básicas con Pandas.

Limpieza y Corrección:

-Conversión de columnas de texto a formato fecha real (datetime).

-Normalización de textos (minúsculas y eliminación de espacios).

-Filtrado de valores extremos (eliminación de préstamos de más de 20.000$ o plazos superiores a 60 meses).

-Creación de Nuevas Variables: Extracción de años y meses, cálculo de los días que tarda un préstamo en financiarse y categorización de los importes.

-Gráficos y Análisis: Uso de Matplotlib y Seaborn para crear histogramas, gráficos de caja y análisis de correlación (pairplot).

-Validación y Exportación: Comprobación de que no existieran errores mediante pruebas automáticas y guardado del archivo limpio (kiva_loans_limpio_final.csv).
