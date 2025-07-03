Análisis de Comportamiento Musical

Este proyecto analiza el comportamiento de escucha musical de los usuarios de las ciudades **Springfield** y **Shelbyville**. A partir de datos de streaming, se exploran patrones de consumo, diversidad musical y actividad de los usuarios, con el fin de generar **recomendaciones estratégicas** para contenido y marketing.

📌 Objetivo del proyecto

Realizar un análisis exploratorio de los datos de reproducción musical de usuarios en diferentes ciudades, con el propósito de identificar patrones de comportamiento, tendencias de consumo y posibles segmentos de usuarios. 

🗂️ Datos utilizados

Se trabajó con la base de datos proporcionados por la empresa:

`music_project_en.csv`: historial de reproducciones de canciones.

🛠️ Herramientas y tecnologías
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  
- SciPy (para pruebas estadísticas)

📈 Análisis realizados

- Análisis por Usuario: Diagrama de Distribución de actividad por usuario de cada ciudad.
- Análisis por Género Musical: Grafico de barras de géneros más escuchados en cada ciudad.
- Análisis Temporal del Consumo Musical : Análisis de días y horas pico en cada ciudad.
- Análisis por artista y canción : Análisis de 5 canciones y 10 artistas más escuchados por ciudad.
- Prueba estadística t-test (ttest_ind) para comparar si los usuarios activos entre ciudades.
- La prueba chi-cuadrado (chi2_contingency) para determinar si la distribución de reproducciones por día es igual entre ciudades.


✅ Conclusiones

🎧 1. Volumen de consumo marcadamente distinto
- Springfield muestra un volumen de reproducciones significativamente mayor que Shelbyville (más del doble).
- Esta diferencia sugiere un mayor engagement o una base de usuarios más activa, lo que puede ser útil para priorizar inversión en campañas o lanzamientos dirigidos.

📅 Patrones diferenciados de consumo por día
- Springfield presenta un patrón de consumo más equilibrado, con picos claros los lunes y viernes, lo que sugiere un hábito constante de escucha en inicios y cierres de semana. Esto lo convierte en un público ideal para estrenos regulares o promociones de inicio de semana y fines de semana.
- Shelbyville, en cambio, muestra una concentración significativa de escuchas los miércoles, revelando un comportamiento menos predecible. Esto abre la puerta a estrategias más puntuales y personalizadas.
- A pesar de estas diferencias en días de mayor actividad, ambas ciudades comparten franjas horarias similares de mayor escucha, lo que permite sincronizar horarios de lanzamientos o campañas, adaptando el día de publicación según la ciudad.

🎼 3. Diversidad musical
- Los mismos géneros aparecen como los más escuchados tanto en Springfield como en Shelbyville. Esto sugiere que, existe un núcleo de preferencias comunes. Esto permitirá crear contenido (como playlists, campañas o promociones) usando estos géneros, y es más probable que funcione bien en las dos ciudades al mismo tiempo.

📊 4. Artistas y canciones compartidos vs. específicos
- La mayoria de artistas y canciones aparecen en el top de ambas ciudades (Kartvelli, MALFA, Irina Shok, etc.), lo que sugiere un núcleo de gustos comunes.

📊 5. Diferencia en actividad de usuarios
- Springfield tiene más usuarios y más reproducciones totales, pero su comportamiento promedio por usuario es menos intenso.
- Shelbyville, aunque con menos personas, tiene usuarios que escuchan más música individualmente.

🧠 6. Los resultados del test de chi-cuadrado muestran diferencias significativas en la distribución de reproducciones musicales por día entre Springfield y Shelbyville. Esto confirma que cada ciudad presenta patrones distintos de consumo semanal, lo cual justifica enfoques diferenciados en estrategias de contenido y marketing. 

📁 Estructura del proyecto

📦 analisis-musical
├── 📄 README.md                     # Este archivo
├── 📄 music_project_en.csv          # Datos de reproducciones musicales por usuario
├── 📄 notebook.ipynb                # Análisis exploratorio y estadístico en Jupyter
├── 📄 requirements.txt              # Librerías necesarias para reproducir el análisis


📦 analisis-musical
├── 📄 README.md
├── 📄 dataset.csv
├── 📄 notebook.ipynb
└── 📁 resultados/
    ├── 📊 graficos/
    │   └── horas_por_ciudad.png
    └── 📄 resumen_estadistico.txt

    
👤 Autor
Cecilia Juliana Ruiz Carhuamaca
Estudiante de análisis de datos en TripleTen