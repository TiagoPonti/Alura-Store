# Alura-Store
Challenge from Oracle Next Education Data Science

Descripción del Proyecto:
Este proyecto consiste en un análisis de datos integral para evaluar el rendimiento de cuatro tiendas de AluraStore Latam. El objetivo principal fue determinar cuál de las tiendas ofrece la mejor oportunidad de venta para un inversor, basándose en el balance entre volumen de ingresos y eficiencia operativa. El análisis incluyó la evaluación de ingresos totales, costos de envío promedio, satisfacción del cliente (calificaciones) y patrones geográficos de venta.

Conclusión principal: Se recomienda la venta de la Tienda 1. Aunque presenta la calificación de cliente más baja ($\approx 3.98$) y el costo de envío más alto ($\approx 26,018$), su capacidad probada de generar el mayor volumen de ingresos ($1.15 Mil Millones) la convierte en el activo más valioso. Sus fallas son de naturaleza operacional y logística, lo cual es un problema sanable para un nuevo comprador.

Prerrequisitos
Para ejecutar este proyecto de análisis, se requiere tener instalado Python y las siguientes librerías:
pandas: Para manejo y manipulación de DataFrames.
matplotlib: Para la creación de gráficos estáticos (barras, dispersión).
numpy: Para operaciones numéricas eficientes.
seaborn: (Opcional) Utilizado para visualizaciones estadísticas o mapas de calor.

Instalación
Siga estos pasos para configurar el entorno local:
Clonar el repositorio: https://github.com/TiagoPonti/Alura-Store
Instalar dependencias:
Estructura de datos: El notebook asume que los archivos de datos (CSV) de las cuatro tiendas están disponibles y se cargan correctamente en las primeras celdas.

Cómo Utilizar
El análisis completo se encuentra en el archivo principal: AluraStoreLatam.ipynb.
Abrir el Notebook: Inicie su entorno de Jupyter (JupyterLab o Jupyter Notebook).
Ejecutar celdas: Ejecute todas las celdas del notebook en orden para reproducir el proceso de limpieza de datos, el cálculo de métricas clave (facturación, costo de envío, calificación), la generación de los gráficos de comparación y el Análisis Geográfico por tienda.
Caso de Uso Clave (Geointeligencia)
La sección final del notebook genera un subplot de 4 gráficos geográficos. Analice este gráfico para ver la distribución de puntos grandes (alto volumen de ventas) y su color (calificación). Si el punto es grande y rojo, es un problema operacional concentrado que justifica la venta de la Tienda 1.
