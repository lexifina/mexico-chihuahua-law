# Chihuahua: law history in git

The law of the State of Chihuahua (Estado Libre y Soberano de Chihuahua, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-chh/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

149 ordenamientos with 1737 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE CHIHUAHUA | 155 | as first published, then each reform: 20 June 1950 to 18 October 2026 |
| `codigo-administrativo/` | CODIGO ADMINISTRATIVO DEL ESTADO DE CHIHUAHUA | 112 | as first published, then each reform: 21 August 1974 to 30 August 2026 |
| `codigo-civil/` | CODIGO CIVIL DEL ESTADO DE CHIHUAHUA | 116 | as first published, then each reform: 23 March 1974 to 25 August 2024 |
| `codigo-de-procedimientos-civiles/` | CODIGO DE PROCEDIMIENTOS CIVILES DEL ESTADO DE CHIHUAHUA | 6 | as first published, then each reform: 26 July 2014 to 23 February 2017 |
| `codigo-de-procedimientos-familiares/` | CODIGO DE PROCEDIMIENTOS FAMILIARES DEL ESTADO DE CHIHUAHUA | 7 | as first published, then each reform: 26 July 2014 to 10 January 2019 |
| `codigo-fiscal/` | CODIGO FISCAL DEL ESTADO DE CHIHUAHUA | 9 | as first published, then each reform: 1 January 2019 to 7 January 2026 |
| `codigo-municipal/` | CODIGO MUNICIPAL PARA EL ESTADO DE CHIHUAHUA | 189 | as first published, then each reform: 21 November 1995 to 1 September 2026 |
| `codigo-penal/` | CODIGO PENAL DEL ESTADO DE CHIHUAHUA | 124 | as first published, then each reform: 30 December 2006 to 30 August 2026 |
| `ley-de-adopciones/` | LEY DE ADOPCIONES DEL ESTADO DE CHIHUAHUA | 2 | as first published, then each reform: 6 February 2020 to 22 February 2020 |
| `ley-de-adquisiciones-arrendamientos-y-contratacion-de-servic/` | LEY DE ADQUISICIONES, ARRENDAMIENTOS Y CONTRATACION DE SERVICIOS DEL ESTADO DE CHIHUAHUA | 7 | as first published, then each reform: 18 February 2018 to 9 August 2026 |
| `ley-de-alcoholes/` | LEY DE ALCOHOLES DEL ESTADO DE CHIHUAHUA | 1 | as first published: 1 January 2018 |
| `ley-de-archivos/` | LEY DE ARCHIVOS PARA EL ESTADO DE CHIHUAHUA | 3 | as first published, then each reform: 28 February 2021 to 11 January 2026 |
| `ley-de-asentamientos-humanos-ordenamiento-territorial-y-desa/` | LEY DE ASENTAMIENTOS HUMANOS, ORDENAMIENTO TERRITORIAL Y DESARROLLO URBANO DEL ESTADO DE CHIHUAHUA | 3 | as first published, then each reform: 1 November 2021 to 19 April 2026 |
| `ley-de-asistencia-social-publica-y-privada/` | LEY DE ASISTENCIA SOCIAL PUBLICA Y PRIVADA PARA EL ESTADO DE CHIHUAHUA | 18 | as first published, then each reform: 31 October 2009 to 25 January 2026 |
| `ley-de-asociaciones-publico-privadas/` | LEY DE ASOCIACIONES PUBLICO PRIVADAS DEL ESTADO DE CHIHUAHUA | 2 | as first published, then each reform: 17 March 2019 to 13 August 2020 |
| `ley-de-atencion-y-apoyo-a-personas-trabajadoras-del-campo/` | LEY DE ATENCION Y APOYO A PERSONAS TRABAJADORAS DEL CAMPO DEL ESTADO DE CHIHUAHUA | 1 | as first published: 10 September 2023 |
| `ley-de-bienes/` | LEY DE BIENES DEL ESTADO DE CHIHUAHUA | 4 | as first published, then each reform: 13 February 2020 to 22 February 2024 |
| `ley-de-bienestar-animal/` | LEY DE BIENESTAR ANIMAL PARA EL ESTADO DE CHIHUAHUA | 13 | as first published, then each reform: 18 November 2010 to 2 July 2026 |
| `ley-de-cambio-climatico/` | LEY DE CAMBIO CLIMATICO DEL ESTADO DE CHIHUAHUA | 3 | as first published, then each reform: 6 August 2013 to 23 February 2017 |
| `ley-de-catastro/` | LEY DE CATASTRO DEL ESTADO DE CHIHUAHUA | 21 | as first published, then each reform: 1 January 1996 to 23 February 2017 |
| `ley-de-ciencia-tecnologia-e-innovacion/` | LEY DE CIENCIA, TECNOLOGIA E INNOVACION DEL ESTADO DE CHIHUAHUA | 5 | as first published, then each reform: 15 March 2018 to 17 November 2024 |
| `ley-de-consulta-a-los-pueblos-y-comunidades-indigenas-en-el/` | LEY DE CONSULTA A LOS PUEBLOS Y COMUNIDADES INDIGENAS EN EL ESTADO DE CHIHUAHUA | 1 | as first published: 22 September 2024 |
| `ley-de-coordinacion-fiscal/` | LEY DE COORDINACION FISCAL DEL ESTADO DE CHIHUAHUA Y SUS MUNICIPIOS | 12 | as first published, then each reform: 27 November 2018 to 7 January 2026 |
| `ley-de-cultura-de-la-legalidad/` | LEY DE CULTURA DE LA LEGALIDAD PARA EL ESTADO DE CHIHUAHUA | 6 | as first published, then each reform: 1 May 2011 to 9 August 2026 |
| `ley-de-cultura-fisica-y-deporte/` | LEY DE CULTURA FISICA Y DEPORTE DEL ESTADO DE CHIHUAHUA | 25 | as first published, then each reform: 22 November 2005 to 28 May 2026 |
| `ley-de-derechos-de-las-personas-mayores-en-el-estado-de-chih/` | LEY DE DERECHOS DE LAS PERSONAS MAYORES EN EL ESTADO DE CHIHUAHUA | 3 | as first published, then each reform: 26 July 2018 to 16 April 2026 |
| `ley-de-derechos-de-los-pueblos-indigenas/` | LEY DE DERECHOS DE LOS PUEBLOS INDIGENAS DEL ESTADO DE CHIHUAHUA | 10 | as first published, then each reform: 30 June 2013 to 10 May 2026 |
| `ley-de-desarrollo-cultural/` | LEY DE DESARROLLO CULTURAL PARA EL ESTADO DE CHIHUAHUA | 6 | as first published, then each reform: 4 February 2018 to 14 May 2026 |
| `ley-de-desarrollo-forestal-sustentable/` | LEY DE DESARROLLO FORESTAL SUSTENTABLE DEL ESTADO DE CHIHUAHUA | 3 | as first published, then each reform: 25 October 2018 to 16 April 2026 |
| `ley-de-desarrollo-rural-integral-sustentable/` | LEY DE DESARROLLO RURAL INTEGRAL SUSTENTABLE PARA EL ESTADO DE CHIHUAHUA | 13 | as first published, then each reform: 18 March 2012 to 9 August 2026 |
| `ley-de-desarrollo-social-y-humano/` | LEY DE DESARROLLO SOCIAL Y HUMANO PARA EL ESTADO DE CHIHUAHUA | 10 | as first published, then each reform: 16 June 2007 to 6 March 2025 |
| `ley-de-desarrollo-y-fomento-economico/` | LEY DE DESARROLLO Y FOMENTO ECONOMICO PARA EL ESTADO DE CHIHUAHUA | 9 | as first published, then each reform: 14 May 2007 to 22 February 2024 |
| `ley-de-deuda-publica/` | LEY DE DEUDA PUBLICA PARA EL ESTADO DE CHIHUAHUA Y SUS MUNICIPIOS | 9 | as first published, then each reform: 1 January 1995 to 17 March 2019 |
| `ley-de-donacion-y-trasplantes-de-organos-tejidos-y-celulas/` | LEY DE DONACION Y TRASPLANTES DE ORGANOS, TEJIDOS Y CELULAS DEL ESTADO DE CHIHUAHUA | 4 | as first published, then each reform: 8 June 2014 to 21 October 2018 |
| `ley-de-economia-circular/` | LEY DE ECONOMIA CIRCULAR PARA EL ESTADO DE CHIHUAHUA | 1 | as first published: 7 July 2025 |
| `ley-de-ejecucion-de-penas-y-medidas-judiciales-antes-ley-de/` | LEY DE EJECUCION DE PENAS Y MEDIDAS JUDICIALES -ANTES LEY DE EJECUCION DE PENAS Y MEDIDAS DE SEGURIDAD DEL ESTADO DE CHIHUAHUA- | 29 | as first published, then each reform: 12 December 2006 to 23 February 2017 |
| `ley-de-entidades-paraestatales/` | LEY DE ENTIDADES PARAESTATALES DEL ESTADO DE CHIHUAHUA | 16 | as first published, then each reform: 29 January 1998 to 30 October 2025 |
| `ley-de-entrega-recepcion/` | LEY DE ENTREGA RECEPCION PARA EL ESTADO DE CHIHUAHUA | 3 | as first published, then each reform: 5 November 2015 to 3 October 2016 |
| `ley-de-equilibrio-ecologico-y-proteccion-al-ambiente/` | LEY DE EQUILIBRIO ECOLOGICO Y PROTECCION AL AMBIENTE DEL ESTADO DE CHIHUAHUA | 1 | as first published: 13 May 2018 |
| `ley-de-fiscalizacion-superior/` | LEY DE FISCALIZACION SUPERIOR DEL ESTADO DE CHIHUAHUA | 4 | as first published, then each reform: 8 September 2019 to 22 December 2022 |
| `ley-de-fomento-a-la-actividad-vitivinicola/` | LEY DE FOMENTO A LA ACTIVIDAD VITIVINICOLA DEL ESTADO DE CHIHUAHUA | 3 | as first published, then each reform: 10 April 2014 to 23 November 2023 |
| `ley-de-fomento-a-la-competitividad-de-la-micro-pequena-y-med/` | LEY DE FOMENTO A LA COMPETITIVIDAD DE LA MICRO, PEQUEÑA Y MEDIANA EMPRESA DEL ESTADO DE CHIHUAHUA | 2 | as first published, then each reform: 25 September 2016 to 27 November 2022 |
| `ley-de-fomento-a-las-actividades-artesanales/` | LEY DE FOMENTO A LAS ACTIVIDADES ARTESANALES DEL ESTADO DE CHIHUAHUA | 6 | as first published, then each reform: 6 November 2008 to 9 August 2026 |
| `ley-de-fomento-al-emprendimiento/` | LEY DE FOMENTO AL EMPRENDIMIENTO DEL ESTADO DE CHIHUAHUA | 3 | as first published, then each reform: 26 January 2023 to 17 October 2024 |
| `ley-de-fomento-para-la-lectura-y-el-libro/` | LEY DE FOMENTO PARA LA LECTURA Y EL LIBRO DEL ESTADO DE CHIHUAHUA | 1 | as first published: 11 November 2018 |
| `ley-de-ganaderia/` | LEY DE GANADERIA DEL ESTADO DE CHIHUAHUA | 5 | as first published, then each reform: 13 December 2015 to 19 April 2026 |
| `ley-de-gobierno-digital/` | LEY DE GOBIERNO DIGITAL PARA EL ESTADO DE CHIHUAHUA | 3 | as first published, then each reform: 18 December 2022 to 7 December 2023 |
| `ley-de-igualdad-entre-mujeres-y-hombres/` | LEY DE IGUALDAD ENTRE MUJERES Y HOMBRES DEL ESTADO DE CHIHUAHUA | 7 | as first published, then each reform: 30 May 2010 to 9 August 2026 |
| `ley-de-imagen-institucional-del-poder-legislativo/` | LEY DE IMAGEN INSTITUCIONAL DEL PODER LEGISLATIVO DEL ESTADO DE CHIHUAHUA | 1 | as first published: 25 September 2014 |
| `ley-de-indulto/` | LEY DE INDULTO DEL ESTADO DE CHIHUAHUA | 1 | as first published: 9 November 2025 |
| `ley-de-ingresos/` | LEY DE INGRESOS DEL ESTADO DE CHIHUAHUA PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-ahumada-para-el-ejercicio-f/` | LEY DE INGRESOS DEL MUNICIPIO DE AHUMADA PARA EL EJERCICIO FISCAL DE 2026, CHIHUAHUA | 1 | as first published: 23 December 2025 |
| `ley-de-ingresos-del-municipio-de-ascension-para-el-ejercicio/` | LEY DE INGRESOS DEL MUNICIPIO DE ASCENSION PARA EL EJERCICIO FISCAL DE 2026, CHIHUAHUA | 1 | as first published: 30 December 2025 |
| `ley-de-ingresos-del-municipio-de-buenaventura-para-el-ejerci/` | LEY DE INGRESOS DEL MUNICIPIO DE BUENAVENTURA PARA EL EJERCICIO FISCAL 2026, CHIHUAHUA | 1 | as first published: 30 December 2025 |
| `ley-de-ingresos-del-municipio-de-camargo-para-el-ejercicio-f/` | LEY DE INGRESOS DEL MUNICIPIO DE CAMARGO PARA EL EJERCICIO FISCAL 2026, CHIHUAHUA | 1 | as first published: 30 December 2025 |
| `ley-de-ingresos-del-municipio-de-carichi-para-el-ejercicio-f/` | LEY DE INGRESOS DEL MUNICIPIO DE CARICHI PARA EL EJERCICIO FISCAL 2026, CHIHUAHUA | 1 | as first published: 30 December 2025 |
| `ley-de-ingresos-del-municipio-de-casas-grandes-para-el-ejerc/` | LEY DE INGRESOS DEL MUNICIPIO DE CASAS GRANDES PARA EL EJERCICIO FISCAL 2026, CHIHUAHUA | 1 | as first published: 30 December 2025 |
| `ley-de-ingresos-del-municipio-de-delicias-para-el-ejercicio/` | LEY DE INGRESOS DEL MUNICIPIO DE DELICIAS PARA EL EJERCICIO FISCAL 2026, CHIHUAHUA | 1 | as first published: 30 December 2025 |
| `ley-de-ingresos-del-municipio-de-janos-para-el-ejercicio-fis/` | LEY DE INGRESOS DEL MUNICIPIO DE JANOS PARA EL EJERCICIO FISCAL 2026, CHIHUAHUA | 1 | as first published: 30 December 2025 |
| `ley-de-ingresos-del-municipio-de-nuevo-casas-grandes-para-el/` | LEY DE INGRESOS DEL MUNICIPIO DE NUEVO CASAS GRANDES PARA EL EJERCICIO FISCAL 2026, CHIHUAHUA | 1 | as first published: 30 December 2025 |
| `ley-de-ingresos-del-municipio-de-santa-barbara-para-el-ejerc/` | LEY DE INGRESOS DEL MUNICIPIO DE SANTA BARBARA PARA EL EJERCICIO FISCAL 2026, CHIHUAHUA | 1 | as first published: 30 December 2025 |
| `ley-de-ingresos-del-municipio-de-satevo-para-el-ejercicio-fi/` | LEY DE INGRESOS DEL MUNICIPIO DE SATEVO PARA EL EJERCICIO FISCAL 2026, CHIHUAHUA | 1 | as first published: 30 December 2025 |
| `ley-de-juicio-politico-y-declaracion-de-procedencia/` | LEY DE JUICIO POLITICO Y DECLARACION DE PROCEDENCIA PARA EL ESTADO DE CHIHUAHUA | 2 | as first published, then each reform: 12 June 2022 to 22 June 2022 |
| `ley-de-justicia-administrativa/` | LEY DE JUSTICIA ADMINISTRATIVA DEL ESTADO DE CHIHUAHUA | 1 | as first published: 16 March 2019 |
| `ley-de-justicia-alternativa/` | LEY DE JUSTICIA ALTERNATIVA DEL ESTADO DE CHIHUAHUA | 3 | as first published, then each reform: 31 May 2015 to 13 September 2018 |
| `ley-de-juventud/` | LEY DE JUVENTUD PARA EL ESTADO DE CHIHUAHUA | 9 | as first published, then each reform: 21 October 2018 to 2 July 2026 |
| `ley-de-la-comision-estatal-de-los-derechos-humanos-antes-ley/` | LEY DE LA COMISION ESTATAL DE LOS DERECHOS HUMANOS -ANTES LEY DE LA COMISION ESTATAL DE DERECHOS HUMANOS- | 15 | as first published, then each reform: 27 September 1992 to 1 September 2024 |
| `ley-de-la-operadora-municipal-de-estacionamientos-de-juarez/` | LEY DE LA OPERADORA MUNICIPAL DE ESTACIONAMIENTOS DE JUAREZ | 3 | as first published, then each reform: 20 July 1990 to 23 June 2005 |
| `ley-de-la-universidad-pedagogica-nacional/` | LEY DE LA UNIVERSIDAD PEDAGOGICA NACIONAL DEL ESTADO DE CHIHUAHUA | 3 | as first published, then each reform: 7 August 2011 to 30 October 2025 |
| – | – | 3 | as first published, then each reform: 6 November 2008 to 30 October 2025 |
| `ley-de-la-universidad-tecnologica-de-camargo/` | LEY DE LA UNIVERSIDAD TECNOLOGICA DE CAMARGO DEL ESTADO DE CHIHUAHUA | 3 | as first published, then each reform: 6 December 2012 to 30 October 2025 |
| `ley-de-la-universidad-tecnologica-de-chihuahua/` | LEY DE LA UNIVERSIDAD TECNOLOGICA DE CHIHUAHUA | 4 | as first published, then each reform: 28 May 2000 to 30 October 2025 |
| `ley-de-la-universidad-tecnologica-de-chihuahua-sur-antes-ley/` | LEY DE LA UNIVERSIDAD TECNOLOGICA DE CHIHUAHUA SUR -ANTES LEY DE LA UNIVERSIDAD TECNOLOGICA JUNTA DE LOS RIOS DEL ESTADO DE CHIHUAHUA- | 4 | as first published, then each reform: 6 December 2012 to 30 October 2025 |
| `ley-de-la-universidad-tecnologica-de-ciudad-juarez/` | LEY DE LA UNIVERSIDAD TECNOLOGICA DE CIUDAD JUAREZ | 5 | as first published, then each reform: 13 June 1999 to 30 October 2025 |
| `ley-de-la-universidad-tecnologica-de-la-babicora/` | LEY DE LA UNIVERSIDAD TECNOLOGICA DE LA BABICORA, DEL ESTADO DE CHIHUAHUA | 3 | as first published, then each reform: 25 December 2011 to 30 October 2025 |
| `ley-de-la-universidad-tecnologica-de-la-tarahumara/` | LEY DE LA UNIVERSIDAD TECNOLOGICA DE LA TARAHUMARA | 3 | as first published, then each reform: 31 December 2009 to 30 October 2025 |
| `ley-de-la-universidad-tecnologica-de-paquime/` | LEY DE LA UNIVERSIDAD TECNOLOGICA DE PAQUIME DEL ESTADO DE CHIHUAHUA | 3 | as first published, then each reform: 6 December 2012 to 30 October 2025 |
| `ley-de-la-universidad-tecnologica-de-parral-en-el-estado-de/` | LEY DE LA UNIVERSIDAD TECNOLOGICA DE PARRAL EN EL ESTADO DE CHIHUAHUA | 3 | as first published, then each reform: 25 December 2011 to 30 October 2025 |
| `ley-de-la-universidad-tecnologica-paso-del-norte-estado-de-c/` | LEY DE LA UNIVERSIDAD TECNOLOGICA PASO DEL NORTE ESTADO DE CHIHUAHUA | 3 | as first published, then each reform: 21 April 2013 to 30 October 2025 |
| `ley-de-limites-intermunicipales/` | LEY DE LIMITES INTERMUNICIPALES DEL ESTADO DE CHIHUAHUA | 1 | as first published: 31 August 2013 |
| `ley-de-los-cuerpos-de-bomberos/` | LEY DE LOS CUERPOS DE BOMBEROS PARA EL ESTADO DE CHIHUAHUA | 1 | as first published: 3 July 2021 |
| `ley-de-los-derechos-de-ninas-ninos-y-adolescentes/` | LEY DE LOS DERECHOS DE NIÑAS, NIÑOS Y ADOLESCENTES DEL ESTADO DE CHIHUAHUA | 51 | as first published, then each reform: 1 January 2016 to 9 August 2026 |
| `ley-de-mejora-regulatoria/` | LEY DE MEJORA REGULATORIA DEL ESTADO DE CHIHUAHUA | 1 | as first published: 11 August 2019 |
| `ley-de-movilidad-y-seguridad-vial/` | LEY DE MOVILIDAD Y SEGURIDAD VIAL DEL ESTADO DE CHIHUAHUA | 2 | as first published, then each reform: 1 January 2025 to 9 July 2026 |
| `ley-de-obras-publicas-y-servicios-relacionados-con-las-misma/` | LEY DE OBRAS PUBLICAS Y SERVICIOS RELACIONADOS CON LAS MISMAS DEL ESTADO DE CHIHUAHUA | 3 | as first published, then each reform: 23 October 2018 to 25 January 2026 |
| `ley-de-participacion-ciudadana/` | LEY DE PARTICIPACION CIUDADANA DEL ESTADO DE CHIHUAHUA | 4 | as first published, then each reform: 24 June 2018 to 1 September 2024 |
| `ley-de-pensiones-civiles/` | LEY DE PENSIONES CIVILES DEL ESTADO DE CHIHUAHUA | 3 | as first published, then each reform: 24 December 2013 to 14 July 2019 |
| `ley-de-pensiones-seguros-de-vida-y-otros-beneficios-a-los-ve/` | LEY DE PENSIONES, SEGUROS DE VIDA Y OTROS BENEFICIOS A LOS VETERANOS DE LA REVOLUCION MEXICANA | 4 | as first published, then each reform: 20 November 1960 to 7 September 2017 |
| `ley-de-planeacion/` | LEY DE PLANEACION DEL ESTADO DE CHIHUAHUA | 11 | as first published, then each reform: 5 January 1989 to 5 September 2024 |
| `ley-de-prestacion-de-servicios-inmobiliarios/` | LEY DE PRESTACION DE SERVICIOS INMOBILIARIOS DEL ESTADO DE CHIHUAHUA | 1 | as first published: 3 June 2018 |
| `ley-de-presupuesto-de-egresos-contabilidad-gubernamental-y-g/` | LEY DE PRESUPUESTO DE EGRESOS, CONTABILIDAD GUBERNAMENTAL Y GASTO PUBLICO DEL ESTADO DE CHIHUAHUA | 9 | as first published, then each reform: 29 December 2013 to 21 December 2023 |
| `ley-de-prevencion-atencion-y-posvencion-del-suicidio/` | LEY DE PREVENCION, ATENCION Y POSVENCION DEL SUICIDIO DEL ESTADO DE CHIHUAHUA | 1 | as first published: 17 November 2024 |
| `ley-de-procedimiento-administrativo/` | LEY DE PROCEDIMIENTO ADMINISTRATIVO DEL ESTADO DE CHIHUAHUA | 1 | as first published: 3 December 2021 |
| `ley-de-profesiones/` | LEY DE PROFESIONES PARA EL ESTADO DE CHIHUAHUA | 9 | as first published, then each reform: 26 January 1998 to 17 October 2024 |
| `ley-de-proteccion-a-la-salud-de-los-no-fumadores/` | LEY DE PROTECCION A LA SALUD DE LOS NO FUMADORES PARA EL ESTADO DE CHIHUAHUA | 7 | as first published, then each reform: 8 November 2009 to 22 February 2024 |
| `ley-de-proteccion-civil/` | LEY DE PROTECCION CIVIL DEL ESTADO DE CHIHUAHUA | 10 | as first published, then each reform: 27 August 2015 to 19 April 2026 |
| `ley-de-proteccion-de-datos-personales/` | LEY DE PROTECCION DE DATOS PERSONALES DEL ESTADO DE CHIHUAHUA | 2 | as first published, then each reform: 7 September 2017 to 12 November 2017 |
| `ley-de-proteccion-y-apoyo-a-migrantes-y-sus-familias/` | LEY DE PROTECCION Y APOYO A MIGRANTES Y SUS FAMILIAS PARA EL ESTADO DE CHIHUAHUA (ANTES: LEY DE PROTECCION Y APOYO A MIGRANTES PARA EL ESTADO DE CHIHUAHUA) | 7 | as first published, then each reform: 24 July 2016 to 14 December 2023 |
| `ley-de-responsabilidad-patrimonial/` | LEY DE RESPONSABILIDAD PATRIMONIAL DEL ESTADO DE CHIHUAHUA | 2 | as first published, then each reform: 8 January 2013 to 23 February 2017 |
| `ley-de-salud-mental/` | LEY DE SALUD MENTAL DEL ESTADO DE CHIHUAHUA | 4 | as first published, then each reform: 14 June 2018 to 9 August 2026 |
| `ley-de-sanidad-e-inocuidad-vegetal/` | LEY DE SANIDAD E INOCUIDAD VEGETAL DEL ESTADO DE CHIHUAHUA | 2 | as first published, then each reform: 23 May 2021 to 2 June 2021 |
| `ley-de-seguridad-escolar/` | LEY DE SEGURIDAD ESCOLAR PARA EL ESTADO DE CHIHUAHUA | 8 | as first published, then each reform: 3 August 2004 to 28 May 2026 |
| `ley-de-seguridad-privada/` | LEY DE SEGURIDAD PRIVADA PARA EL ESTADO DE CHIHUAHUA | 5 | as first published, then each reform: 30 December 2012 to 22 July 2018 |
| `ley-de-transparencia-y-acceso-a-la-informacion-publica/` | LEY DE TRANSPARENCIA Y ACCESO A LA INFORMACION PUBLICA DEL ESTADO DE CHIHUAHUA | 8 | as first published, then each reform: 4 May 2016 to 11 January 2024 |
| `ley-de-transporte/` | LEY DE TRANSPORTE DEL ESTADO DE CHIHUAHUA | 3 | as first published, then each reform: 22 March 2020 to 30 July 2022 |
| `ley-de-turismo/` | LEY DE TURISMO DEL ESTADO DE CHIHUAHUA | 15 | as first published, then each reform: 20 May 2012 to 30 October 2025 |
| `ley-de-vialidad-y-transito/` | LEY DE VIALIDAD Y TRANSITO PARA EL ESTADO DE CHIHUAHUA | 40 | as first published, then each reform: 21 September 2006 to 9 August 2026 |
| `ley-de-victimas/` | LEY DE VICTIMAS PARA EL ESTADO DE CHIHUAHUA | 6 | as first published, then each reform: 1 January 2017 to 30 August 2026 |
| `ley-de-vida-silvestre/` | LEY DE VIDA SILVESTRE PARA EL ESTADO DE CHIHUAHUA | 4 | as first published, then each reform: 19 October 2014 to 2 July 2026 |
| `ley-de-vivienda/` | LEY DE VIVIENDA DEL ESTADO DE CHIHUAHUA | 11 | as first published, then each reform: 24 August 2012 to 9 August 2026 |
| `ley-del-agua/` | LEY DEL AGUA DEL ESTADO DE CHIHUAHUA | 15 | as first published, then each reform: 3 April 2012 to 19 April 2026 |
| `ley-del-archivo-general/` | LEY DEL ARCHIVO GENERAL DEL ESTADO DE CHIHUAHUA | 2 | as first published, then each reform: 20 August 2022 to 11 January 2026 |
| `ley-del-centro-de-conciliacion-laboral/` | LEY DEL CENTRO DE CONCILIACION LABORAL DEL ESTADO DE CHIHUAHUA | 2 | as first published, then each reform: 18 February 2018 to 4 October 2020 |
| `ley-del-colegio-de-chihuahua/` | LEY DEL COLEGIO DE CHIHUAHUA | 3 | as first published, then each reform: 30 October 2005 to 30 October 2025 |
| `ley-del-colegio-de-educacion-profesional-tecnica/` | LEY DEL COLEGIO DE EDUCACION PROFESIONAL TECNICA DEL ESTADO DE CHIHUAHUA | 3 | as first published, then each reform: 19 September 1999 to 14 March 2019 |
| `ley-del-himno-y-el-escudo/` | LEY DEL HIMNO Y EL ESCUDO DEL ESTADO DE CHIHUAHUA - ANTES LEY DEL HIMNO DEL ESTADO DE CHIHUAHUA- | 5 | as first published, then each reform: 27 August 2006 to 3 October 2016 |
| `ley-del-instituto-chihuahuense-de-educacion-para-los-adultos/` | LEY DEL INSTITUTO CHIHUAHUENSE DE EDUCACION PARA LOS ADULTOS | 9 | as first published, then each reform: 27 May 1999 to 30 October 2025 |
| `ley-del-instituto-chihuahuense-de-infraestructura-fisica-edu/` | LEY DEL INSTITUTO CHIHUAHUENSE DE INFRAESTRUCTURA FISICA EDUCATIVA | 6 | as first published, then each reform: 6 November 2008 to 9 August 2026 |
| `ley-del-instituto-chihuahuense-de-salud/` | LEY DEL INSTITUTO CHIHUAHUENSE DE SALUD | 6 | as first published, then each reform: 17 September 1987 to 3 October 2016 |
| `ley-del-instituto-de-apoyo-al-desarrollo-tecnologico-antes-l/` | LEY DEL INSTITUTO DE APOYO AL DESARROLLO TECNOLOGICO -ANTES LEY DEL INSTITUTO DE ENTRENAMIENTO EN ALTA TECNOLOGIA- | 6 | as first published, then each reform: 1 July 1999 to 28 March 2021 |
| `ley-del-instituto-de-capacitacion-para-el-trabajo/` | LEY DEL INSTITUTO DE CAPACITACION PARA EL TRABAJO DEL ESTADO DE CHIHUAHUA | 5 | as first published, then each reform: 13 September 2001 to 30 October 2025 |
| `ley-del-instituto-municipal-de-pensiones/` | LEY DEL INSTITUTO MUNICIPAL DE PENSIONES DEL ESTADO DE CHIHUAHUA | 5 | as first published, then each reform: 27 December 2015 to 22 June 2023 |
| `ley-del-instituto-para-el-desarrollo-salvalcar/` | LEY DEL INSTITUTO PARA EL DESARROLLO SALVALCAR | 1 | as first published: 8 October 1987 |
| `ley-del-notariado/` | LEY DEL NOTARIADO DEL ESTADO DE CHIHUAHUA | 2 | as first published, then each reform: 2 January 2020 to 1 November 2020 |
| `ley-del-organismo-publico-descentralizado-denominado-parque/` | LEY DEL ORGANISMO PUBLICO DESCENTRALIZADO DENOMINADO PARQUE CENTRAL DE CIUDAD JUAREZ, CHIHUAHUA | 1 | as first published: 8 December 2022 |
| `ley-del-periodico-oficial/` | LEY DEL PERIODICO OFICIAL DEL ESTADO DE CHIHUAHUA | 2 | as first published, then each reform: 25 August 2009 to 30 June 2013 |
| `ley-del-programa-escuela-para-madres-padres-o-quienes-ejerza/` | LEY DEL PROGRAMA ESCUELA PARA MADRES, PADRES O QUIENES EJERZAN LA TUTELA, GUARDA Y CUSTODIA PARA EL ESTADO DE CHIHUAHUA | 1 | as first published: 11 April 2024 |
| `ley-del-registro-civil/` | LEY DEL REGISTRO CIVIL DEL ESTADO DE CHIHUAHUA | 1 | as first published: 6 October 2016 |
| `ley-del-registro-estatal-de-personas-deudoras-alimentarias-m/` | LEY DEL REGISTRO ESTATAL DE PERSONAS DEUDORAS ALIMENTARIAS MOROSAS DE CHIHUAHUA | 2 | as first published, then each reform: 26 August 2021 to 10 July 2022 |
| `ley-del-registro-publico-de-la-propiedad/` | LEY DEL REGISTRO PUBLICO DE LA PROPIEDAD DEL ESTADO DE CHIHUAHUA | 3 | as first published, then each reform: 27 June 2010 to 23 February 2017 |
| `ley-del-sistema-anticorrupcion/` | LEY DEL SISTEMA ANTICORRUPCION DEL ESTADO DE CHIHUAHUA | 2 | as first published, then each reform: 22 October 2017 to 14 March 2019 |
| `ley-del-sistema-descentralizado-de-aseo-urbano-del-municipio/` | LEY DEL SISTEMA DESCENTRALIZADO DE ASEO URBANO DEL MUNICIPIO DE CHIHUAHUA | 1 | as first published: 16 September 1993 |
| `ley-del-sistema-estatal-de-seguridad-publica/` | LEY DEL SISTEMA ESTATAL DE SEGURIDAD PUBLICA DEL ESTADO DE CHIHUAHUA | 25 | as first published, then each reform: 13 October 2013 to 3 July 2025 |
| `ley-del-subsistema-de-preparatoria-abierta-y-telebachillerat/` | LEY DEL SUBSISTEMA DE PREPARATORIA ABIERTA Y TELEBACHILLERATO DEL ESTADO DE CHIHUAHUA -ANTES LEY DEL SUBSISTEMA DE PREPARATORIA ABIERTA DEL ESTADO DE CHIHUAHUA- | 4 | as first published, then each reform: 7 June 2012 to 30 October 2025 |
| `ley-electoral/` | LEY ELECTORAL DEL ESTADO DE CHIHUAHUA | 18 | as first published, then each reform: 23 August 2015 to 30 June 2026 |
| `ley-electoral-reglamentaria-de-los-articulos-99-100-101-102/` | LEY ELECTORAL REGLAMENTARIA DE LOS ARTICULOS 99, 100, 101, 102 Y 103 DE LA CONSTITUCION PARA ELEGIR PERSONAS JUZGADORAS DEL ESTADO DE CHIHUAHUA | 2 | as first published, then each reform: 24 January 2025 to 25 January 2025 |
| `ley-estatal-de-atencion-a-las-adicciones/` | LEY ESTATAL DE ATENCION A LAS ADICCIONES DEL ESTADO DE CHIHUAHUA | 6 | as first published, then each reform: 23 October 2011 to 5 December 2024 |
| `ley-estatal-de-bibliotecas/` | LEY ESTATAL DE BIBLIOTECAS | 3 | as first published, then each reform: 21 September 2006 to 27 September 2018 |
| `ley-estatal-de-derechos-de-chihuahua/` | LEY ESTATAL DE DERECHOS DE CHIHUAHUA | 8 | as first published, then each reform: 1 January 2022 to 7 January 2026 |
| `ley-estatal-de-educacion/` | LEY ESTATAL DE EDUCACION DEL ESTADO DE CHIHUAHUA | 109 | as first published, then each reform: 28 December 1997 to 2 July 2026 |
| `ley-estatal-de-justicia-civica-chihuahua/` | LEY ESTATAL DE JUSTICIA CIVICA, CHIHUAHUA | 2 | as first published, then each reform: 7 April 2024 to 30 October 2025 |
| `ley-estatal-de-proteccion-a-testigos/` | LEY ESTATAL DE PROTECCION A TESTIGOS | 5 | as first published, then each reform: 23 August 2009 to 2 December 2014 |
| `ley-estatal-de-salud/` | LEY ESTATAL DE SALUD DEL ESTADO DE CHIHUAHUA | 57 | as first published, then each reform: 15 April 2012 to 9 August 2026 |
| `ley-estatal-del-derecho-de-las-mujeres-a-una-vida-libre-de-v/` | LEY ESTATAL DEL DERECHO DE LAS MUJERES A UNA VIDA LIBRE DE VIOLENCIA, CHIHUAHUA | 32 | as first published, then each reform: 24 January 2007 to 2 July 2026 |
| `ley-general-de-sistema-de-documentacion-e-informacion-public/` | LEY GENERAL DE SISTEMA DE DOCUMENTACION E INFORMACION PUBLICA DEL ESTADO DE CHIHUAHUA | 6 | as first published, then each reform: 20 July 1997 to 3 October 2016 |
| `ley-hacienda/` | LEY HACIENDA DEL ESTADO DE CHIHUAHUA | 10 | as first published, then each reform: 1 January 2019 to 7 January 2026 |
| `ley-organica-de-la-contaduria-general-del-congreso/` | LEY ORGANICA DE LA CONTADURIA GENERAL DEL CONGRESO DEL ESTADO DE CHIHUAHUA | 7 | as first published, then each reform: 9 July 1995 to 13 September 2007 |
| `ley-organica-de-la-fiscalia-general/` | LEY ORGANICA DE LA FISCALIA GENERAL DEL ESTADO DE CHIHUAHUA | 40 | as first published, then each reform: 28 September 2010 to 21 May 2025 |
| `ley-organica-de-la-universidad-autonoma-de-chihuahua/` | LEY ORGANICA DE LA UNIVERSIDAD AUTONOMA DE CHIHUAHUA | 4 | as first published, then each reform: 28 June 2007 to 17 July 2022 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Chihuahua, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 3 days after publication.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.
