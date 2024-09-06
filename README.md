#Curso Data Science - Ingenias - Fundación YPF + Media Chicas

#Integrantes:
- Laura S Gómez Velázquez
- María Candela Herrera
- Sofía Vaucelles
  
###Objetivo del Proyecto:
El objetivo de este análisis es segmentar los pozos de hidrocarburos en grupos homogéneos utilizando modelos no supervisados para disminuir costos a través del cálculo necesario de agua. Con esta segmentación, se pretende lograr los siguientes objetivos específicos:
Identificar Clústeres de Pozos Similares:
Agrupar los pozos en clústeres basados en características como la profundidad, la cantidad de fracturas, el tipo de reservorio, el volumen de agua y CO2 inyectado, entre otros. Esto permitirá identificar grupos de pozos con características operativas y de rendimiento similares.

###Analizar Características de Clústeres:
Examinar y comparar las características de cada clúster para entender las diferencias y similitudes entre los grupos. Esto podría revelar patrones operacionales, geológicos o de rendimiento que podrían no ser evidentes en un análisis individual.

###Origen del Dataset:
El Dataset fue descargado de Datos.gov.ar

###Descripción del Dataset:
El Dataset contiene información de los diferentes tipos de variables, por ejemplo, la profundidad, la cantidad de fracturas, el tipo de reservorio y el volumen del agua, entre otras. Dichas variables serán analizadas a través del anáisis exploratorio de datos.

###Diccionario de Variables:

Nombre de la Columna	Descripción
id_base_fractura_adjiv	Identificador único de la fractura
idpozo	Identificador del pozo
sigla	Sigla del pozo
cuenca	Cuenca donde se encuentra el pozo
areapermisoconcesion	Área de permiso o concesión
yacimiento	Yacimiento
formacion_productiva	Formación productiva
tipo_reservorio	Tipo de reservorio
subtipo_reservorio	Subtipo de reservorio
longitud_rama_horizontal_m	Longitud de la rama horizontal en metros
cantidad_fracturas	Cantidad de fracturas
tipo_terminacion	Tipo de terminación
arena_bombeada_nacional_tn	Cantidad de arena bombeada (nacional) en toneladas
arena_bombeada_importada_tn	Cantidad de arena bombeada (importada) en toneladas
agua_inyectada_m3	Cantidad de agua inyectada en metros cúbicos
co2_inyectado_m3	Cantidad de CO2 inyectado en metros cúbicos
presion_maxima_psi	Presión máxima aplicada en psi
potencia_equipos_fractura_hp	Potencia de los equipos de fractura en caballos de fuerza (hp)
fecha_inicio_fractura	Fecha de inicio de la fractura
fecha_fin_fractura	Fecha de finalización de la fractura
fecha_data	Fecha de registro de los datos
anio_if	Año de inicio de la fractura
mes_if	Mes de inicio de la fractura
anio_ff	Año de finalización de la fractura
mes_ff	Mes de finalización de la fractura
anio_carga	Año de carga de los datos
mes_carga	Mes de carga de los datos
empresa_informante	Empresa que proporciona la información
mes	Mes de registro
anio	Año de registro

###Desarrollo:
Se comenzó con un Análisis Exploratorio de los datos (EDA) que nos permitió responder preguntas de diversos tipos como: ¿Cuántas filas y columnas tiene el dataset?, ¿Hay valores faltantes?, ¿Qué variables tomamos para nuestro objetivo final en común?, entre otras. Se utilizó modelo supervisado como regresión lineal, Random Forest y Gradient Boosting y modelo no supervisado como Knn y Análisis de Componentes PCA.
