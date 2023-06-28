# PIH-DAProyecto de Análisis de Accidentes Aéreos
Este proyecto tiene como objetivo analizar y mejorar la seguridad de los vuelos mediante el análisis de una base de datos de accidentes aéreos. El conjunto de datos proporciona información detallada sobre los accidentes, incluyendo el año del accidente, la ruta tomada, la aerolínea, el modelo del avión, la cantidad de fallecidos y las personas a bordo.

El proceso de desarrollo consta de tres partes importantes:

Para iniciar se realizo un largo proceso de ETL con el objetivo de hacer mas accesible la información y normalizar ciertas columnas para que la información sea mas precisa, se detectaron outliers y finalmente se unifico todo en una única tabla (ETL-EDA.ipynb).

En el proceso de Análisis Exploratorio(EDA) se compararon los números de fallecidos con las distintas columnas y valores que categorizaban los eventos(Fecha|Aerolinea|Avion|Ruta), con el fin de encontrar relaciones directas , indirectas o inversas entre valores y categorías con la cantidad de fallecidos,que era el dato que nos interesa reducir.

Para concluir se realizo un dashboard en powerBi con el cual se mostraron las relaciones entre estas categorías ya mencionadas(Fecha|Aerolinea|Avion|Ruta) y el numero-proporción de fallecidos

Objetivos
Analizar la tendencia de los accidentes a lo largo del tiempo y establecer un índice de accidentes por año.
Evaluar la supervivencia en los accidentes y calcular el índice de supervivencia.
Identificar las aerolíneas con mayor frecuencia de accidentes y establecer un índice de accidentes por aerolínea.
Analizar los modelos de avión asociados con la mayoría de los accidentes y calcular el índice de accidentes por modelo de avión.
Evaluar la seguridad de las rutas tomadas por las aerolíneas y establecer un índice de accidentes por ruta tomada.
Identificar las fases críticas del vuelo donde ocurren la mayoría de los accidentes y calcular el índice de accidentes por fase del vuelo.
Medir la frecuencia de los accidentes y establecer el tiempo promedio entre accidentes.
Calcular el índice de fallecidos por accidente y buscar reducirlo.
Categorizar los accidentes según el tipo de incidente y establecer un índice de accidentes por tipo de incidente.
Evaluar el cumplimiento de las regulaciones de seguridad por parte de las aerolíneas y establecer un índice de cumplimiento.
Resultados esperados
A través de este proyecto, se espera obtener una comprensión detallada de los accidentes aéreos y los factores que contribuyen a ellos. Al analizar los KPIs definidos, se buscará identificar áreas de mejora en la seguridad de los vuelos y proponer medidas correctivas. El objetivo final es reducir la cantidad de accidentes y fallecidos, mejorando así la seguridad y confiabilidad de los vuelos.

Tecnologías utilizadas
Base de datos de accidentes aéreos
Power BI para el análisis de datos y la visualización de resultados
Instrucciones de uso
Descargar el conjunto de datos de accidentes aéreos y almacenarlo en una ubicación accesible.
Configurar Power BI y abrir el archivo del proyecto.
Actualizar la conexión de datos para que apunte al conjunto de datos descargado.
Explorar los diferentes paneles y visualizaciones para acceder a los análisis y KPIs establecidos.
Utilizar los resultados obtenidos para identificar áreas de mejora y proponer acciones para mejorar la seguridad de los vuelos.
