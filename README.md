
# INTRODUCCION: Flujos Migratorios

- Según la estimación más reciente, en 2020 había en el mundo aproximadamente 281 millones de migrantes internacionales, una cifra equivalente al 3,6% de la población mundial.
- Globalmente, el número estimado de migrantes internacionales ha aumentado en las últimas cinco décadas. El total estimado de 281 millones de personas que vivían en un país distinto de su país natal en 2020 es superior en 128 millones a la cifra de 1990 y triplica con creces la de 1970.

![Migraciones globales](https://user-images.githubusercontent.com/113458958/236061867-e62b4aec-8f08-403a-8d4d-fc0b6244b5b3.PNG)

![Migrantes internacionales](https://user-images.githubusercontent.com/113458958/236061906-f924311d-db4e-4804-a7b6-970f4f9d604b.PNG)

- Los Estados Unidos de America hacia el principal detino de los migrantes internacionales desde 1970, pasando de 12 millones en 1970 a cerca de 51 millones en 2020. Alemania ocupa el segundo lugar con 9 millones en el 2000 a casi 16 millones en el 2020.

- La gran mayoría de las personas que migran no cruzan fronteras internacionales, sino que permanecen dentro de sus países (se ha estimado que en 2009 había 740 millones de migrantes internos). Dicho esto, el aumento de los migrantes internacionales a lo largo del tiempo – tanto en cifras absolutas como proporcionalmente – ha sido evidente, y algo más rápido de lo que se había pronosticado

# DESARROLLO DEL PROYECTO

## Objetivo

- Estudiar y analizar los flujos migratorios a nivel global
- Analizar la relación e impactos que se generan en la economía


## Alcance

- Argentina y paises latinoamericanos con emigración o inmigración a Argentina

## KPIs

![KPIs](.\scr\img\kpis.png)

## Stack Tecnológico

![STACKTEC](.\scr\img\stacktec.png)

## Diccionario de Datos

### Migración neta

La migración neta es el total neto de personas que migraron durante el período: la cantidad total de inmigrantes menos la cantidad anual de emigrantes, incluidos los ciudadanos y los no ciudadanos.

* Columnas: 
    - value: int 
    - date: int
    - countryiso3code: str, columna de relación con la tabla cod_pais
	

### Población, total

La población total se basa en la definición de población de facto, que cuenta a todos los residentes independientemente de su estatus legal o ciudadanía. Los valores que se muestran son estimaciones de mitad de año.

* Columnas: 
    - value: int 
    - date: int
    - countryiso3code: str, columna de relación con la tabla cod_pais

### PIB (US$ a precios actuales)

El PIB a precio de comprador es la suma del valor agregado bruto de todos los productores residentes en la economía más todo impuesto a los productos, menos todo subsidio no incluido en el valor de los productos. 
Se calcula sin hacer deducciones por depreciación de bienes manufacturados o por agotamiento y degradación de recursos naturales. Los datos se expresan en moneda local a precios corrientes.

* Columnas: 
    - value: int 
    - date: int
    - countryiso3code: str, columna de relación con la tabla cod_pais
	
### Remesas

Las remesas personales comprenden las transferencias personales y la remuneración de los empleados

Las transferencias personales consisten en todas las transferencias corrientes en efectivo o en especie realizadas o recibidas por hogares residentes hacia o desde hogares no residentes. Las transferencias personales incluyen, por lo tanto, todas las transferencias corrientes entre personas físicas residentes y no residentes. 

La remuneración de los empleados se refiere a los ingresos de los trabajadores fronterizos, de temporada y otros trabajadores a corto plazo que están empleados en una economía en la que no son residentes y de los residentes empleados por entidades no residentes. 

Los datos están expresados ​​en dólares estadounidenses corrientes. 

* Columnas(tabla inmigrante y emigrante): 
    - value: int 
    - date: int
    - countryiso3code: str, columna de relación con la tabla cod_pais


### Código Países

Esta tabla contiene los códigos de los países.

* Columnas: 
    - countryiso3code: str, columna de primaria
    - nombre_pais: str



# CONCLUSIONES

- El mundo envejece rápidamente
- Hay una disminución de la tasa de natalidad
- Las políticas migratorias mejoradas pueden ayudar a impulsar la prosperidad en todos los países
- El modelo ideal de migración debe tener en cuenta los países de origen, tránsito y destino
- Aumenta la competencia por los trabajadores y el talento, a medida que las poblaciones envejecen
- Disminuye la población en los países ricos y de ingreso medio
- Los países de ingreso bajo tendrán un rápido crecimiento demográfico, y registrarán una mayor presión en la creación de empleos para los jóvenes.
- La crisis económica, la devaluación del peso y la falta de oportunidades ha aumentado la emigración en Argentina.
- La emigración de argentinos ha tenido un impacto significativo en la economía del país, ya que muchos de ellos eran jóvenes y altamente calificados, lo que ha generado una fuga de talentos.


# RECOMENDACIONES
- Formular políticas que tengan como objetivo,  la correspondencia entre las habilidades de los migrantes y la demanda en las sociedades de destino.
- Fomentar la creación de empleo, incentivar la inversión y el emprendimiento
- Desarrollar habilidades que tengan alta demanda en todo el mundo para que los ciudadanos que emigran puedan obtener mejores empleos.
- Proteger a sus ciudadanos mientras están en el extranjero, y crear incentivos para que aumenten las remesas al país.
- Crear políticas que miren el costo/beneficio para atraer los migrantes de acuerdo a las necesidades el país, como por ejemplo ofrecer empleo a migrantes calificados y dar beneficios fiscales

# FUENTE DE DATOS

* Los datos utilizados fueron extraidos de:
    - <a href='https://www.bancomundial.org/es/who-we-are?cid=ECR_GA_worldbank_es_extp_search&gclid=CjwKCAjwvJyjBhApEiwAWz2nLWid8v9vxlXMnX19gudmcg9HQ84veks8-zmajCVOGzDe9tQUMjyfjxoCQQUQAvD_BwE'>Banco mundial</a>
    - <a href='https://www.un.org/en/'>Naciones Unidas</a>

<img scr='.\scr\img\fuente_datos.pngS'></img>
![FUENTE DE DATOS](.\scr\img\fuente_datos.png)
