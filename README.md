# Sprint7-Final_Proyect

Proyecto Sprint 7

Análisis de datos para ConnectaTel Latinoamerica

- Obejtivo: evaluar el comportamiento de los clientes de la empresa con datos registrados hasta el año 2024.
- Data Sets utilizados para el análisis:
  - plans.csv → información de los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra)
  - users.csv → información de los clientes (edad, ciudad, fecha de registro, plan, churn)
  - usage.csv → detalle del uso real de los servicios (llamadas y mensajes)
 
- Etapas del análisis:
  - Revisión y exploración de datos, datos ausentes, nulos y/o inválidos
  - Evaluación y apliación de estrategia para manejo de datos ausentes y/o inválidos
  - Modificación de tipo de datos para fechas y valores numéricos necesarios para el análisis
  - Revisión de parámetros aritméticos, exploración y gráficos de datos para visualizar comportamietos de usuarios y outliers
  - Segmentación por edad y uso
  - Unión de la información final en un nuevo df user_profile con información limpia, clara y segmentada.

- Para reproducir este análisis:
  1. Abre el notebook en Google Colab usando este enlace: https://colab.research.google.com/drive/16W05ypmywprwvUff-4oq1cT9vDbf9tlc
  2. Descarga el archivo plans.csv, users.csv y usage.csv obtenidos en la plataforma de TripleTen para este proyecto y súbelo a la carpeta de archivos de Colab (ícono de carpeta a la izquierda).
  3. Asegúrate de tener instaladas las librerías: pandas, numpy, seaborn, matplotlib.pyplot
  4. Ejecuta las celdas en orden, de arriba hacia abajo (Entorno de ejecución > Ejecutar todas).
