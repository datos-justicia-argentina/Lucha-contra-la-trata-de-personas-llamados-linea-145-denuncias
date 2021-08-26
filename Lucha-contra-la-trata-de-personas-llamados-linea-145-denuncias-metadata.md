Lucha contra la trata de personas - Llamados línea 145 - Denuncias
------------------------------------------------------------------

Este conjunto de datos contiene las llamadas atendidas por personal técnico del Programa Nacional de Rescate y Acompañamiento a las Personas Damnificadas por el Delito de Trata, de la Línea 145, con licenciaturas en Psicología o Trabajo Social, especializado en la escucha y la recepción. Se trata de un número de llamada gratuita, de alcance nacional, en el cual la atención está garantizada las 24hs. los 365 días del año, y que está facultado para recibir denuncias, relacionadas con el delito de Trata de Personas. Las mismas pueden realizarse en forma anónima a los fines de preservar la identidad de los denunciantes. La entrevista con el ciudadano puede finalizar en denuncia, si se trata de un caso de trata sexual o laboral, orientación,  si es una consulta que requiere de orientación pero no refiere al delito de trata, o puede determinarse que resultó un llamado no pertinente (llamados equivocados, bromas telefónicas o llamados obscenos).

La República Argentina ha incorporado el delito de Trata de Personas puesto que se contrajo como una obligación internacional en la Ratificación del [Protocolo para Prevenir, Reprimir y Sancionar la Trata de Personas, especialmente Mujeres y Niños](http://www.ohchr.org/Documents/ProfessionalInterest/ProtocolTraffickingInPersons_sp.pdf), el cual complementa la [Convención de las Naciones Unidas contra la Delincuencia Organizada Transnacional (Italia, Palermo 2000](https://www.unodc.org/documents/treaties/UNTOC/Publications/TOC%20Convention/TOCebook-s.pdf)

http://datos.jus.gob.ar/dataset/lucha-contra-la-trata-de-personas-llamados-linea-145-denuncias

https://www.argentina.gob.ar/jefatura/comitecontralatrata

Características
---------------

-   **Fecha de Primera** **Publicación:** 08/03/2018

-   **Tags o Etiquetas:** 145, trata, explotación, oferta sexual, desapariciones, grooming, captaciones, víctimas, género, vulnerabilidades, orientaciones, conflicto vecinal, adicciones, consumo, abuso infantil, denuncias

-   **Organización:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Política Criminal. Programa Nacional de Rescate y Acompañamiento a las Personas Damnificadas por el Delito de Trata

-   **Autor:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Política Criminal. Programa Nacional de Rescate y Acompañamiento a las Personas Damnificadas por el Delito de Trata

-   **Responsable:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Política Criminal. Programa Nacional de Rescate y Acompañamiento a las Personas Damnificadas por el Delito de Trata

-   **Grupo:** Acceso a Justicia, Género

-   **Frecuencia de Actualización:** Mensualmente

> La estructura mencionada a continuación hace referencia a los archivos publicados en el portal datos.jus.gob.ar a partir del mes de enero 2020. Los datos publicados surgen a patir de la registración en el sistema SICAJ (Sistema Informático de los Centros de Acceso a Justicia)

Recursos disponibles
--------------------

### Lucha contra la trata de personas denuncias línea 145 – 202001 - AAAAMM

-   **Nombre del archivo:** lucha-contra-la-trata-de-personas-denuncias-linea-145-202001-AAAAMM.csv

**Descripción del contenido:** detalle de los llamados atendidos por las y los profesionales del Programa Nacional de Rescate y Acompañamiento a las Personas Damnificadas por el Delito de Trata de la Línea 145, sobre casos de explotación laboral y/o explotación sexual. A partir de febrero de 2019 los datos surgen de su registración en el sistema SICAJ (Sistema Informático de los Centros de Acceso a Justicia)

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** desde enero de 2020 hasta la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **fecha_ingreso (date)**: fecha en que se cargan los primeros datos en el sistema. Las denuncias son cargadas en el sistema al momento de realizarlas. Formato AAAA-MM-DD

-	**hora_ingreso (datetime)**: hora en que se cargan los datos en el sistema. Formato hh:mm

-   **nro_registro_interno (int):** identificador de la denuncia. Permite relacionar a la denuncia con la tabla de personas referidas en las denuncias

-   **situación (string):** refiere a la evaluación que realiza la o el profesional que toma la consulta, según una serie de indicadores, en la cual determina si se trata de una urgencia o una emergencia. Esta evaluación determina el tipo de derivación que se efectúa.

-   **origen (string):** indica si la denuncia la realizó un ciudadano o una institución

-   **es_anonima (string):** toma valor Sí cuando no se identifica la persona que realiza la denuncia

-   **tema (string):** refiere a la problemática por la cual se realiza la denuncia. Toma la variable:

    -   Trata

-   **subtema (string):** refiere al subtema de la denuncia. Puede tomar los siguientes valores, entre otros:

    -   Explotación laboral
	
    -   Explotación sexual
	
    -   Explotación sexual niñas, niños y adolescentes
	
    -   Oferta laboral engañosa
	
    -   Extracción forzosa de órganos, tejidos o fluidos

-   **provincia (string):** provincia donde aconteció el hecho denunciado

-   **localidad (string):** localidad donde aconteció el hecho denunciado

-   **barrio (string):** barrio donde aconteció el hecho denunciado

-   **dependencia_alta (string):** dependencia desde la cual se cargó en el sistema la denuncia

-   **via_ingreso (string):** medio a través del cual ingresa la denuncia. Puede tomar los valores:

    -   Línea 145
	
    -   Correo institucional
	
    -   Teléfono institucional

-   **derivacion_institucion (string):** organismo al cual es derivada la denuncia para que lleve a cabo la judicialización o para su conocimiento. Cuando los hechos ocurren en la Ciudad de Buenos Aires el Programa Nacional de Rescate lleva adelante la judicialización. Si se trata de una emergencia se deriva a su vez a las Fuerzas Federales de Seguridad. Puede tomar los valores:

    -   Área legal del Programa Nacional de Rescate

    -   Gendarmería Nacional Argentina

    -   Juzgado/Fiscalía

    -   Oficina de Monitoreo

    -   Policía Federal Argentina

    -   Protex

    -   Comisarías

    -   Otros
	
	> Desde el día 1° de julio el PNR dejó de judicializar las denuncias. Se judicializa a través del Ministerio Público Fiscal (PROTEX)  o en caso de tratarse de una emergencia a través de las Fuerzas Federales de Seguridad

-   **derivacion_fecha (string):** fecha en la que se derivó la denuncia a otro organismo. Formato AAAA-MM-DD

-   **derivacion_judicializa (string):** toma valor Sí cuando la derivación termina siendo judicializada. No se judicializa en tanto sea una orientación

-   **derivacion2_institucion (string): ídem derivacion_institucion
	
-   **derivacion2_fecha (date): ídem derivacion_fecha
	
-   **derivacion2_judicializa (string): ídem derivacion_judicializa
	
-   **derivacion3_institucion (string): ídem derivacion_institucion
	
-   **derivacion3_fecha (date): ídem derivacion_fecha
	
-   **derivacion3_judicializa (string): ídem derivacion_judicializa

-   **denunciante_nacionalidad (string):** nacionalidad de la persona que realiza la denuncia

-   **denunciante_provincia (string):** provincia en la que se encuentra la persona que realiza la denuncia

-   **denunciante_localidad (string localidad en la que se encuentra la persona que realiza la denuncia

-   **denunciante_tipo (string):** refiere al tipo de denunciante. Puede tomar los valores:
	
    -   Denunciante - ciudadano
	
    -   Denunciante - institución

    -   Denunciante - institución
	
    -   Denunciante - víctima directa
	
    -   Denunciante - víctima indirecta
	
-   **denunciante_como_conocio_la_linea (string):** refiere al medio por el cual conoció la línea la persona que realiza la denuncia

-   **denunciante_genero (string):** género de la persona que realiza la denuncia. Puede tomar los valores:

    -   Hombre

    -   Mujer

    -   Transexual

    -   Transgénero

    -   Travesti

-   **denunciante_edad_aparente (string):** edad aparente de la persona que realiza la denuncia

-   **provincia_indec_id (string):** código de provincia desde la cual se realiza la denuncia, según la codificación de provincia implementada por INDEC (hasta 05/2019 nombre campo orientacion_provincia_indec_id)

### Lucha contra la trata de personas denuncias línea 145 – referidos - 202001 - AAAAMM

-   **Nombre del archivo:** oficina-rescate-denuncias-referidos-202001-AAAAMM.csv

**Descripción del contenido:** detalle de las personas a las que se hace referencia en la denuncia por el Delito de Trata de la Línea 145. Refiere tanto víctimas como acusados

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** desde enero de 2020 hasta la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **nro_registro_interno (int):** identificador de la denuncia. Permite relacionar al referido con la denuncia

-   **fecha_ingreso_denuncia (date)**: fecha en la que se ingresa la denuncia al sistema. Formato AAAA-MM-DD

-   **tema (string):** refiere a la problemática por la cual se realiza la denuncia. Toma el mismo valores que en la denuncia

-   **subtema (string):** refiere al subtema de la orientación. Toma los mismos valores que en la denuncia
  
-   **referido_tipo (string):** referido tipo. Puede tomar los siguientes valores:

    -   Acusado
	
    -   Víctima directa
	
    -   Víctima indirecta - familiar

-   **nacionalidad (string):** nacionalidad de la persona referida

-   **provincia (string):** provincia a la que pertenece la persona referida

-   **localidad (string):** localidad a la que pertenece la persona referida

-   **genero (string):** género de la persona referida. Puede tomar los mismos valores que el campo denunciante_genero

-   **edad_aparente (string):** edad aparente de la persona referida

-   **embarazada (string):** toma valor Sí cuando la persona referida está embarazada

-   **discapacidad (string):** toma valor Sí cuando la persona referida posee algún tipo de discapacidad

-   **provincia_indec_id (string):** código de la provincia a la que pertenece la persona referida, según la codificación de provincia implementada por INDEC

### Lucha contra la trata de personas denuncias línea 145 – AAAA

-   **Nombre del archivo:** lucha-contra-la-trata-de-personas-denuncias-linea-145-AAAA.zip

-	**Descripción del contenido:** denuncias sobre trata de personas recibidas en la Línea 145 en el año AAAA

-   **Formato:** ZIP

### Lucha contra la trata de personas denuncias línea 145 – referidos - AAAA

-   **Nombre del archivo:** oficina-rescate-denuncias-referidos-AAAA.zip

**Descripción del contenido:** referidos en las denuncias recibidas en la Línea 145 sobre trata de personas en el año AAAA

-   **Formato:** ZIP


> La estructura mencionada a continuación hace referencia a los archivos publicados en el portal datos.jus.gob.ar durante el período comprendido entre el año 2017 y 2019 organizados en archivos anuales.


Recursos disponibles
--------------------

### Lucha contra la trata de personas llamados línea 145 – AAAAMM

-   **Nombre del archivo:** lucha-contra-la-trata-de-personas-llamados-linea-145-AAAAMM.zip

**Descripción del contenido:** detalle de los llamados atendidos por los profesionales del Programa Nacional de Rescate y Acompañamiento a las Personas Damnificadas por el Delito de Trata de la Línea 145, sobre casos de explotación laboral, explotación sexual, desaparición de personas, publicidad de oferta sexual, traslado de personas, posible captación, grooming y venta de niños,

> Cada fila en este archivo representa un llamado, ya que en el llamado se identifica una única víctima y un único agresor/a. 

-   **Formato:** ZIP

### Campos del recurso

-   **denuncia_fecha (date)**: fecha en que se atendió el llamado. Formato AAAA-MM-DD

-   **denuncia_previa (string):** toma el valor Sí cuando se conoce que se había realizado una denuncia anterior sobre el hecho

-   **derivacion_seguimiento (string):** toma valor Sí cuando la denuncia es derivada al área “Seguimiento”

-   **llamante_anonimo (string):** toma valor Sí cuando no se identifica la persona que realiza la denuncia

-   **llamante_es_victima (string):** hace referencia a si la persona que realiza la denuncia es víctima. Puede tomar los valores:

    -   No es Víctima

    -   Víctima Directa
    
    -   Víctima Indirecta

-   **llamante_genero (string):** género de quien realiza el llamado. Puede tomar los valores:

    -   Masculino

    -   Femenino

    -   Trans

    -   Situaciones con hombres y mujeres o trans (varios)

    -   Ns/Nc: no sabe / no contesta

    -   Otros

-   **llamante_rango_etario (int):** rango etario de la persona que realiza el llamado. Puede tomar los valores:

    -   0 a 13 años

    -   14 a 16 años

    -   16 a 17 años (específico para trabajo adolescente)

    -   18 a 25 años

    -   26 a 40 años

    -   41 a 60 años

    -   61 años en adelante

    -   No refiere

-   **llamante_provincia (string):** provincia a la que pertenece la persona que realiza el llamado

-   **victima_identificada_genero (string):** género de la víctima identificada. Puede tomar los valores:

    -   Masculino

    -   Femenino

    -   Trans

    -   Situaciones con hombres y mujeres o trans (varios)

    -   Ns/Nc: no sabe / no contesta

    -   Otros

-   **victima_identificada_rango_etario (int):** rango etario de la víctima identificada. Puede tomar los valores:

    -   0 a 13 años

    -   14 a 16 años

    -   16 a 17 años (específico para trabajo adolescente)

    -   18 a 25 años

    -   26 a 40 años

    -   41 a 60 años

    -   61 años en adelante

    -   No refiere

-   **victima_identificada_discapacidad (string):** toma valor Sí cuando la víctima identificada posee algún tipo de discapacidad

-   **victima_identificada_embarazada (string):** toma valor Sí cuando la víctima identificada se encuentra embarazada

-   **victima_identificada_provincia_origen (string):** provincia en la que nació la víctima identificada

-   **victima_identificada_nacionalidad (string):** nacionalidad de la víctima identificada

-   **denunciado_genero (string):** género de la persona denunciada. Puede tomar los valores:

    -   Masculino

    -   Femenino

    -   Trans

    -   Situaciones con hombres y mujeres o trans (varios)

    -   Ns/Nc: no sabe / no contesta

    -   Otros
    
-   **denunciado_rango_etario (int):** rango etario de la persona denunciada. Puede tomar los valores:

    -   0 a 13 años

    -   14 a 16 años

    -   16 a 17 años (específico para trabajo adolescente)

    -   18 a 25 años

    -   26 a 40 años

    -   41 a 60 años

    -   61 años en adelante

    -   No refiere
    
-   **denunciado_provincia (string):** provincia en la que se encuentra la persona denunciada

-   **connivencia_fuerza_seguridad (string):** toma valor Sí cuando en los hechos relatados se hiciere mención a la connivencia o autoría de personas pertenecientes a las fuerzas de seguridad

-   **connivencia_poder_politico (string):** toma valor Sí cuando en los hechos relatados se hiciere mención a la connivencia o autoría de personas con carácter de funcionarios públicos

-   **victimas_estimadas_cantidad (string):** cantidad estimada de víctimas afectadas en el hecho denunciado

-   **victimas_estimadas_genero (string):** género de las víctimas estimadas en el hecho denunciado. Puede tomar los valores:

    -   Masculino

    -   Femenino

    -   Trans

    -   Situaciones con hombres y mujeres o trans (varios)

    -   Ns/Nc: no sabe / no contesta

    -   Otros
    
-   **victimas_estimadas_rango_etario (int):** rango etario de las víctimas estimadas en el hecho denunciado. Puede tomar los valores:

    -   0 a 13 años

    -   14 a 16 años

    -   16 a 17 años (específico para trabajo adolescente)

    -   18 a 25 años

    -   26 a 40 años

    -   41 a 60 años

    -   61 años en adelante

    -   No refiere

-   **victimas_estimadas_provincia_hecho (string):** provincia en la que se produjo el hecho denunciado

-   **denuncia_tipo_explotacion (string):** se menciona a qué tipo de explotación hace referencia la denuncia. Puede tomar los valores:

    -   Explotación sexual

    -   Explotación laboral

    -   Desaparición

    -   Publicidad de oferta sexual

    -   Oferta laboral engañosa

    -   Traslado de personas

    -   Posible captación

    -   Venta de niños y otros delitos

    -   Explotación sexual niñas, niños y adolescentes

    -   Explotación laboral niñas, niños y adolescentes

    -   Grooming

    -   Pornografía infantil

    -   Ofrecimiento

    -   Mula

    -   Servidumbre doméstica

    -   Posible trata de personas (hecho indefinido).

    -   Matrimonio forzado

    -   Extracción forzosa de órganos, tejidos o fluidos
    
>   La variable informada como "Indicadores de Posible Trata" hasta enero de 2019 es reemplazada por "Posible Captación" a partir del mes de febrero de 2019.

-   **denuncia_via_ingreso (string):** medio a través del cual ingresa la denuncia

    -   Línea 145

    -   Correo institucional

    -   Teléfono institucional (no salientes)

    -   Presencial

    -   Lamadas salientes

    -   Llamadas realizadas por seguimiento

    -   Línea 149 - CENAVID

-   **acercamiento_tipo (string):** refiere a cómo el denunciante conoció la línea 145 o el Programa

    -   TV

    -   Internet

    -   Radio

    -   Campañas del Programa

    -   Capacitación

    -   ONG – Organismos Nacionales

    -   Boca en boca

    -   Otros

-   **derivacion_organismo (string):** organismo al cual es derivada la denuncia. Puede tomar los valores:

    -   Ministerio de Seguridad

    -   Oficina de Monitoreo

    -   Área legal ya judicializada

    -   Fuerzas de Seguridad Federal

    -   Juzgado/Fiscalía

    -   Protex

    -   Área legal para judicializar

    -   Ufisex

    -   Comisarías

    -   Otros

-   **derivacion_fecha (date):** fecha en la que se derivó la denuncia a otro organismo

-   **llamante_provincia_id (int):** código INDEC de la provincia a la que pertenece la persona que realiza el llamado (hasta 05/2019 nombre campo llamante_provincia_indec_id)

-   **victima_identificada_provincia_origen_id (int):** código INDEC de la provincia en la que nació la víctima identificada (hasta 05/2019 nombre campo victima_identificada_provincia_origen_indec_id)

-   **denunciado_provincia_id (int):** código INDEC de la provincia en la que se encuentra la persona denunciada (hasta 05/2019 nombre campo denunciado_provincia_indec_id)

-   **victimas_estimadas_provincia_hecho_id (int**): código INDEC de la provincia en la que se produjo el hecho denunciado (hasta 05/2019 nombre campo victimas_estimadas_provincia_hecho_indec_id)


### Notas

[Ley 27.275 - Derecho de Acceso a la Información Pública]( http://servicios.infoleg.gob.ar/infolegInternet/anexos/265000-269999/265949/norma.htm)

[Ley 26.364](http://servicios.infoleg.gob.ar/infolegInternet/anexos/140000-144999/140100/norma.htm)

[Ley 26.842](http://servicios.infoleg.gob.ar/infolegInternet/anexos/205000-209999/206554/norma.htm)

[Ley 26.904](http://servicios.infoleg.gob.ar/infolegInternet/anexos/220000-224999/223586/norma.htm)

[Resolución 74/2011](http://servicios.infoleg.gob.ar/infolegInternet/anexos/180000-184999/184545/norma.htm)

[Decreto 936/2011](http://servicios.infoleg.gob.ar/infolegInternet/anexos/180000-184999/184133/norma.htm)

[Código Penal de la Nación Argentina Ley 11.179](http://servicios.infoleg.gob.ar/infolegInternet/anexos/15000-19999/16546/texact.htm)

[Protocolo para prevenir, reprimir y sancionar la trata de personas, especialmente mujeres y niños, que complementa la Convención de las Naciones Unidas contra la Delincuencia Organizada Transnacional](http://www.ohchr.org/Documents/ProfessionalInterest/ProtocolTraffickingInPersons_sp.pdf)

[Convención de las Naciones Unidas contra la Delincuencia Organizada Transnacional (Italia, Palermo 2000)](https://www.unodc.org/documents/treaties/UNTOC/Publications/TOC%20Convention/TOCebook-s.pdf)

Se considera a la trata de personas como una de las modernas formas de esclavitud, que genera un comercio humano garantizándole a los autores ganancias económicas similares a las obtenidas respecto del tráfico de estupefacientes y el tráfico ilegal de armas.

Desde el plano humanitario, se hablará de la existencia de una relación de sujeción especial entre el autor y la víctima; un binomio sujeto-objeto donde esta última será considerada –por el autor- como una cosa. Finalmente y en consecuencia, la trata de personas constituye una vulneración y avasallamiento de los derechos humanos en general y de la libertad en particular.

En cumplimento con las obligaciones internacionalmente contraídas, el Estado Nacional tipificó el delito de Trata de Personas en el **Libro II, Título V del [Código Penal](http://servicios.infoleg.gob.ar/infolegInternet/anexos/15000-19999/16546/texact.htm), en sus art. 145bis y 145ter.** Fue introducido originalmente mediante la [Ley 26.364](http://servicios.infoleg.gob.ar/infolegInternet/anexos/140000-144999/140100/norma.htm), sancionada el día 29 de abril del año 2008, y luego modificada el 26 de diciembre del año 2012, mediante la [Ley 26.842](http://servicios.infoleg.gob.ar/infolegInternet/anexos/205000-209999/206554/norma.htm), actualmente en vigencia.

La trata de personas se estructura a través de dos elementos, como son las acciones (ofrecer, captar, trasladar, recibir y acoger) y una determinada finalidad de explotación; la cual no requiere ser concretada para tener por consumado el delito, puesto que este se configura siempre y cuando se realice alguna de conductas (acciones) con cualquiera de las finalidades de explotación mencionadas por la ley.

Por lo tanto, la Trata de Personas es un delito de resultado anticipado o recortado, donde el legislador anticipa el momento de la consumación, aunque el objeto del bien jurídico – la libertad - no esté todavía materialmente perjudicado, o lo esté solo en parte. Es esta finalidad de explotación es la que permite distinguir conductas de naturaleza similar que sin embargo constituyen actos preparatorios o tentativas de otros delitos.

*MODALIDADES DE EXPLOTACIÓN:*

**Explotación laboral:**

Inc. b) “cuando se redujere o mantuviere una persona en condición de esclavitud o servidumbre, bajo cualquier modalidad”

Inc b) “Cuando se obligare a una persona a realizar trabajos o servicios forzados”;

**Explotación sexual:**

Inc c) “Cuando se promoviere, facilitare o comercializare la prostitución ajena o cualquier otra forma de oferta de servicios sexuales ajenos”.

**Pornografía infantil:**

Inc. d) Cuando se promoviere, facilitare o comercializare la pornografía infantil o la realización de cualquier tipo de representación o espectáculo con dicho contenido;

**Matrimonio forzado:**

Inc. e) Cuando se forzare a una persona al matrimonio o a cualquier tipo de unión de hecho;

**Extracción de órganos:**

Inc. f) “Cuando se promoviere, facilitare o comercializare la extracción forzosa o ilegítima de órganos, fluidos o tejidos humanos. El consentimiento dado por la víctima de la trata y explotación de personas no constituirá en ningún caso causal de eximición de responsabilidad penal, civil o administrativa de los autores, partícipes, cooperadores o instigadores.

De esta manera, el tipo penal del art. 145 bis queda cumplido con la captación, traslado, acogimiento, recepción u ofrecimiento de una persona con finalidad de explotación. En líneas generales, la antigua [Ley 26.364](http://servicios.infoleg.gob.ar/infolegInternet/anexos/140000-144999/140100/norma.htm)contaba con estas acciones, pero exigía, para la tipificación del delito, que el autor se valiera de mecanismos específicos, llamados medios comisivos, para el logro de los verbos.

No obstante, estos mecanismos mediante los cuales el autor obtendría el consentimiento de la víctima conservan su plena vigencia, en tanto que - [Ley 26.842](http://servicios.infoleg.gob.ar/infolegInternet/anexos/205000-209999/206554/norma.htm) - constituyen agravantes del tipo básico, y son enunciados en el art 145ter del Código Penal.

Por lo tanto, de acuerdo a la [Ley 26.842](http://servicios.infoleg.gob.ar/infolegInternet/anexos/205000-209999/206554/norma.htm), no interesa si la víctima es mayor o menor de 18 años, puesto que el consentimiento de ésta no constituirá en ningún caso causal de eximición de responsabilidad. Este cambio, de trascendental importancia, se sustenta en la premisa de que ningún ser humano puede consentir la degradación de su dignidad.

**Línea 145:**

Desde el año 2011 la ex Oficina de Rescate, actual Programa Nacional cuenta con la línea 145, asignada por la Comisión Nacional de Comunicaciones dependiente del Ministerio de Planificación Federal, Inversión Pública y Servicios, por [Resolución 74/2011](http://servicios.infoleg.gob.ar/infolegInternet/anexos/180000-184999/184545/norma.htm), en el Boletín Oficial el día 7 de Julio de 2011. Se trata de un número de llamada gratuita, de alcance nacional, en el cual la atención está garantizada las 24hs. los 365 días del año, y que está facultado para recibir denuncias, relacionadas con el delito de Trata de Personas. Las mismas pueden realizarse en forma anónima a los fines de preservar la identidad de los denunciantes.

Una de las novedades fundamentales de la [Ley 26.842](http://servicios.infoleg.gob.ar/infolegInternet/anexos/205000-209999/206554/norma.htm) – Titulo VI - fue la creación de un "Sistema Sincronizado de Denuncias sobre los Delitos de Trata y Exploración de Personas", que determina "*asígnasele el número telefónico ciento cuarenta y cinco (145), uniforme en todo el territorio nacional, que funcionará en forma permanente durante las veinticuatro horas del día a fin de receptar denuncias sobre los delitos de trata y explotación de personas (art. 15)”.*

A lo anterior, se ordena la creación y conservación *“de un archivo con los registro de las llamadas telefónicas (…), identificados electrónicamente (…), a fin de contar con una base de consulta de datos para facilitar la investigación de los delitos de trata y explotación de personas (art 16)”.*

Desde el año 2011 la Línea 145 se enmarca dentro del Programa Nacional de Rescate y Acompañamiento a las Personas Damnificadas por el Delito, asignada por la Comisión Nacional de Comunicaciones, dependiente del Ministerio de Planificación Federal, Inversión Pública y Servicios, por [Resolución 74/2011](http://servicios.infoleg.gob.ar/infolegInternet/anexos/180000-184999/184545/norma.htm).

**Anonimato:** según lo establece el artículo 17 de la [Ley 26.842](http://servicios.infoleg.gob.ar/infolegInternet/anexos/205000-209999/206554/norma.htm) las denuncias podrán ser efectuadas de manera anónima. Esta posibilidad es considerada como una de las modificaciones más relevantes introducidas con respecto de la [Ley 26.364](http://servicios.infoleg.gob.ar/infolegInternet/anexos/140000-144999/140100/norma.htm), puesto que ella responde a una herramienta de acceso a la justicia y detección de casos de crimen organizado universalmente aceptada. Sirve, además, para conocer de un supuesto “autor en que fuere funcionario público o miembro de una fuerza de seguridad, policial o penitenciaria” (inciso 7 Art 145 ter CP).

**Profesional:** las denuncias son recibidas por personal técnico, con licenciaturas en Psicología o Trabajo Social, especializado en la escucha y la recepción. Se consigna en referencia a la persona que recibe el llamado y o correo electrónico de la ciudadanía. La elección de las especialidades profesionales está inspirada en las “Garantías mínimas para el ejercicio” de los derechos de las víctimas Titulo II Detrás de esta regulación está la idea de que el interrogatorio forense es un acto con alto contenido revictimizante y que sus efectos pueden ser morigerados cuando éste está dirigido por un especialista en psicología. Además, la persona que se comunica para realizar una denuncia no tiene por qué conocer los aspectos relevantes de un hecho de trata de personas (lugar de captación, forma de traslado, forma de pago del traslado, quién pagó, quién esperó en el lugar de explotación, características del lugar de explotación, entre otras innumerables cuestiones), por lo que es necesario que el personal conozca la temática acabadamente para que las preguntas y repreguntas conduzcan a la obtención de información y a la calidad de esa información.


Este Conjunto de datos es publicado en el Portal de Datos Abiertos de la Justicia Argentina mediante [Resolución Nº 187 del Ministerio de Justicia y Derechos Humanos](http://datos.jus.gob.ar/resoluciones/RESOL-2018-187-APN-MJ.pdf), del 9 de Marzo de 2018.
