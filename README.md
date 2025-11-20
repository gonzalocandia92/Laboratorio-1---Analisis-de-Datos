# 📊 Laboratorio de Análisis de Datos — Ventas Mayoristas (Clientes y Ventas)

Descripción del proyecto  
Este repositorio contiene un análisis exploratorio de datos (EDA) y un proceso ETL elaborado en un notebook (Laboratorio1.ipynb) sobre un conjunto de datos de clientes y ventas mayoristas. El objetivo principal es evaluar el comportamiento de las ventas, identificar patrones por región y producto, extraer KPIs relevantes y detectar oportunidades de crecimiento o mejora en la operación comercial.

El flujo de trabajo aplicado incluye:
- Extracción de archivos CSV (clientes y ventas).
- Limpieza y transformación de columnas (normalización de texto, conversión de fechas).
- Detección y manejo de duplicados y valores nulos.
- Agregaciones y cálculo de métricas (totales, promedios, etc.).
- Visualizaciones para apoyar la interpretación de resultados (desde el notebook).

Estructura del repositorio
Proyecto_Laboratorio/  
├── Laboratorio1.ipynb      # Notebook principal con el análisis completo  
├── Input/                  # Carpeta con los datasets CSV  
│   ├── clientes.csv  
│   └── ventas_mayorista.csv  
├── Output/                 # Carpeta con datasets transformados / resultados  
│   └── ...  
└── README.md               # Este archivo

Tecnologías y librerías principales
- Python
- pandas — manipulación y transformación de datos
- numpy — cálculos numéricos
- chardet — detección de encoding de archivos CSV
- google.colab — entorno sugerido para ejecutar el notebook
(Opcional: matplotlib / seaborn para visualizaciones si se agregan gráficas en el notebook)

Guía de Uso
Para replicar este análisis, seguí los siguientes pasos:

1. Cloná este repositorio en tu máquina local:
   https://github.com/gonzalocandia92/Laboratorio-1---Analisis-de-Datos.git

2. Abrí el archivo Laboratorio1.ipynb en Google Colab.

3. Asegurate de que los archivos clientes.csv y ventas_mayorista.csv estén dentro de la carpeta Input del repositorio o en la ruta que se indique en el notebook.  
   - En Google Colab el notebook incluye la opción de montar Google Drive; también podés subir los CSV al entorno.

4. Ejecutá las celdas del notebook de forma secuencial para reproducir todo el flujo ETL y el análisis:
   - Extracción: carga de CSV y detección de encoding.
   - Transformación: limpieza de columnas, normalización de texto y conversión de fechas.
   - Validación: revisión de duplicados y nulos.
   - Análisis: agregaciones y generación de métricas/KPIs.

Archivos de entrada esperados
- Input/clientes.csv — información de clientes (id_cliente, nombre_cliente, provincia, localidad, categoría)
- Input/ventas_mayorista.csv — registros de ventas (fecha_hora, id_cliente, producto, categoría_producto, cantidad, precio_unitario, total)

Objetivos del análisis
- Analizar el comportamiento de ventas por producto, categoría y región.
- Identificar patrones y zonas con mayor volumen de transacciones.
- Detectar clientes o segmentos con potencial para expansión comercial.
- Extraer KPIs operativos (ventas totales, ticket promedio, productos más vendidos, etc.) y conclusiones basadas en evidencia para apoyar la toma de decisiones.

Autor
Candia Gonzalez Gonzalo Ismael  



