# Análisis Exploratorio de datos - Inseguridad en Jalisco (2019 - 2023)

### Introducción y descripcíón del proyecto
<div style="text-align: justify"> La percepción que tienen los jalisciences acerca de la seguridad en Jalisco discrepa con los datos según una nota del periodico el Informador (Lomeli, J., 2023).  Esto no quiere decir que los datos del gobierno sean poco confiables o estén equivocados, si no que depende de la interpretación y objetivos a los que se desea llegar. Existe una amplia relación entre la economía y el crimen, y es por ese interés de realizar un analisis exploratorio y profundo sobre los delitos cometidos en el estado de Jalisco durante el periodo de 2019 hasta el mes de febrero 2023 a nivel municipal y colonia.
  
  Podemos pensar que zonas con deficiente y desigual cobertura de servicios básicos, concentran factores de riesgo que contribuye a las mayores tasas de crimen y violencia. La desigualdad de oportunidades, hace que la población en peor situación vea al crimen relativamente más rentable que las actividades legales a las que tendría acceso. El deterioro de los espacios urbanos, como la falta de iluminación o pavimento tiende a incrementar las probabilidades de delitos, ya que las zonas en malas condiciones, con infraestructura dañada, pueden ser un indicador de ausencia del estado y por ende, zonas de baja probabilidad de ser arrestados y condenados.   
  El objetivo de realizar el EDA es poder identificar y comprender las variables que pueden llegar a tener influencia en la delicuencia en Jalisco y posteriormente sirva de interés a investigadores y politicas públicas para plantear un modelo que prmite detectar la relación causal entre variables y delitos y resolver problemas con base a las necesidades de cada una de las regiones. </div>

### Fuente de Datos
<div style="text-align: justify"> Los datos se presentan en un archivo csv y extráidos de la sección de laboratorio de datos del portal web Plataforma de Seguridad del Instituto de Información Estadística y Geográfica de Jalisco (IIEG). https://iieg.gob.mx/plataforma_seguridad/#/laboratorio <div>  
  
### Descripción breve de la información
  
  El dataset cuenta con 294,316 registros, es decir, número de carpetas o delitos registrados durante el periodo 2019 - Febrero 2023.
  Y con las siguientes columnas o variables:
    
  + **fecha**: Periodo de los delitos cometidos (2019-01-01 hasta 2023-02-28)
  + **delito**: Tipo de delito cometido (el dataset tiene 16 diferentes tipos de delitos)
  + **x**: Longitud
  + **y**: Latitud
  + **colonia**: Colonia del municipio de Jalisco
  + **municipio**: Municipio del estado de Jalisco
  + **clave_mun**: Clave nnúmerico del municipio de Jalisco
  + **hora**: La hora aprox. en que se cometio el delito (00.00 hasta 23.59)
  + **bien_afectado**: Si fue afectado el patrimonio o hacía la persona ( si fue a su libertad, agresión sexual o integridad corporal)
  + **zona_geografica**: Si el delito fue cometido en la Área Metropolitana de Guadalajara (AMG) o en el resto de los municipio (Interior)
  
### Resumen de resultados 
Entre los resultados más destacados del análisis EDA se encuentran los siguientes puntos:
  1. Existe una reducción de los delitos totales en 2020 (por mitigación de la pandemia) y después del segundo semestre del 2020 hay una ligera alza que se ha mantenido durante los otros próximos dos años.
  2.  Los delitos que mayormente se cometieron durante el periodo analizado fue: Robo de vehículos, Violencia Familiar y el robo a personas y negocios
  3. Se observa que la mayoria de los delitos se han cometido en la zona metropolitana de Guadalajara por encima de los otros municipios, sin embargo llama la atención que el delito de abuso sexual infantil el resto de los municipios se encuentrán por encima del área metropolitana de Guadalajara (una posible causa se puede deber a que en cierto municipios todavía existe el matrimonio de adultos con menores de edad).
  4. Los delitos frecuentemente se cometieron durante los primeros dias de inicio de la semana (lunes y martes) en un horario aproximadamente de la madrugada (12:00 a.m) y por la noche.
  5. Si existe una reducción en los delitos que son ocasioados a bienes patrimoniales como el robo a vehículos, homocidios, feminicidios sin embargo en temas de Violación, Violencia Familiar, Abuso sexual a menores, lesiones dolosas (afectaciones de integridad personal y sexual).
  6. Se tomaron los delitos de Violencia familiar y violacíón debido al punto explicado anteriormente y se identifica con el mapa de calor la concentración de estos dos delitos en la amg y en cada uno de los centros de los municipios, dando lugar a que este tipo de delito se comente en la mayor parte del Estado de Jalisco.
  7. Se identifico las colonias de Oblatos y Zona Centro con mayor registro de delitos de violencia familiar en el municipio de Guadalajara.
  
 
  
  
  
  
  
![](C:/Users/eduri/OneDrive/Documents/Semestre IV/DPII/Imagenes_EDA/Tipo_delitos.png)
  
  
  
![](https://media.giphy.com/media/CCFFPwOK9xbamQksxU/giphy-downsized-large.gif)

Source: [Giphy](https://media.giphy.com/media/CCFFPwOK9xbamQksxU/giphy-downsized-large.gif)
  
  
