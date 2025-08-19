# alura_first_proyect
Proyecto de Análisis de Tiendas Alura Store

¡Hola! 👋 Este es mi proyecto para el Desafío Alura Latam donde analicé los datos de 4 tiendas para ayudar al Sr. Juan a decidir cuál vender.
📋 Qué hace el proyecto
📊 Analiza ingresos, ventas por categoría, opiniones de clientes y costos de envío.

📍 Opcional: Mapa de ventas por ubicación (latitud/longitud).
🎯 Conclusión: Recomendé vender la Tienda 4 (porque tiene menos ganancias y productos poco populares).

🛠️ Cómo lo hice
Usé Python con estas librerías:

python
import pandas as pd  # Para los datos
import matplotlib.pyplot as plt  # Para gráficos simples
# Opcional: seaborn y folium para mapas chidos

📂 Archivos importantes
analisis_tiendas.ipynb: Código completo con explicaciones.

data/: Datos de cada tienda en CSV (¡son muchos registros!).
mapas/: Si haces la parte opcional, guarda aquí los mapas HTML.

🔍 Resultados clave
Tienda 4 es la peor:
Menos ingresos ($1,038M vs $1,150M de la Tienda 1).
Productos como "Refrigerador" casi no se venden
Mapas (extra):
La Tienda 1 vende más en ciudades grandes (¡por eso gana más!).

🚀 Cómo ejecutarlo
Clona el repo:
git clone https://github.com/tuusuario/alura-store-analysis.git

Abre el Jupyter Notebook:
jupyter notebook analisis_tiendas.ipynb

🤔 Dificultades
Al principio no sabía cómo usar groupby en Pandas (pero ya le entendí!).
