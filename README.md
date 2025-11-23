# Precios-Paltas
Precios Paltas- Laboratorio II

Contexto:

Este análisis es un estudio de precios de la Palta para una cadena de supermercados que busca incorporar el producto mencionado al área de verduleria.

ETL:

Se realizaron las siguientes acciones:
- Se pusieron los nombres de los encabezados convirtiendo la 1er fila en Título
- Se quitaron columnas irrelevantes como el Nro de muestras, se juntaron columnas como las de PLU y se crearon nuevas como las de Tipo de Empaques
- Se cambiaron nombres de columnas y tipos de datos de las mismas
- Se eliminaron datos nulos dónde era necesario como en la columna region

Modelado de Datos:
A partir de la tabla avocado se crearon 5 tablas que se utilizaron en el informe:
- Región
- Tipo
- Calendario
- Empaque
- Variedad Palta

Se formó, de esta manera, 5 fuentes de datos que se relacionaban con la tabla avocado.

Medidas Dax:
Se crearon las siguientes medidas DAX para utilizar en el informe:
- Cantidad de Ciudades
- Precio Máximo por Unidad
- Precio Mínimo por Unidad
- Precio Promedio por Unidad

EDA:


Se busca contestar las preguntas:
- ¿Cuál es el precio promedio por Unidad?
- ¿Cuál es el precio máximo por Unidad?
- ¿Cuál es el precio mínimo por Unidad?
- ¿Cuál es el precio promedio por región?
- ¿Cuál es el precio promedio por ciudad?
- ¿Cómo evoluciona el precio a lo largo del año?
