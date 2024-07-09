# Analisis_ETL

El caso que se presentará a continuación consiste en poblar una dimensión de clientes de un banco portugués para una campaña de marketing. Este banco posee 50 clientes identificados con un ID para cada cliente, sexo, nivel educacional, estado civil, edad y otros atributos descritos en el archivo bank-additional-names.txt. Ahora, este banco tiene 3 fuentes de datos (bank-A.csv, bank-B.csv y bankC.csv) donde se complementa la información, por lo que ninguna es suficiente por sí misma. Las fuentes de datos corresponden a 3 archivos csv, las cuales se encuentran en el sitio web del curso.

La idea de este miniproyecto es que se realice una conexión a las 3 fuentes de datos, se limpien los datos, se consolide la información y se obtenga una base de datos única. En este caso, se procederá a exportar un archivo csv o Excel, que contenga el resultado. Hay que considerar si efectivamente todas las bases de datos entregan información relevante para la consolidación del set final.

El formato final que se debe obtener se encuentra en el archivo output.csv (el archivo de salida output.csv no se encuentra normalizado, pero el archivo de salida pedido debe ir normalizado).

Recuerda descargar el archivo Miniproyecto1.zip para desarrollar tu trabajo.

Trabajo a realizar:
Usando Python en Jupyter Notebook o Google Colab, se espera que se realicen los siguientes pasos:

Cargar las librerías a utilizar, se debe comentar y explicar la elección de ellas.
Cargar y revisar cada fuente de datos, ver su contenido, características y definir si será utilizado para complementar la información. Debe justificar la toma de la decisión. Además, describir los datos, caracterizarlos y explicarlos.
Realizar dos gráficas que muestren las características de los datos, explicando cada gráfico.
Unir las fuentes de información a partir de un atributo único.
Filtrar los atributos que deben ser utilizados
Limpiar y depurar la base de datos unida, verificando datos faltantes, datos NaN, desconocidos, erróneos, duplicados, datos redundantes, etc. Debe justificar esta toma de decisión.
Homogeneizar los datos, para dejarlos con la estructura indicada en el archivo output.csv. Respetar la estructura y los espacios señalados.
Finalmente normalizar, justificando el tipo de normalización escogida. Normalizar los datos numéricos, explicar el tipo de normalización utilizada (recordar que es normalización de datos y no normalización de base de datos, i.e. Standard Scaler, MinMax Scaler, etc.)
Generar un archivo de salida csv o Excel.
