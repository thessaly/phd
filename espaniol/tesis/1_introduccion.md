# Capítulo 1 - Introducción

## ¿Qué es el hardware científico abierto?

Cuando se quiere definir el término 'hardware' en español aparecen varios inconvenientes. 
El primero es la falta de una traducción. ¿Cómo se traduce 'hardware'? ¿Se trata de materiales, herramientas, tecnologías, dispositivos? 
¿Incluye materiales biológicos, reactivos, herramientas analógicas, mecánicas?
¿Es necesario traducirlo? 

En segundo lugar aparece la asociación directa del término al ámbito de la informática. 
Coloquialmente en español entendemos el concepto 'hardware' como el soporte físico (ref RAE) o los componentes materiales de una computadora, equiparándolo al concepto de 'computer hardware' en inglés. 
Esto genera algunos problemas dado que se pierden en la traducción acepciones importantes. 
'Hardware' originalmente incluye al conjunto de equipamiento o componentes utilizados para un fin en particular (ref Merriam-webster). 
Se trata de una definición amplia, que abarca tanto herramientas para crear música como equipamiento militar o ferretería industrial, por nombrar algunos usos.

Este trabajo de tesis trata sobre el caso particular del hardware científico abierto. 
Tomamos la definición de 'hardware científico' de la comunidad Global por el Hardware Científico Abierto ó GOSH (2018):

> "El Hardware Científico Abierto (HwCA) refiere a cualquier tipo de hardware utilizado en investigaciones científicas que pueda ser obtenido, ensamblado, utilizado, estudiado, modificado, compartido y vendido por cualquier persona.
> Incluye equipamiento tradicional de laboratorio tanto como materiales auxiliares como pueden ser sensores, reactivos biológicos, componentes electrónicos analógicos o digitales."


El término 'abierto' que utilizamos también se toma de la convención de esta comunidad (GOSH, 2018):

> "La definición de Hardware científico abierto está en parte inspirada por las comunidades de Hardware Abierto y de Obras culturales Libres, pero los términos 'libre' (free) y 'abierto' (open) pueden prestarse a confusión.
> La palabra 'libre' (free) en inglés en el contexto de la tecnología se suele malinterpretar como 'gratis' (free of charge).
>
> Nosotros la entendemos, sin embargo, como la libertad de restricciones a comprar, hacer, utilizar, estudiar, modificar, compartir y vender.
> Estas libertades no implican que una tecnología deba ser gratis o no comercial.
>
> Utilizamos el término 'abierto' para el hardware científico en contraste al hardware cerrado propietario, pero se deben tener en cuenta los valores mencionados anteriormente."

Esta distinción entre 'abierto' y 'libre' deriva de la barrera idiomática y se puede observar en la mayoría de las comunidades que trabajan con materiales no propietarios. En español esa ambigüedad no existe, por lo cual es común encontrar los términos 'hardware libre', 'tecnologías libres', 'tecnologías abiertas' y otros en proyectos de Latinoamérica. 
Conociendo esta multiplicidad de denominaciones en la región, en este trabajo se utilizará la denominación 'hardware científico abierto' ya que figura oficialmente en la traducción al español del manifiesto GOSH.

La definición de GOSH hace referencia a dos comunidades: de Hardware Abierto (OSHWA) y de Obras Culturales Libres que son ligeramente diferentes. 

Por un lado la comunidad [Open Hardware Association (OSHWA)](https://www.oshwa.org/) toma la siguiente definición de apertura:

>"Hardware abierto es aquel hardware cuyo diseño se hace disponible públicamente para que cualquier persona lo pueda estudiar, modificar, distribuir, materializar y vender, tanto el original como otros objetos basados en ese diseño.
>
>Las fuentes del hardware (entendidas como los ficheros fuente) habrán de estar disponibles en un formato apropiado para poder realizar modificaciones sobre ellas. Idealmente, el hardware de fuentes abiertas utiliza componentes y materiales de alta disponibilidad, procesos estandarizados, infraestructuras abiertas, contenidos sin restricciones, y herramientas de fuentes abiertas de cara a maximizar la habilidad de los individuos para materializar y usar el hardware. El hardware de fuentes abiertas da libertad de controlar la tecnología y al mismo tiempo compartir conocimientos y estimular la comercialización por medio del intercambio abierto de diseños".

Por otro lado, desde las [Obras Culturales Libres](https://freedomdefined.org) la apertura se basa en las cuatro libertades:

>
- la libertad de usar el trabajo y disfrutar de los beneficios de su uso
- la libertad de estudiar el trabajo y aplicar el conocimiento adquirido de él
- la libertad de hacer y redistribuir copias, totales o parciales, de la información o expresión
- la libertad de hacer cambios y mejoras, y distribuir los trabajos derivados
>

Adicionalmente la obra debe estar cubierta por una licencia cultural libre, o su situación legal debe proporcionar las mismas libertades esenciales enumeradas anteriormente. Esto sin embargo no es condición suficiente, ya que una obra específica puede ser no-libre de otras maneras que restrinjan las libertades esenciales.

Otros criterios adicionales para que una obra sea considerada libre dentro de esta comunidad son:

>
- Disponibilidad de los datos fuente: Si un trabajo final ha sido obtenido mediante la compilación o procesamiento de uno o varios archivos fuente, todos los datos fuente subyacentes deben estar disponibles junto con el propio trabajo bajo las mismas condiciones.
- Uso de un formato libre: Para los archivos digitales, el formato en que se haga disponible el trabajo no debe estar protegido por patentes, salvo que se conceda un permiso libre de regalías, ilimitado, irrevocable y de ámbito mundial para hacer uso de la tecnología patentada.
- Sin restricciones técnicas: La obra debe estar disponible de una forma en la que no se usen medidas técnicas para limitar las libertadas enumeradas anteriormente.
- Sin otras restricciones o limitaciones: La propia obra no debe estar cubierta por restricciones legales (patentes, contratos, etc.) o limitaciones (como derechos de privacidad) que impidan las libertades enumeradas anteriormente.
>

Las definiciones de las dos comunidades no son sustancialmente distintas, pero la primera ilustra el mecanismo utilizado para resolver el problema del traspaso desde código a objetos abiertos, una de las dificultades más importantes identificadas en la literatura (González y Gómez-Arribas, 2003; Rubow, 2008; McManara, 2007; FLOK, 2015). 
Para que el hardware sea abierto, se considera que lo que debe abrirse son los archivos correspondientes a su diseño (esquemáticos, listas de materiales, instrucciones de uso y armado, software, etc). 

Esta dificultad plantea preguntas interesantes alrededor de los conceptos de apertura y accesibilidad.
¿Es abierto un desarrollo que tiene entre sus componentes un microprocesador que sólo puede ser fabricado en un lugar del mundo? ¿O un desarrollo que requiere de un expertise para ser utilizado, que no está disponible en ciertas comunidades?

Este capítulo tiene la intención de introducir el concepto de hardware científico abierto a través de un hilo imaginario que conecta las distintas etapas de desarrollo de un proyecto de hardware científico abierto.
Comienza con los orígenes y antecedentes, siguiendo con los factores macro que favorecieron el crecimiento exponencial de estas prácticas en los últimos años, para luego pensar qué razones movilizan a las personas a diseñar estos proyectos, cómo lo hacen, qué beneficios y qué obstáculos se presentan en el camino e incipientes recomendaciones de políticas de promoción. 
A su vez se introducen algunos casos relevantes a nivel global, ya sea por la importancia de sus comunidades o su rol de multiplicador de nuevas iniciativas.

***
>**Box 1: Arduino**  
>  
>Arduino es una plataforma de prototipado libre compuesta por una placa electrónica de entradas y salidas simple y un entorno de desarrollo que utiliza un lenguaje de programación fácil de usar. Los diseños del hardware y el software se encuentran liberados bajo licencia Creative Commons CompartirIgual 2.5 (Share-A-Like), lo que habilita a compartir, adaptar e incluso distribuir comercialmente los objetos creados en base a Arduino, siempre y cuando se indiquen las modificaciones realizadas y se mantenga el mismo tipo de licencia. Arduino funciona además como "marca", ya que se comercializan placas oficiales que pagan por llevar el nombre Arduino y otras que no y se definen como “Arduino-compatibles”.
>
> En su origen, Arduino fue pensado por un equipo de cinco personas en el Ivrea Interaction Design Institute en Turín, Italia, con el objetivo de contar con una herramienta sencilla de utilizar para estudiantes, que les permitiera fabricar objetos sin tener que contar con conocimientos avanzados de electrónica. Actualmente, además de la plataforma, Arduino es una comunidad organizada alrededor de su sitio web, donde más de 300 mil usuarios de distintas partes del mundo comparten sus diseños, recomendaciones y preguntas.
>
><img src="https://upload.wikimedia.org/wikipedia/commons/f/f8/Reprap_Darwin.jpg" width=50%>       
>_Fig. 1: Versión 1.0 (Darwin) de RepRap, la impresora 3D autorreplicable basada en Arduino (Fuente: Wikipedia)_
>
>
>Arduino posee algunas ventajas que lo volvieron una de las ‘estrellas’ del hardware libre, viralizando su uso en cientos de proyectos a escala global y motorizando así la nueva ola del movimiento maker. Los atributos que destacan en Arduino son, principalmente: bajos costos -la placa más sencilla cuesta menos de 25 dólares-, compatibilidad en todos los sistemas operativos -Windows, Macintosh, Linux-, utilizar un lenguaje de programación simple para los novatos pero con funcionalidades potentes para los expertos, y la posibilidad de contar con código abierto tanto en software como hardware, posibilitando el intercambio entre usuarios y sumando modificaciones y nuevas funcionalidades en base a experiencias de otros.
>
>Arduino es empleado, entre otros usos, para crear instrumental de laboratorio económico y adaptado a las necesidades de los científicos
>(Baden et al, 2015; Pearce, 2012), por docentes para enseñar programación y robótica a estudiantes (Bordignon, 2015; Valera et al, 2014), por músicos y artistas para experimentar y realizar nuevas instalaciones (Juan Cortés; Zach Gage), por ingenieros y diseñadores para prototipar nuevos artefactos (Gautam et al, 2016; Karvinen y Karvinen, 2011) y por ejemplo, construir dispositivos de accesibilidad -como anteojos o calzado para no videntes-.
***

## ¿Quiénes y por qué desarrollan hardware científico abierto?

Una de las discusiones centrales en la literatura open source es la de entender por qué las comunidades desarrollan tecnologías abiertas, qué motivaciones encuentran para invertir tiempo y energía en proyectos que pueden -o no- monetizarse, o qué otro tipo de retribuciones reciben los colaboradores. 
Al mirar el panorama de las comunidades que se encuentran desarrollando hardware abierto para ciencia el primer rasgo que surge es la heterogeneidad. 

Las motivaciones detrás de estos "hacedores" son diversas, abarcando un amplio espectro que incluye la figura del inventor hobbista y la tradición del “hágalo usted mismo”, las comunidades con una orientación política claramente definida, ancladas tanto en el autonomismo como el mediactivismo o la ética hacker, hasta nuevos emprendedores y organizaciones que comienzan a experimentar con modelos de negocio basados en la apertura.

Esta sección intenta reconstruir los contextos y motivaciones que consideramos más relevantes al análisis de la comunidad de hardware científico abierto.

### Filosofía del Software Libre

La contribución del movimiento de Software Libre es clave para las diversas ramas de la producción abierta y colaborativa que surgieron potenciadas por el uso de plataformas online (Benkler, 2006).
Aunque el dominio específico de este movimiento sea el ámbito de la computación, su contribución fundamental radica en su filosofía y el uso de copyleft. 
Su principal referente es Richard Stallman, quien en 1985 creó la Fundación por el Software Libre (FSF por sus siglas en inglés). 
Después de graduarse en Harvard en 1971 Stallman comenzó a trabajar en el laboratorio de Inteligencia Artificial del MIT como programador, en un ambiente signado por la cultura hacker y la colaboración entre pares:

> Whenever people from another university or a company wanted to port and use a program, we gladly let them. If you saw someone using an unfamiliar and interesting program, you could always ask to see the source code, so that you could read it, change it, or cannibalize parts of it to make a new program (Stallman, 1999)

Este panorama de libre intercambio de código mutó hacia el inicio de la década de los '80. 
Por un lado la comunidad hacker(1) se vio desintegrada por el éxodo de los integrantes del laboratorio hacia empresas privadas. 
Por otro lado, los fabricantes comenzaron a imponer restricciones a la copia y redistribución de código alegando razones de competencia y amparados por la recientemente publicada Ley de Copyright de Estados Unidos, en 1976 (ref). 
Este carácter privativo de la producción de código continuaría en auge hasta el día de hoy, aunque con matices en los últimos años.

A partir de este cambio en 1983 Stallman inicia el proyecto GNU ("GNU's Not UNIX") con el fin de producir un sistema operativo completamente libre. 
UNIX en ese entonces era uno de los sistemas operativos más ampliamente utilizados, privativo, creado por Ken Thompson y Dennis Ritchie tras abandonar un proyecto con MIT y sumarse a AT&T Bell Laboratories. 
Contar con un sistema operativo libre constituía la base que habilitaría cualquier desarrollo de código posterior.

Con el propósito de garantizar que la distribución de GNU no se volviera propietaria, Stallman crea el método 'copyleft': utiliza la ley de copyright para garantizar que el producto siga siendo libre, de forma contraria a su propósito original. 
El instrumento específico que utiliza es la "Licencia Pública General de GNU" (o GNU GPL por sus siglas en inglés), una licencia que garantiza al usuario libertades de uso, modificación, distribución y estudio al mismo tiempo que le impide agregar futuras restricciones a estas mismas libertades.

A principios de los años '90 existía suficiente desarrollo en la comunidad GNU como para crear un sistema operativo funcional, sin embargo el núcleo o kernel (Hurd) no estaba lo suficientemente desarrollado. 
Esto es lo que comenzó a desarrollar en 1991 Linus Torvalds, y que publicaría luego como Linux kernel bajo la licencia GPLv2, habilitando el uso de GNU-Linux a escala global.

Compartir de forma pública las innovaciones o mejoras realizadas de forma individual no constituye una novedad a través de la historia, ya que pueden rastrearse antecedentes en áreas tan diversas como la industria del hierro en el siglo XVIII (Allen, 1983) o el equipamiento médico (Von Hippel and Finkelstein,1979). 
Sin embargo el aporte del movimiento por el Software Libre a través del concepto de copyleft, sus licencias y la promoción del modelo de producción de pares sistematizó una forma de trabajar -e innovar- colaborativa, de libre circulación de la información. 

Según Mansell y Berdou (2008), GPL establece un proceso de governanza auto-propagador por fuera del control de autoridades nacionales, internacionales u organismos de regulación que usualmente controlan el diseño, producción y circulación del conocimiento y la información.
Esto inspiró otros movimientos en diversas áreas (open Source drugs, Open Design, Free Culture, Open Source Ecology para nombrar algunos), incluyendo el desarrollo de hardware.

Uno de los más importantes derivados del desarrollo del proyecto GNU y el trabajo de la Fundación por el Software Libre es el concepto de "Código abierto" (open source). 
Surge como respuesta de un grupo de programadores al término "software libre", dentro del mismo movimiento. 
El contenido político y la ambiguedad en inglés del término 'free software' -que lo asocia a gratuidad- volvían difícil su adopción en el ámbito de los negocios. 
Es por esto que deciden generar un nuevo concepto, orientado a resaltar los beneficios en términos de colaboración y eficiencia, más cercano a la terminología empresarial.

En 1998 Eric Raymond -programador, autor de *'La Catedral y el Bazar'*, referencia en el ámbito open source-, hace un llamado público a la comunidad de software libre a adoptar el nuevo término y funda la asociación "Open Source Initiative". 
Contó con el apoyo de muchos personajes importantes de la comunidad en el primer "Open Source Summit"; dentro de quienes apoyaron la iniciativa se encontraba Linus Torvalds. 
Richard Stallman se opone al concepto de código abierto ya que "resalta la posibilidad de crear software potente y de alta calidad, pero evita las ideas de libertad, comunidad y principios".

A modo de ejemplo de las controversias en la comunidad, en 2007 luego de años de discusiones en la comunidad de software libre se lanzó la licencia GPLv3.
La mayor diferencia entre las versiones v2 y v3 es que la última prohíbe la 'tivoización', concepto acuñado por Stallman para referirse a dispositivos que utilizan software con licencia GPLv2 pero limitan las libertades del usuario mediante modificaciones de hardware. 
Torvalds se alejó de la discusión y no adoptó la GPLv3, por lo cual Linux sigue siendo GPLv2.

La visión del grupo disidente creció tanto en número como influencia convirtiéndose en hegemónica en la actualidad, con licencias específicas open source (ref) y un cada vez mayor número de compañías utilizando software de código abierto (ref), entre las cuales se encuentran grandes nombres como Google, Facebook o Microsoft. 
En los últimos años la definición de Código Abierto (ref) incluyó requerimientos adicionales a la libre disponibilidad del código, incorporando cláusulas de no discriminación a las personas, colectivos o grupos de trabajo.

***
>**Box2: Hardware científico abierto en CERN**
>
>
***

### Cultura hacker
Como se mencionaba anteriormente, la filosofía del software libre es uno de los pilares del movimiento de hardware abierto y en particular de hardware abierto científico. 
En los años de surgimiento alrededor de 1980 el MIT fue uno de los lugares donde la cultura hacker comenzó y floreció; la visión de este grupo se ve expresada en uno de los textos claves de la época: *'Hackers: Heroes of the Computer Revolution'* (Levy, 1984).

El libro de Levy hace explícita una 'ética hacker' que incluye compromiso con la libre circulación de la información, la meritocracia y la creencia de que puede construirse un mundo mejor y más bello utilizando computadoras.
Numerosas aproximaciones a la cultura hacker invocan este hito aplicándolo a toda la comunidad y obviando las múltiples y diversas motivaciones que coexisten dentro de ella (Coleman, 2009).

El concepto de libertad, ya sea en términos de libertad de expresión, privacidad, meritocracia o poder de los individuos, es constituyente principal del discurso hacker (Coleman, 2004; Kelty, 2005, 2008). 
Sin embargo la articulación de estos conceptos liberales toma diferentes formas en la interacción con sistemas socio-técnicos diversos, creando un set de expresiones relacionadas pero diferentes en torno a la propiedad, el trabajo y la creatividad (Coleman y Golub, 2008).

Maxigas (2012) propone reconstruir estas identidades diversas a partir de una genealogía de dos de los espacios predominantemente habitados por la comunidad hacker a partir de los años '90: los hackerspaces y los hacklabs. 
Esta aproximación resulta útil porque muestra dos polos dentro del gradiente de orientaciones, que dan origen a los múltiples ensamblados que encontramos en la actualidad.
Además permite entender cómo sobre la figura de los hackerspaces, por ejemplo, se suman en los últimos años nuevas comunidades como la de Biohacking.

#### Hacklabs, autonomistas y mediactivistas 
El primero de los casos se centra alrededor del espacio de los ‘hacklabs’. Yuill (2008) los define como "*[...] espacios voluntarios que proveen acceso público y gratuito a computadoras y a Internet. Usualmente hacen uso de máquinas recuperadas y recicladas que corren GNU/Linux y a la vez que proveen acceso a computadoras, la mayoría de los hacklabs tienen talleres funcionando en un rango de temas que van desde el uso básico de la computadora e instalación de software GNU/Linux, hasta programación, electrónica y radiodifusión independiente (o pirata). Los primeros hacklabs se desarrollaron en Europa, usualmente surgiendo de tradiciones de centros sociales ocupados y media labs comunitarios. En Italia se les relaciona con los centros sociales autonomistas y en España, Alemania y en los Países Bajos con movimientos de ocupación anarquistas"*. 

Los movimientos autonomistas, basados en conceptos marxistas y anarquistas, tuvieron relevancia en los años '70 en Italia, Alemania y Francia con la premisa de proveer alternativas a las instituciones administradas por el Estado. 
Una de sus estrategias era el squatting u ocupación de inmuebles, donde una de las funciones de los espacios ocupados era la de 'centro social' donde se reproducían alternativas a las instituciones oficiales.

El medioactivismo era otra práctica difundida, sobre una tradición de publicación independiente con hitos en la radiodifusión pirata y comunitaria desde los años '60. 
Las comunidades de medioactivistas apropiaron tecnologías de consumo masivo como grabadoras y otros productos electrónicos accesibles en los años '80, y luego computadoras personales. 
Su objetivo entre otros era bajar las barreras para la participación de la producción cultural y tecnológica, y establecer una infraestructura de comunicación distribuida para organizaciones anticapitalistas. 
Como tales, tuvieron un rol importante en el surgimiento del movimiento alternativo a la globalización: la iniciativa de mayor resonancia en este sentido fue la red Indymedia de comunicación independiente.

Estas dos tendencias se combinan en el origen de los hacklabs. Los centros sociales ocupados, en el corazón de la vida urbana, requerían de infraestructuras de comunicación como acceso público a internet y computadoras.
Los mediactivistas, por el otro lado, requerían estrategias para convocar, producir, enseñar y aprender sobre sus prácticas.

Algunos ejemplos de hacklabs son Ultralab en Forte Prenestino, Italia, surgido a fines de los '90, que se autodefine como un 'patrón emergente' de la conjunción de necesidades tecnológicas de las comunidades que lo integran. 
Otro ejemplo más reciente es Hackney Crack House en Londres, que hasta 2012 proveía una red de área local y servidor al espacio ocupado donde se alojaba, y funcionaba como lugar de reunión para experimentar con distintas tecnologías.

Los hacklabs son espacios declaradamente políticos enfocados en desarrollar infraestructura de comunicaciones para las comunidades que los habitan, privilegiando la creatividad y el acceso a quienes generalmente se ven inhabilitados para ello.

***
>**Box3: Estrógenos abiertos, gynepunk**
>
>
***

#### Hackerspaces y expansión
El caso de los hacklabs describido anteriormente es un extremo del espectro político dentro de un gradiente que incluye fablabs, makerlabs, medialabs, innovation labs y espacios de co-working.
Los últimos dos (y también los fablabs), de surgimiento más reciente, se distinguen por estar inmersos en un contexto institucional (universitario, gubernamental, organización o empresa); su fin es la innovación en investigación o productos comerciales.
Lo que diferencia a los hackerspaces del resto de estos espacios es que están administrados por y para integrantes de la comunidad hacker.

La primer ola de hackerspaces se relaciona a la cultura hacker universitaria ya mencionada del MIT y otros institutos en los Estados Unidos, donde se desarrollaban las primeras computadoras y sistemas operativos.
Esta escena se completaba con grupos que hacían ingeniería reversa de las nuevas tecnologías (phreakers), en ese momento mayoritariamente redes telefónicas.
En Europa la historia está menos documentada pero uno de los hitos es la fundación del Chaos Computer Club en 1981, con fuerte foco en la investigación sobre seguridad informática y privacidad.

Una nueva ola de hackerspaces parece haber sido iniciada a partir de una serie de conferencias en 2007 y 2008, orientadas a los problemas prácticos de cómo se administra y organiza un espacio de estas características.
Resulta relevante ya que pone el concepto de hackerspace al frente y la creación de nuevos espacios en la agenda de la comunidad. 

Estos nuevos espacios fomentan un modelo de membresía abierto con funciones de aprendizaje, producción y socialización.
Aunque las actividades varían entre distintos espacios, Maxigas (2012) identifica una progresión desde las tareas de desarrollo de software libre hacia las de hardware, primero con desarrollo de infraestructura de redes, luego microelectrónica y en algunos casos impresión 3D - fabricación digital.
El surgimiento de Arduino provocó una explosión de proyectos e interacción en este tipo de espacios, muchos de ellos con fines educativos, facilitando el diálogo con las instituciones formales como universidades o escuelas. 

El desarrollo y expansión de los hackerspaces se alinea con la trayectoria del movimiento hacker, que gana cada vez mayor anclaje institucional.
La apertura al trabajo con interfaces físicas (mayoritariamente microcontroladores) permitió el crecimiento masivo del modelo, ya que la colaboración en este tipo de proyectos se ve facilitada por la disponibilidad de espacios comunes. 
El contenido político de estos espacios es más difuso, más orientado a valores liberales, lo que le permite una flexibilidad de discurso y expansión hacia un espectro mayor de actores: desde el público general a las empresas.

***
>**Box4: flypi**
>
>
***

### Cultura Do-it-yourself (DIY)
Las actividades en los hackerspaces confluyen en numerosas oportunidades con la cultura del **Hágalo Usted Mismo** (“Do it yourself” o DIY, también autodenominados 'makers'), mencionada anteriormente aldededor del desarrollo de Arduino, RaspberryPi y otros microcontroladores accesibles al gran público.
Algunos antecedentes culturales de estas actividades incluyen las actividades de radio aficionados (Douglas, 1987) y las prácticas DIY de mitad de siglo XX en Estados Unidos (la figura del inventor o hobbista), donde actividades previamente conceptualizadas como utilitarias se transformaron en recreativas (Haring, 2006).

En la actualidad resulta útil la distinción que Hertz (2011) realiza sobre DIY utilitario y DIY hedonista.
El primero responde a la necesidad de construir objetos con los materiales disponibles, muchas veces escasos o inapropiados, para resolver problemas de la vida cotidiana. 
Por ejemplo, el científico que en un laboratorio sin recursos desarrolla hardware de bajo costo para obtener más muestras, o el que se encuentra estudiando un proceso y construye hardware que le permita ponerlo a prueba.
Ambas situaciones están documentados para el caso del instrumental científico (von Hippel, 1976).

Por otro lado el DIY hedonista refiere al elemento lúdico, la exploración personal y el aprendizaje de nuevos métodos en el espectro de motivaciones.
En la mayoría de los espacios más visibles de la comunidad maker (revista MAKE, MakerFaire, HackaDay, Instructables) el DIY hedonista es predominante, especialmente en proyectos de personalización del consumo.
Más allá de ser útil al análisis y la comprensión de las motivaciones, en la realidad ambos conceptos suelen superponerse.

Según Mark Frauenfelder -editor jefe de la revista MAKE, de referencia para el sector- las motivaciones de la comunidad maker responden a una insatisfacción con la cultura del consumo y del descarte, y a una revalorización del concepto japonés de *wabi-sabi* o la "*apreciación de la imperfección de los objetos*" (Suzuki, D.1959). 
Hertz suma a esto la motivación generada por reacción a la cultura de la caja negra (“black box”) típica de la fabricación en la era digital: la velocidad de las innovaciones en materia de tecnología implica que los objetos de consumo estén producidos basándose en componentes y procesos complejos. 

El concepto de caja negra implica que no es posible para el usuario comprender su lógica interna sino sólo el resultado de su funcionamiento, incluso siendo experto. 
Si un objeto se rompe o queda obsoleto, se vuelve inutilizable y genera dependencia de los fabricantes, lo cual es altamente frecuente dados los paradigmas de obsolescencia programada dominantes en la industria. 
Reemplazar partes es casi imposible para los consumidores, dada la alta especialización de la ingeniería y fabricación que el objeto conlleva. 
Este rol pasivo de los consumidores genera una reacción por parte de la comunidad DIY, que construye objetos de consumo con componentes simples y compartiendo información, algo que Frauenfelder engloba en el concepto de “vivir auténticamente”.

A nivel de comunidad, los "makers" cuentan con reuniones y exposiciones anuales -Maker Faire en Nueva York, San Francisco y Nairobi, por ejemplo-, el desarrollo de un mercado cada vez más importante de componentes y kits electrónicos de fácil utilización (Powell, 2012) y la existencia de la revista *MAKE*, una especie de continuo de la revista *Popular Mechanics* de mediados del siglo XX, orientada a la clase media y las actividades hobbistas de tiempo libre. 
El papel de MAKE no es menor: varios autores le asignan el rol de moldear y normativizar el rumbo que toma la comunidad en base a las prácticas que se difunden a través de ella.

Específicamente la cultura DIY en el rubro del instrumental científico creció exponencialmente en los últimos años, tanto dentro como fuera de la academia. 
Ejemplos de ésto son los desarrollos que se realizaron en diversas áreas, sólo contando los basados en Arduino: UAVs for oceanographic research (Busquets, et al., 2012), behavioral experiments (D’Ausilio, 2012), pressure monitoring (Russell et al., 2012), drop velocity measurements (Fobel, et al., 2013), microscopy (Gualda, et al., 2013), electrophysiology (Newman, et al., 2012), Skinner boxes (Pineño, 2014), and multi-spectral in-vivo optical image acquisition (Sun et al., 2010). 

Cuando la distinción entre DIY hedonista y utilitario se quiere aplicar al hardware abierto científico surgen algunos problemas, ya que la percepción es que las motivaciones son híbridas. 
Según el análisis de Kera (2018) sobre iniciativas de hardware científico abierto, éstas integran la ciencia a la vida cotidiana y por lo tanto a esferas políticas, artísticas y lo que denomina 'ciencia artesanal' (usos exploratorios).
Los artesanos científicos combinan la búsqueda del conocimiento y la construcción de instrumentos con las necesidades de sus comunidades (utilitario) pero también con las propias (espíritu lúdico).

Este aspecto híbrido los vuelve puentes útiles entre dominios del conocimiento generalmente desconectados (ingeniería, humanidades, arte, ciencia) pero también con el dominio cívico como el activismo, la colaboración y los valores comunitarios.
En particular en Latinoamérica esta visión política está influenciada por movimientos surgidos en los años '80, como se describe más adelante.

***
>**Box5: kalpana**
>
>
***

### Biohacking o DIY biology
Garage biology, biohacking o biología ciudadana/comunitaria son expresiones que describen un movimiento de amateurs realizando experimentos biológicos fuera de los ámbitos tradicionales como universidades o corporaciones.
Delfanti () analiza *DIYbio*, la iniciativa más reconocida del ambiente, una red creada en 2008 compuesta de varios grupos en ciudades de Europa y Estados Unidos.
DIYbio tiene como objetivo proveer a los no expertos con un espacio de colaboración y protocolos y herramientas de código abierto para la investigación biológica.
Como tales, son parte del fenómeno de la producción abierta y colaborativa a través de plataformas online (Benkler, 2006).

Los miembros de la comunidad tienen relación con el movimiento hacker: desarrollan sus espacios bajo el modelo de hackerspaces o directamente instalan una sección 'bio' en hackerspaces existentes.
Están además inmersos en una red de emprendedores y start-ups que enfrentan al gran mercado de las compañías del rubro de la biotecnología.
En 2008 el movimiento comenzó con Mackenzie Cowell, un desarrollador web, y Jason Bobe, parte del proyecto Genoma en la escuela de Medicina de Harvard.
En 2010, cerca de 2000 personas eran parte de la lista de correos y existían docenas de grupos comunitarios desde Boston a Bangalore.

Las actividades incluyen proyectos de ciencia ciudadana simples como aislamiento de bacterias o extracción de ADN, pero también construcción de hardware científico abierto (Ward, 2010).
DIYbio dialoga con instituciones como universidades, compañías, medios y agencias gubernamentales preocupadas por cuestiones de ética y seguridad (Schmidt, 2008).
Sus miembros son jóvenes biólogos, profesionales de la computación que desean experimentar en biología y artistas interesados en un abordaje crítico DIY a la biología.

En cuanto a cómo se definen, la comunidad nombra referencias como la cultura hacker, el DIY y el movimiento del Software libre, el espíritu lúdico y 'biopunk'.
Establecen comparaciones con el *Homebrew Computer Club*, el centro de operaciones hacker de los '70 en la Bahía de San Francisco donde se encontraban Steve Wozniak, Bill Gates, Steve
Jobs y otros (Bloom, 2009; Economist, 2009; Golob, 2007; Johnson, 2008). 
Otros se definen como makers, artesanos, entusiastas, hobbistas o amateurs pero coinciden en la visión de la innovación norteamericana y la cultura de garage.

Como colectivo resaltan la importancia del rol educativo sobre las biotecnologías, especialmente frente a dudas sobre seguridad o ética en las prácticas (DIYbio 2010). 
La apertura es un requisito de la iniciativa a fin de volver el campo *'accesible para quien desee involucrarse'*.
El acceso a equipamiento científico es uno de los obstáculos principales en estos proyectos, siendo uno de los ámbitos más productivos del hardware científico abierto con ejemplos como OpenPCR (http://openpcr.org). 

***
>**Box6: hackteria**
>
>
***

### Latinoamérica: el movimiento de tecnología apropiada y las pedagogías críticas
El panorama del hardware científico abierto tanto en Latinoamérica como en otras regiones del denominado 'Sur Global' presenta algunas particularidades; en general el discurso se orienta hacia las potencialidades que el mismo puede tener para el desarrollo, conectando con temáticas postcoloniales (Kera, 2018).
Esta orientación está presente en GOSH desde el manifiesto bajo las ideas de empoderamiento, justicia cognitiva, brecha norte-sur, conocimientos indígenas, desarrollo endógeno.
En Latinoamérica existen grupos que son parte de GOSH y trabajan en temáticas cercanas a la agroecología, la educación popular y la revalorización del conocimiento indígena.

Estas concepciones y áreas de trabajo se alinean con las ideas del movimiento de Tecnología Apropiada, predominante en los años '80 en la región. 
Las ideas de la Tecnología Apropiada (TA) se originaron en los debates sobre desarrollo y asistencialismo de los años '60, bajo el concepto de tecnologías para el desarrollo. 
La búsqueda se orientaba a principios de diseño de tecnologías situadas, ambiental y socialmente justas involucrando comunidades locales (Kaplinksy, 1990; Willoughby, 1990).
El término 'tecnología apropiada' implicaba un set de características comunes: tecnologías de bajo costo, fabricadas con materiales locales, generadoras de empleo, empleando mano de obra local, pequeña escala, sin requerir expertise o educación de tipo hegemónico 'occidental', de uso colaborativo o colectivo, sin uso de patentes o propiedad intelectual. 

Los actores e instituciones alrededor de la TA eran diversos, incluyendo activistas, extensionistas, educadores, ingenieros, algunos científicos, organismos de financiación y hacedores de políticas.
El movimiento llegó a Latinoamérica a principios de los años '80 en tiempos de represión política, ajuste económico y crisis de deuda internacional. 
A nivel internacional ya se encontraba perdiendo fuerza frente al neoliberalismo (Kaplinksy, 1990), sin embargo a nivel regional ganó momento basándose en las ideas de la teoría de la dependencia estructural y la ‘Escuela Latinoamericana de Pensamiento en Ciencia, Tecnología y Desarrollo’.

Casi todos los países de Sudamérica tuvieron algún tipo de actividad de TA en este período en forma de centros y programas de investigación autónomos.
Estos centros reunían ingenieros, economistas, sociólogos y trabajadores sociales, algunos estudiantes y voluntarios y escasos vínculos a instituciones académicas.
Las ideas globales de la TA no se ajustaban a la realidad latinoamericana de los '80, por lo que la primer tarea de los centros fue desarrollar nuevos marcos en torno a los actores, situaciones y problemas locales.

Lo que caracterizó al movimiento en Latinoamérica fue su esfuerzo por construir un abordaje distinto, participativo que utilizara la tecnología como una herramienta para la autonomía y el empoderamiento.
Sus impulsores experimentaban con metodologías que permitieran a las comunidades definir sus propios problemas y testear sus alternativas. 
Las ideas de la TA en la región fueron inevitablemente influenciadas por los debates e ideas de la educación popular, investigación acción participativa, agroecología y revalorización del conocimiento indígena. 
Autores como Paulo Freire y Orlando Fals Borda eran muy influyentes, lo que contribuyó a delinear nuevas aproximaciones a la participación (Kaimowitz, 1993). 
A través del desarrollo de artefactos, técnicas y prácticas materiales se pretendía desarrollar autonomía y crear nuevas formas de activismo y conciencia política para generar empoderamiento. 
Se trataba de una aproximación práctica, que surgía del trabajo a campo y por ende flexible a incorporar distintos enfoques; las metodologías incluían por ejemplo procesos de co-diseño de tecnologías, auto-organización y construcción desde los usuarios.

A medida que las políticas neoliberales comenzaron a predominar en la región, las agencias de desarrollo se vieron somentidas a "ajustes estructurales" (Rist, 2011). 
Algunas iniciativas de TA lograron sobrevivir a partir de fondos que buscaban reconstruir procesos de democratización luego de las dictaduras latinoamericanas, aunque con enfoques diferentes. 

Las ideas del movimiento de TA impulsaron nociones sobre la tecnología que pueden rastrearse en distintas iniciativas, como la Red de Tecnologías Sociales en Brazil a comienzos del siglo XXI.
Los procesos de participación pública e inclusión de conocimientos locales son una práctica común en los proyectos actuales de desarrollo (Chambers, 1997; Pieterse, 1998), con sus críticas (Cooke & Kothari, 2001; Hickey & Mohan, 2004).
En la actualidad, esta concepción del hardware científico abierto 'para el desarrollo' se puede observar en el trabajo de grupos con comunidades locales alrededor de temáticas principalmente de daño ambiental (monitoreo comunitario) y agroecología, pero también con iniciativas como Trend4Africa, donde el hardware científico abierto permite equipar laboratorios de bajos recursos en varios países africanos.

***
>**Box7: public lab**
>
>
***

## ¿Por qué ahora?
Como se menciona en las secciones anteriores, la filosofía del software libre surgió en los años '80, la cultura del do-it-yourself tiene raíces aún anteriores y los científicos modifican sus equipos y herramientas desde hace al menos 30 años (von Hippel, 1976).
Sin embargo en los últimos años se puede observar un crecimiento explosivo de los proyectos de hardware abierto para ciencia: colorímetros (Anzalone et al., 2013a), sistemas fotométricos para cuantificar nitratos enzimáticos (Wittbrodt, et al., 2015), nephelometers (Wijnen et al. 2014a), turbidímetros (Kelly et al., 2014), liquid auto-samplers (Carvalho and Eyre, 2013), operadores de microfluidos (Da Costa, et al., 2014), equipos para biotecnología (Lucking et al., 2014; Gross et al., 2014; Su et al., 2014), espectroscopía de masa (Malonado-Torres et al., 2014; Chiu and Urban, 2015), automated sensing arrays (Wittbrodt, et al. 2014), phasor measurement units (Laverty et al., 2013), syringe pumps (Wijnen et al., 2014b), optics and optical system components (Zhang et al., 2013), nanotecnología para trabajar con ADN (Damase et al., 2015), monitoreo ambiental (Pearce, et al., 2012; Chemin et al., 2014) and compatible components for plasma physics labs (Zwicker et al., 2015) and medical apparatuses like magnetic resonance imaging systems (Hermann et al., 2014).

Históricamente las grandes compañías dominan la producción de hardware por dos razones: la fabricación es costosa y requiere de expertise.
Huang (2017) alega que la desaceleración de la performance en innovación de las grandes compañías habilita una ventana de oportunidad para el hardware abierto, sumado a una ola de la cultura de la reparación a medida que más tecnología se vuelve obsoleta.
La literatura coincide en que la aparición de plataformas de prototipado de bajo costo y accesibilidad en términos de expertise, como Arduino, jugaron un rol fundamental en este salto (Pearce, 2017; Söderberg, 2013; Powell, 2012). 
Otro factor de relevancia es la difusión de la fabricación digital con herramientas como impresoras 3D (ver Box XXX), clave para el desarrollo de proyectos de hardware abierto, pero también cortadoras láser, CNC y otros (Söderberg, 2013).

La práctica colaborativa de compartir los diseños, facilitada por la masificación de internet como medio de comunicación de bajo costo, permitió que se formen comunidades alrededor de los dispositivos donde la información circula libremente.
Adicionalmente la infraestructura necesaria para la colaboración alrededor del hardware encontró lugar en la creación de innumerables espacios físicos de innovación de distinto tipo, ya sean hacklabs, makerspaces, fablabs, centros comunitarios de innovación u otros (Maxigas, 2012; Kera, 2012).

Powell (2012) resalta como los costos también bajan a partir de que muchas formas de hardware antes electrónicas pueden hoy ser reemplazadas con software, y componentes simples pueden ser impresos en diversos materiales a bajo costo. 
Von Hippel, también en este sentido, menciona cómo la habilidad de innovar de los usuarios es mayor en los últimos años gracias a la disponibilidad de software y hardware de alta calidad y facilidad de uso sumado al acceso a información compartida.

Actualmente es posible diseñar un prototipo virtualmente, probarlo y obtener una primera versión física sin demasiado esfuerzo, que posteriormente puede fabricarse a escala previa adaptación del diseño, por ejemplo en China.
En el mundo del hardware abierto para productos de consumo esto es una práctica difundida, que lentamente comienza a ser explorada en el ámbito del hardware abierto para ciencia.
Pearce aduce que se habrían reducido los costos de producir hardware científico en un 90–99% respecto de equipos propietarios de misma funcionalidad (Pearce, 2014a; Pearce,  2014b). 

> **Box 8: RepRap**
>
>La construcción de una impresora RepRap constituye muchas veces uno de los primeros momentos de aprendizaje de los entusiastas de la fabricación digital.  
>
>De forma similar a Linux, RepRap comenzó en 2005 como un proyecto universitario del Dr. Adrian Bowyer de la Universidad de Bath, con el objetivo de construir una impresora auto-replicable. Es decir, una impresora que pudiera imprimir las partes para construir una nueva impresora. A partir de la colaboración online en blogs y wiki, los usuarios fueron construyendo copias del primer prototipo, realizando modificaciones que documentaban y ponían a disposición online.
>
><img src="https://upload.wikimedia.org/wikipedia/commons/c/c7/RepRap_%27Mendel%27.jpg" width=70%>    
>_Fig. 8: RepRap 2.0, versión Mendel (Fuente: Wikipedia)_
>
>Uno de los disparadores del boom de la impresión 3D ha sido la expiración de las patentes de los equipos originales de impresión (The Economist 2013), creados en la década de los ochenta. Por ejemplo, en 2009 expiró la patente del proceso de modelado por deposición fundida (conocidas como FMD por su sigla en inglés) que utiliza filamentos plásticos. La caída de las patentes permitió una explosión de experimentación con nuevas impresoras, de la cual surgió RepRap, que utilizando el modelo open source permite que cualquier usuario realice modificaciones y mejoras en las máquinas. Desde ese momento, la impresoras 3D FDM se convirtieron en un objeto de escritorio y su costo se redujo hasta menos de los mil dólares en los modelos fabricados por los usuarios (Mins 2013).
>
>En 2011 nació el grupo conocido como "Clone Wars" dentro de la comunidad RepRap, con el fin de documentar en español todo lo necesario para que cualquier persona pueda construir su propia impresora 3D.

## ¿Cuáles son los principales usos del hardware abierto? **FALTA**

### Ciencia y tecnología en contextos académicos

Uno de los sectores donde el OSHW ha tenido mayor impacto ha sido el de desarrollo de instrumental para laboratorios científicos. Combinando el uso de Arduino e Impresión 3D, investigadores de diversos puntos del planeta comienzan a generar instrumental específico, que permite automatizar la toma de datos a menores tiempos y costos de investigación. Esto es particularmente interesante en el caso de laboratorios ubicados en países con restricciones para el ingreso de instrumental o repuestos, pero también para el caso de necesidades muy específicas que generan poco interés en los grandes fabricantes y por lo tanto acarrean grandes costos y demoras en su provisión.

>**Box 6: Bomba de jeringa open source (OSSP)**
>
>Un equipo de laboratorio de la Universidad Tecnológica de Michigan, liderado por el investigador Joshua Pearce, publicó una librería de diseños open source que permite a los científicos producir su propio instrumental de laboratorio. Comenzaron publicando los diseños de una bomba de jeringa, instrumento utilizado frecuentemente en la mayoría de los laboratorios para aplicar dosis controladas de líquidos, ya sea drogas o reactivos.
>
>El objetivo es que cualquier científico pueda reproducir los diseños y generar un ahorro a partir de la fabricación 3D con RepRap -autorreplicable-. Además, los planos son customizables realizando pequeños cambios en el software: "No sólo diseñamos una bomba de jeringa… Diseñamos todas las futuras" afirmó Pearce.
>
>La librería fue diseñada utilizando software open source, y puede ser replicada mayoritariamente utilizando una impresora 3D RepRap y materiales accesibles como arandelas. Los investigadores realizaron pruebas de performance, en las cuales la OSSP resultó ser consistente con la calidad de las bombas de jeringa comerciales. En total, el costo del desarrollo fue de 50 dólares, pudiendo reemplazar productos comerciales que cuestan entre 250 y 2500 dólares.
>
><img src="http://www.appropedia.org/images/0/08/Double-pump.jpg" width=70%>    
>_Fig. 10. Una bomba de jeringa OS doble que cuesta 120 USD versus la versión comercial, de 5000 USD (Fuente: Appropedia)_
>
>Para este caso se realizó una valoración económica, obteniendo un valor de retorno de la inversión fluctuante entre $168,000 to $2.5 millones, para concluir que este método es sencillo y provee información para tomar decisiones. Resulta específicamente atractivo para organizaciones interesadas en maximizar el retorno de las inversiones públicas en tecnologías asociadas a la ciencia, medicina o educación.

Dado el reciente origen de los desarrollos, éstos aún no cuentan con un gran nivel de precisión, aunque se espera que la tendencia sea hacia un mayor perfeccionamiento. El hecho de que el personal de laboratorio se involucre en el desarrollo de los instrumentos trae aparejada una mayor comprensión de las condiciones en las que se generan los datos, mejorando la interpretación que se hace de los mismos.

En algunos casos, científicos de laboratorios tradicionales se han acercado a hackspaces y makerspaces, espacios de innovación ciudadana, conectando con actores fuera del ámbito académico que pueden enriquecer tanto las propuestas de desarrollo como la agenda de investigación. La creación de herramientas basadas en OHW es una forma de conectar el mundo académico con el resto de la sociedad: algunos proyectos lo utilizan para llamar la atención de los estudiantes hacia las carreras científicas.

Uno de los principales obstáculos en este ámbito es que el esquema de incentivos profesional aún no valora el trabajo de creación de herramientas por parte del investigador. Generalmente los usos de los potenciales desarrollos de instrumental son tan específicos que el tamaño de la comunidad de colaboración no resulta significativo. Esto hace que en la práctica, en la mayoría de los casos el proceso de desarrollo recaiga principalmente en una o dos personas, volviéndose lento y demandando mucha energía por parte del científico. Al no estar formalmente categorizado dentro de los sistemas de valoración profesional, el tiempo dedicado a estas actividades no puede ser capitalizado, por lo cual la motivación para diseñar y construir OHW se ve reducida. Una de las opciones que se vislumbran para contrarrestar el problema es la aparición de revistas científicas especializadas para la publicación de diseños OHW, lo que permitiría visualizar el trabajo realizado por los científicos-inventores y medir su impacto en la comunidad.

- biología sintética
- óptica, microscopios
- microfluídica
- física (CERN y otros)
- nanotecnología
- muestreos ambientales/biológicos
- química

### Ciencia comunitaria

- monitoreos ambientales comunitarios
- biohacking
- drones

### Medicina

### Agricultura

### Educación

- educación STEM
- introducción a la electrónica para alumnos de diseño y otros

Dentro del ámbito de la educación, el principal impacto se ve en la enseñanza de contenidos técnicos a través de los talleres de robótica. La robótica presenta una doble ventaja como herramienta en la educación técnica: por un lado combina un componente de interés y fascinación por parte de los estudiantes -materializado en múltiples concursos a escala global- y a la vez requiere el desarrollo de múltiples habilidades: mecánica, electrónica, gestión energía, ciencias de la computación, entre otras. Para orientar estos cursos en ciertos colegios o universidades se utilizan herramientas de programación de bajo nivel como lenguaje ensamblador, o nivel medio como lenguaje C. Sin embargo la sintaxis o estructura de estos lenguajes se convierte en algún momento en barreras que desmotivan a los estudiantes:, si le sumamos la parte electrónica, el montaje y el diseño, muchas veces se vuelve un motivo de frustración.

La principal ventaja del OH en este campo es el aumento de la velocidad de iteración, es decir la posibilidad de experimentar a un bajo costo, y la creatividad que se puede desarrollar a partir de la utilización de sistemas flexibles, como Arduino. Un punto no menor consiste en que al contar con el diseño completamente abierto, los estudiantes acceden a experimentar con los desarrollos en todos los niveles y los docentes encuentran más fácil la tarea de dar soporte y mantenimiento.

Algunos autores resaltan la utilidad de los desarrollos para que los estudiantes puedan pasar de la filosofía del saber al hacer, en un ambiente de estudio propicio para nuevas posibilidades de expresión, antes vedadas por el elevado costo de los materiales. Existen múltiples experiencias de estudiantes y talleres en escuelas donde se evidencia la sencillez y mayor velocidad en los procesos de aprendizaje cuando se utilizan diseños basados en OSHW.

Además de la adquisición de habilidades técnicas y el fomento de la creatividad, los estudiantes se benefician a partir del trabajo colaborativo y multidisciplinario que implica trabajar en el desarrollo de un artefacto basado en OSHW.

> **Box 7: Minipiano - Haciendo música con Arduino**
>
>En este experimento, Bordignon e Iglesias enseñan a los estudiantes, a través de la construcción de un piano de tres teclas, a trabajar con luces led, botones y con un buzzer para entender cómo se leen los datos y cómo utilizarlos en los programas que se realizarán en Arduino.
>  
>A medida que el desarrollo del juguete va requiriendo mayores capacidades, las instrucciones van entrando en mayor detalle: valores de verdad y condiciones lógicas, sentencias de programación específicas, etc.
>
><img src=https://i.ytimg.com/vi/bHOqsk8TnGY/maxresdefault.jpg width=70%>    
>_Fig. 11. En la plataforma YouTube se pueden encontrar distintas versiones del proyecto de minipiano en Arduino (Fuente: YouTube)_

Otra rama de la educación donde comienza a evidenciarse el potencial del OSHW, cercano a la robótica, es en el diseño de sistemas embebidos. Un sistema embebido es una combinación de hardware y software que trabaja junto con algún sistema mecánico o electrónico diseñado para cumplir una función específica. Por lo tanto, se usa para dotar de "inteligencia" a un artefacto, por ejemplo electrodomésticos. Miles de millones de microprocesadores se fabrican por año en el mundo, sin embargo 99% de ellos permanece invisible para los consumidores, siendo su destino los sistemas embebidos.

En este ámbito se puede observar una motivación cercana al movimiento *maker*, relacionada a la corriente del aprendizaje construccionista y su leitmotiv de "aprender haciendo", basada en las ideas de John Dewey, Maria Montessori, y Jean Piaget. Los educadores que adhieren a esta orientación plantean que enseñar en la práctica el uso del hardware y su intervención permite tener una perspectiva más amplia sobre el funcionamiento de las tecnologías digitales y deja de lado la visión de los objetos cotidianos como cajas negras cerradas y mágicas para pasar a percibirlos como resultado de un diseño premeditado. Además, hacen hincapié en la valoración del error como método de aprendizaje, generando un espacio seguro donde los estudiantes pueden tomar información a partir de experimentos fallidos.

En el ámbito local es importante mencionar el trabajo de Bordignon e Iglesias, donde proponen una serie de experimentos basados en Arduino para aplicar en clase. Trabajando con sistemas embebidos, detallan la información necesaria para que en distintos niveles del ciclo educativo los estudiantes puedan desarrollar desde un semáforo o un termómetro hasta juegos con electrónica de mayor complejidad (ver Box 7).

### Productos de consumo
- wearables
- DIY hedonista

### Arte

- audiovisuales
- sonido
- performance

### Activismo 
- transhackfeminismo 
- redes libres

## ¿Cómo se hace hardware abierto?

### Herramientas de fabricación digital 

Como se mencionaba en la sección '¿Por qué ahora?', el desarrollo y difusión de herramientas de fabricación digital tuvo un impacto directo en el surgimiento de proyectos de hardware abierto (Söderberg, 2013).
Muchas de las herramientas tecnológicas que conforman la práctica de la fabricación digital no son particularmente nuevas; lo novedoso en la actualidad son las reducciones de los costos y escala de las tecnologías y un aumento de la versatilidad en el proceso de fabricación (Fressoli y Smith, 2015).

En términos de acceso, los usuarios pueden disponer indivualmente de las herramientas o acudir a espacios comunitarios donde abonan una tarifa por tiempo de uso (o usan sin costo) las herramientas disponibles (de Brujin, 2010; Mellis, 2014).
Los espacios comunitarios permiten acceder a herramientas más complejas y costosas, y ofrecen oportunidades para el aprendizaje y el intercambio.
También existe la posibilidad de contratar una variedad de servicios de fabricación digital a distancia, lo que incrementa tanto la velocidad como el costo del proceso pero disminuye el control del usuario sobre el mismo y la posibilidad de iteración.

En esta sección se detallan las principales herramientas de fabricación digital disponibles y sus principales usos. 
Además de las mencionadas existen una variedad de otras herramientas específicas desarrolladas por los usuarios. 

#### Impresión 3D
Uno de los disparadores del crecimiento de la impresión 3D fue la expiración de las patentes de los equipos creados en la década de los ochenta.
A modo de ejemplo, en 2009 expiró la patente del proceso de modelado por deposición fundida (conocido como FMD por su sigla en inglés) que utiliza filamentos plásticos, ocasionando una explosión de experimentación en el rubro (Fressoli y Smith, 2015).

El proyecto RepRap (nombre corto de 'Replicating rapid prototyper'), iniciado por Adrian Bowyer en la Universidad de Bath (Reino Unido), es uno de los casos paradigmáticos dentro de la impresión 3D.
Su objetivo original era desarrollar una herramienta de fabricación de bajo costo capaz de producir una copia de sí misma, basada en archivos digitales de diseño (de Brujin, 2010).
Utilizando procesos aditivos de fabricación, la RepRap se comercializa a menos de 500 euros, garantizando el acceso a una gran cantidad de usuarios.

Diferentes modelos de impresoras 3D pueden utilizarse con diversos materiales, resoluciones y tolerancias; ampliando el espectro de estabilidad, propiedades ópticas, apariencia, acabado y demás propiedades (Mellis, 2014).
Las especificaciones de diseño, geometría, materiales y resistencias se distribuyen fácilmente en archivos digitales editables con FOSS especializado (Blender, OpenSCAD), lo que facilita la colaboración dentro de las comunidades.

#### Cortadoras láser, tornos CNC y otros
Las cortadoras láser y los tornos CNC (control numérico) son otro ejemplo de herramientas ampliamente difundidas en fablabs o makerspaces. 
Las primeras permiten calar, cortar o grabar materiales como maderas balsas, cartón, acrílico y otros; existen variedades que cortan vinílico y otras basadas en chorro de agua para cortar materiales más densos.
En el caso de los tornos CNC, su utilización permite la remoción controlada de materiales con alta precisión a partir de bloques sólidos.

Estas herramientas trabajan con una variedad mayor de materiales respecto de la impresión 3D, pero son más limitadas en términos de las geometrías que pueden producir, e involucran un proceso más largo de fabricación, ensamblado y acabado. 
Nuevamente las especificaciones geométricas, de material y ensamblado son fácilmente distribuidas en archivos digitales, aunque requieren de ajustes particulares adaptados a cada máquina. 

Para materiales textiles existen también herramientas de control numérico que emulan el proceso de bordado o del telar, otros dispositivos como brazos robóticos y partes adaptables son cada vez más comúnmente desarrolladas por los usuarios (Mellis, 2014).

#### Circuitos impresos y electrónica
Mellis (2014) considera la producción de circuitos impresos como un proceso de fabricación digital.
A partir de los diseños digitales se producen placas mediante procesos afotográficos sobre materiales como cobre, a la que se suma una capa aislante y otra con texto y anotaciones.
El proceso puede realizarse con máquinas CNC en espacios comunitarios o mediante servicios que ofrecen la fabricación a usuarios individuales partir del diseño digital.

Uno de los principales obstáculos identificados a la hora de replicar diseños electrónicos es encontrar los componentes electrónicos necesarios (GOSH, 2018). 
La alta especificidad de algunos diseños hace que sea muy complejo encontrarlos, sumado a que en algunos países existen limitaciones de importación.
El ensamblado además requiere de cierta habilidad manual para la soldadura y resolución de problemas. 

### Diseño y fabricación: de la idea al prototipo, del prototipo al producto
Los pasos necesarios para construir hardware electrónico han ido mutando a partir de la disponibilidad de herramientas de fabricación digital y FOSS que permite emular etapas de diseño y testeo.
Sin embargo aún se precisa contar con ciertos conocimientos y herramientas específicos en términos de electrónica o programación.

La mayoría de los proyectos comienzan con una idea prototipada rápidamente como prueba de concepto.
Para ello suelen utilizarse protoboards, básicamente cajas de plástico con orificios conectados entre sí que permiten crear un circuito sin necesidad de soldar cables o componentes.
En este punto el diseño no es perfecto, sólo sirve para comprobar que funciona y determinar qué componentes son necesarios.

![protoboard](https://en.wikipedia.org/wiki/Breadboard#/media/File:Breadboard.JPG)

En la actualidad todos los objetos electrónicos se fabrican utilizando plaquetas de circuito impreso (PCB), a diferencia del sistema de cableado punto a punto utilizado hasta los años 60. 
Hasta el advenimiento de las herramientas digitales se requería cierta habilidad "artística" del fabricante: se utilizaba una “máscara” de cinta negra sobre una placa de acetato para indicar la ruta de conexiones más eficiente a fin de transformar el diagrama en una plaqueta. 
Los circuitos impresos aportaron un nivel mucho mayor de automatización en la fabricación: se eliminó el cableado, ya que las conexiones, constituidas por líneas de cobre, se encuentran integradas en un soporte no conductor -generalmente epoxy- que además sostiene los componentes.
Estas innovaciones permitieron no sólo reducir el espacio que ocupa el circuito sino también integrar el uso de microchips, el corazón de las tecnologías como teléfonos móviles, computadoras, tablets y más.

<br>
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/67/PCB_design_and_realisation_smt_and_through_hole.png/1024px-PCB_design_and_realisation_smt_and_through_hole.png" width=80%>    
*Fig 4: ejemplo de diseño digital de circuito impreso (izq.) y circuito final (der.) (Fuente: Wikipedia)*

Actualmente, una vez que se obtiene una prueba de concepto el próximo paso consiste en trasladar el diseño a su versión digital, que servirá para producir el circuito integrado o PCB.
Esta 'versión digital' consta de dos partes: un diagrama esquemático ('schematic') y un diagrama de diseño ('layout'). 

El diagrama esquemático es un gráfico donde se especifican los componentes electrónicos (resistencias, capacitores, circuitos integrados) a utilizar y sus conexiones, a través de un sistema de símbolos. 
En caso de ser necesario también se indica información sobre valores de cada componente (por ejemplo una resistencia de 10-kilohm). 

Sin embargo el esquemático no posee toda la información necesaria para fabricar una plaqueta de circuito impreso, por lo cual se debe armar el diagrama de diseño, que especifica la disposición del circuito en la placa.
Tanto el esquemático como el layout se obtienen mediante FOSS especializado, como Fritzing o KiCad.

![esquemático](https://circuitdigest.com/sites/default/files/circuitdiagram_mic/12v-battery-charger-circuit-with-variable-voltage.gif)
*Fig. 3: Ejemplo de diagrama esquemático para un cargador de batería DIY (Fuente: Circuit Digest)*

![layout](https://circuitdigest.com/sites/default/files/inlineimages/12v-battery-charger-circuit-PCB-layout-Kicad.gif)
*Fig. 3: Ejemplo de PCB layout para un cargador de batería DIY (Fuente: Circuit Digest)*

Los dos productos de la etapa anterior son luego transformados en archivos vectoriales denominados 'Gerber' que pueden ser leídos por un fabricante, donde se detallan tamaño de componentes, forma y conexiones y se diseña la configuración física final del circuito. 
Es un proceso orientado gráficamente, en el cual el diseñador ubica los componentes y las conexiones de la forma más eficiente posible -el software propone el arreglo más conveniente aunque siempre requiere retoques por parte del diseñador-. 
Dado un set Gerber, el fabricante puede crear una o 100 mil copias de un circuito.

```
G04 Short version a file taken from the Example Job 1, created by Filip Vermeire, Ucamco*
%TF.FileFunction,Copper,Bot,L4*%    
%TF.Part,Single*%    
%FSLAX35Y35*%    
%MOMM*%    
%TA.AperFunction,Conductor*%    
%ADD10C,0.15000*%    
%TA.AperFunction,ViaPad*%
%ADD11C,0.75000*%
%TA.AperFunction,ComponentPad*%
%ADD12C,1.60000*%
%ADD13C,1.70000*%
%SRX1Y1I0.00000J0.00000*%
G01*
G75*
%LPD*%
D10*
X7664999Y3689998D02*
X8394995D01*
X8439999Y3734999D01*
X9369999D01*
D11*
X7664999Y3689998D03*
X8359999Y1874998D03*
X9882998Y3650498D03*
D12*
X4602988Y7841488D03*
D13*
X10729976Y2062988D03*
X10983976D03*
X11237976D03*
M02*
```    
_Fig 5: ejemplo de archivo en formato Gerber, para ser leído por el fabricante (Fuente: Wikipedia)_

En cuanto a las dificultades que se identifican en los procesos de desarrollo, principalmente son aquellas relacionadas a la dificultad de conseguir componentes -que no se encuentran disponibles en todos los países-, la necesidad de estandarización en el uso tanto de plataformas electrónicas como de software de diseño, que permita a los grupos interactuar de forma sencilla -en este sentido todos los autores remarcan la importancia de Arduino-, y en menor medida la dificultad para documentar y trackear los cambios entre versiones -para lo cual existen iniciativas de documentación por parte de distintas organizaciones-.

Los pasos descritos aplican al desarrollo de una plaqueta electrónica (PCB), presente en casi todos los artefactos que usamos a diario. 
Sin embargo, crear un artefacto requiere de otras instancias adicionales de desarrollo, como el diseño final del objeto, elección de los materiales, mecánica de las partes, programación del software, etc. 

#### Buenas prácticas

Aunque la barrera de acceso a la fabricación de hardware es menor en la actualidad, autores como Wozniak (2014) y Oberloier (2017) consideran que las buenas prácticas de diseño son fundamentales para asegurar la accesibilidad y replicabilidad de los desarrollos. 

Wozniak (2014) propone un modelo de diseño de producto para hardware al que denomina 'cascada'. 
En el mismo se detallan etapas de definición de especificaciones, diseño, prototipado y testeo; el proceso es necesariamente iterativo pero requiere de avances secuenciales. .

![waterfall model of product development](../notas_bibliografia/wozniak.png)

Todas las recomenciones (Buechley, ; Malinen, ; Mellis, 2014) coinciden en que otro aspecto clave a la hora de facilitar el proceso de desarrollo de hardware libre es la **modularidad**.
Oberloier detalla aún más este y otros requisitos en sus procedimiento general para el diseño de hardware científico abierto (2017).

Las guías incluyen no sólo recomendaciones para el diseño si no para la documentación y colaboración, bajo cinco preceptos:

1. Hacer una revisión de la literatura para basarse en diseños pre-existentes, y si no es posible realizar una prueba de concepto simple
    - Este paso asegura que no se 'reinventa la rueda' y se contribuye al pool de conocimientos existente. 
2. Diseñar teniendo en cuenta:
    - Utilización de FOSS para garantizar replicabilidad
    - Minimizar el tipo de partes y complejidad para asegurar reparabilidad, actualización y mantenimiento
    - Minimizar el volumen de material y costo de producción para disminuir el impacto ambiental, costos económicos y tiempo de desarrollo
    - Utilizar componentes ampliamente disponibles en el mercado cuando no se trate de piezas personalizadas, para facilitar replicabilidad
3. Validar el diseño a través de un proceso de calibración de bajo costo y transparente.
4. Documentar el diseño, fabricación, ensamblado, calibración y operación en detalle, orientado a un no especialista, siguiendo las guías de OSHWA.
5. Compartir la documentación en repositorios open source específicos (Open Science Framework, Github, 3DPrint Exchange, Open Circuit Institute)


### Documentación y grados de apertura **FALTA**

One of the challenges they face is that sharing knowledge about atoms is not as frictionless as sharing bits; hardware needs to  be  described  through  more  complex  constructs  like  2D  or  3D schematics, which may require more specific software to  be  edited  and  displayed  (Bonvoisin, 2017). 
Hardware components are generally less documented than software (), which makes some authors (Bonvoisin, 2017) raise questions around the degrees of openness in open source hardware projects.


Journal of Open Hardware
HardwareX
OSF
Docubricks

Bonvoisin, J., Buchert, T., Preidel, M., & Stark, R. G. (2018). How participative is open source hardware? Insights from online repository mining. Design Science, 4. https://doi.org/10.1017/dsj.2018.15

Bonvoisin, J., & Mies, R. (2018). Measuring Openness in Open Source Hardware with the Open-o-Meter. Procedia CIRP, 78, 388–393. https://doi.org/10.1016/j.procir.2018.08.306



### Comunidad y colaboración **FALTA**

Cruz, A. H. M. (n.d.). Exploring the Open Source Hardware phenomenon: Empirical essays on the role of user communities in the creation of innovation, organizations and markets. 165.

Hallgren, J., & Wiberg, W. (n.d.). Open Source Hardware – A case study of user developed derivatives. 47.

Kyriakou, H., & Nickerson, J. V. (2014). Collective Innovation in Open Source Hardware. SSRN Electronic Journal. https://doi.org/10.2139/ssrn.2421332

Mellis L., D. . B. (2012). Collaboration in Open-Source Hardware: Third-Party Variations on the Arduino Duemilanove.

Mies, R., Bonvoisin, J., & Jochem, R. (2018). Harnessing the Synergy Potential of Open Source Hardware Communities. In Co-creation: reshaping business and society in the era of bottom-up economics. New York, NY: Springer Berlin Heidelberg.

Morreale, F., Moro, G., Chamberlain, A., Benford, S., & McPherson, A. P. (2017). Building a Maker Community Around an Open Hardware Platform. Proceedings of the 2017 CHI Conference on Human Factors in Computing Systems  - CHI ’17, 6948–6959. https://
doi.org/10.1145/3025453.3026056

Tech, R. P. G., Ferdinand, J.-P., & Dopfer, M. (2016). Open Source Hardware Startups and Their Communities. In The decentralized and networked future of value creation (pp. 129–145). New York, NY: Springer Berlin Heidelberg.

Wozniak. (2014). The Design Process: How to Get from Nothing to Something. In Building Open Source Hardware: DIY Manufacturing for Hackers and Makers.


Una de las principales cuestiones que la literatura analiza es la diferencia entre el proceso de desarrollo del software y el de hardware.
Mientras la virtualidad del software facilita la colaboración sin mediar distancias en un proceso bastante directo entre usuarios, la materialidad inherente al desarrollo de hardware implica que éste requiera de instancias discretas y potencialmente independientes de trabajo. 
Como se ve en algunos estudios de caso, esto determina cuellos de botella particulares, asociados principalmente al multi-expertise requerido para modificar un objeto y a la existencia de patentes en los objetos físicos. 
Al respecto, algunas organizaciones han comenzado a documentar protocolos de desarrollo de OSH, a manera de guías de buenas prácticas (Oberloier y Pearce, 2017) o describiendo procesos exitosos (Ackermann, 2009).

A diferencia del proceso colaborativo que da origen al software libre, en el caso del hardware la multiplicidad de conocimientos requeridos para comenzar a trabajar impone ciertas restricciones: salvo contadas excepciones, se requiere de trabajo en grupo donde actores de diversa formación aporten sus conocimientos.

Algunos autores enfatizan que uno de los criterios para que un desarrollo de hardware sea exitoso es que la comunidad de colaboradores sea lo suficientemente grande para asegurar un mínimo de aportes diversos.  
Sin embargo, Buechley remarca que este proceso de colaboración se da de manera más descentralizada en hardware que en software, observándose mucho más frecuentemente múltiples iniciativas de pequeña escala, con una dinámica más "privada" de la colaboración, sobre grandes iniciativas a partir de comunidades numerosas. 
El carácter privado de la colaboración también es observado por Malinen en el caso del desarrollo del eCar finés: a la hora de construir hardware, es más común que la colaboración exitosa se pueda dar en pequeños grupos que al menos una vez se encuentran físicamente en lugares de trabajo.

### Licencias para hardware

El objetivo de contar con licencias para hardware es asegurar tanto la libre circulación de ideas como la atribución a los autores.
Una de las distinciones fundamentales que diferencian al hardware de FOSS es que el copyright aplica a los esquemáticos y los diseños, pero no al producto tangible, donde aplican patentes y marcas registradas.
Pearce (2018) asocia el crecimiento de los repositorios online en los últimos años (como Github, Thingiverse, Libre3D y muchos otros) a que el uso de copyright no es la estrategia apropiada para esquemáticos y diseños de productos tangibles, resultando sencillo realizar una pequeña modificación de un diseño protegido evitando sanciones (Bradshaw et al., 2010).

Existen antecedentes de encuestas a la comunidad de hardware abierto que incluyen preguntas sobre licencias, pero los datos están desactualizados (OSHWA 2012, 2013) o las metodologías no son consistentes (Black Duck).
Katz (2012) hizo una revisión de las licencias existentes para hardware hasta el momento, destacando la licencia TAPR y la licencia CERN OHL.
Tanto TAPR como CERN OHL siguen la lógica copyleft, para asegurar que tal como en FOSS el hardware se distribuya garantizando disponibilidad de la documentación de base y asegurando reutilización, adopción y redistribución con las mismas reglas.
Katz (2012) critica este rasgo y propone adaptar la licencia Apache 2.0, ampliamente utilizada en FOSS; esta propuesta se transformaría en la licencia Solderpad.

En 2019 Katz realiza una encuesta orientada a productores de procesadores abiertos pero que brinda información útil sobre la comunidad y el uso de licencias.
Según este último estudio, alrededor de 500 proyectos utilizan la licencia CERN-OHL en GitHub, 434 utilizan Solderpad y sólo 15 utilizan TAPR OHL en la misma plataforma.
La mayoría de los entrevistados prefiere licencias más permisivas como Solderpad, ya que dejan menos elementos bajo incertidumbre y resulta más difícil interactuar con modelos propietarios que no desean ser incluidos bajo copyleft, además de traer problemas con agencias de financiamiento.
Todos coinciden sin embargo en que la adopción de copyleft o no-copyleft finalmente es ideológica, con proyectos que no ven problemas en utilizar licencias permisivas con el riesgo de ser integrados en proyectos propietarios; y otros que privilegian la libre redistribución.

![licencias para hardware](../notas_bibliografia/katz2018.png)

El mismo estudio sugiere que los proyectos de hardware abierto deberían incorporar alguna de las licencias más populares dependiendo de los objetivos del mismo; utilizar licencias menos populares puede causar problemas de incompatibilidad y de adopción por otros del proyecto.
Las sugerencias apuntan a si el proyecto busca maximizar reutilización o libertades - sugiriendo Solderpad en el primer caso y CERN OHL en el segundo.
En el primer caso el portador de la licencia puede verse en la situación de que su diseño sea incorporado a sistemas propietarios y el diseño resultante no sea puesto a disponibilidad.

Por otro lado, como se mencionaba al inicio el concepto de hardware implica mucho más que artefactos electrónicos. 
Uno de los casos que es útil para ilustrar esto en la licencia OpenMTA, orientada a regular la transferencia de materiales biológicos como ser plásmidos, muestras y otros cuyas cantidades no son intrínsecamente limitadas.
Open MTA fue presentado en 2018 por un colectivo de investigadores, profesionales de transferencia de tecnología y expertos legales entre otros, en una nota en la revista Nature (Kahl et al, 2018).


1. [TAPR license](https://www.tapr.org/ohl.html)    

La Tucson Amateur Packet Radio Corporation es una organización internacional sin fines de lucro fundada en 1982 en Estados Unidos, que reúne radioaficionados y promueve actividades de investigación, educación, publicaciones, reuniones y estándares en la comunidad. 
Una de sus actividades es la de provisión de kits para que hobbistas puedan armar sus propios sistemas y soporte para que puedan concretar sus diseños en productos.

Según OSHWA en su [breve historia del hardware abierto](https://www.oshwa.org/research/brief-history-of-open-%20source-hardware-organizations-and-definitions/), en 2005 en una de estas colaboraciones con un grupo desarrollando software para radioaficionados (Tucson Amateur Packet RadioSystem) se planteó la necesidad de contar con un mecanismo que impidiera la apropiación por privados del desarrollo.
Fue escrita por John Ackermann, un abogado y radioaficionado, y publicada en 2007 con el expreso fin de aplicar el mecanismo copyleft a dispositivos físicos.

Se convirtió así en la primer licencia abierta para hardware, bajo forma de contrato a diferencia de GPL que se plantea como términos y condiciones.
Requiere que la documentación de diseño (archivos CAD, esquemáticos, planos mecánicos) esté disponible para cualquier usuario del dispositivo, incluyendo modificaciones.
El software que acompaña el dispositivo (incluyendo firmware) no está cubierto por la licencia, que delega esta función en licencias de software que se consideren apropiadas.

2. [CERN open hardware license](https://www.ohwr.org/projects/cernohl)

La Colaboración Europea para la Investigación Nuclear (CERN) fue una de las pioneras en el área al lanzar el repositorio de hardware abierto en 2009. 
Éste surgió a partir de la colaboración entre CERN y la industria aldededor del proyecto White Rabbit, un dispositivo para sincronización de nodos en un radio de 10 km con precisión de sub-nanosegundos.
Javier Serrano, líder del equipo de hardware para sincronización en CERN, decidió aplicar la metodología de colaboración y trabajo abierto que veía en los equipos de software a su propio equipo.

En 2011 a partir de la colaboración entre Javier y el equipo de Knowledge Transfer en CERN se publica la primera versión de la CERN Open Hardware License (CERN OHL).
Según Ayass (2012), abogada que colaboró en la redacción de la licencia, el objetivo era 'definir las reglas bajo las cuales se comparten y distribuyen los diseños en el Open Hardware Repository, y establecer un marco legal para las contribuciones de CERN al repositorio'.
Originalmente pensada para uso interno de CERN, la licencia está disponible y es utilizada por numerosos proyectos de hardware abierto. 

La licencia está diseñada para ser compatible con la definición de apertura de OSHWA.
Dos características son relevantes: por un lado es una licencia copyleft, aunque los autores consideran que existe flexibilidad en caso de que las compañías requieran esquemas diferentes como dual licensing (Ayass, 2012).
Por otro lado es importante para CERN demostrar su contribución a la sociedad y por ende hacer un seguimiento de quiénes utilizan la licencia; sugieren por lo tanto notificar al iniciador del proyecto cuando se utiliza y exigen mantener la notificación sobre la licencia en la documentación con fines de acreditación.

Al igual que TAPR, CERN OHL sólo se aplica a hardware: el software que acompaña el dispositivo (incluyendo firmware) no está cubierto por la licencia.
La actual versión, CERN OHL 1.2 está en proceso colaborativo de revisión a una versión 2 que aparecería con variantes más permisivas (similar a Solderpad) sumadas a la actual de copyleft (Katz, 2019).cence
 
3. [Solderpad](http://solderpad.org/licenses/)

Como se mencionaba anteriormente, la licencia Solderpad surge a partir de una crítica a la rigidez del copyleft para el caso de hardware, realizada por Andrew Katz (2012).
Katz hace hincapié en que este mecanismo conduce a una menor adopción del hardware abierto, haciendo su evolución más lenta y disminuyendo el tamaño del ecosistema de innovación.
El autor toma la licencia de software abierto Apache 2.0, ampliamente reconocida y comprendida por la comunidad, y la adapta a los usos del hardware.

La principal modificación radica en extender los derechos de Apache asociados a copyright, patentes y marcas registradas hacia derechos sobre bases de datos, diseños y topografía de semiconductores.
El aporte de esta licencia radica en ser una alternativa no copyleft, es decir no obliga al usuario a utilizar la misma licencia en los derivados.
La versión vigente es la 2.0, en revisión por cambios menores.

4. [OpenMTA](https://biobricks.org/openmta)

Los Acuerdos de Transferencia de Materiales (MTAs) establecen los marcos legales para compartir biomateriales, con el objetivo de promover el intercambio, innovación y traducción en tecnologías.
El MTA más frecuentemente utilizado en la actualidad, el [Acuerdo Uniforme de Transferencia de Materiales Biológicos (UBMTA)](https://www.ott.nih.gov/resources/) fue desarrollado en 1990 antes de la masificación de internet, la secuenciación de genoma y la biología sintética, lo que dificulta el trabajo en la actualidad.
Dos de las restricciones más importantes de la UBMTA son la prohibición de redistribución y del uso comercial. 

A modo de propuesta OpenMTA se desarrolló colaborativamente impulsado por la fundación BioBricks y el centro de investigación en biología sintética OpenPlant.
Tiene cinco objetivos principales, alineados a la Definición de Apertura: acceso, atribución, reuso, redistribución y no discriminación. 

Como todos los MTAs se trata de un contrato en el cual el proveedor entrega materiales a cambio de la promesa de atribución, reporte y pago de tasas de procesamiento de material.
A diferencia de los actuales, OpenMTA permite el reuso de materiales dentro de los marcos legales y la redistribución con reporte al proveedor.
Las instituciones firmantes no tienen obligación de manejarse 100% con OpenMTA, ni de aplicarlo a derivados. 

OpenMTA se encuentra disponible en el sitio de BioBricks y se planea sumar adhesiones para incorporarlo a otras plataformas de intercambio de materiales biológicos. 
La aplicación a materiales humanos no está contemplada en esta versión, pero numerosas peticiones hicieron que se inicie un proceso de discusión colaborativa para elaborar una propuesta.


## Modelos de negocio para hardware abierto

Autores como Bauwens (2011) y Söderberg (2011) asocian al hardware abierto con la producción distribuida y sus beneficios (fabricación local, menores costos de distribución y transporte, comunidades de innovación, mayor participación).
La aparición y crecimiento de los proyectos basados en hardware abierto, particularmente el caso de Arduino y otras firmas como Sparkfun y Adafruit, desafían la lógica de los modelos de negocio tradicionales. 

Según un informe sobre el estado de situación del rubro, analizando 100 start-ups de hardware abierto (Berchon, 2013), la mayoría se encuentran en los Estados Unidos (68%) -concentradas en los núcleos de desarrollo de hardware alrededor de las universidades y hackerspaces activos- seguido por Europa (19%) y Asia (7%). 
El mayor crecimiento se da en el año 2007: hasta ese entonces se lanzaba sólo una compañía OHW por año: ejemplos de ello son Parallax (1986), Solarbotics (1994), Lynxmotion (1995, luego comprada por RobotShop), ShopBot (1996), Egnite (1997), WIZnet (1998). 

Gran parte de las compañías basadas en OHW trabajaban en 2013 en el rubro de electrónica para hobbistas y educación (63%); muchas de ellas inspiradas por el éxito de modelos como Arduino o Raspberry Pi, desarrollando kits y placas compatibles. 
La segunda posición es para las herramientas de fabricación (15%), más específicamente impresión 3D (11%). El resto del mercado se encuentra fragmentado en nichos específicos: drones (3%), iluminacion (3%), sintetizadores de sonido (2%).

En cuanto al perfil de los emprendedores, mayoritariamente poseen una formación en ingeniería (83%), diseño (17%) -incluyendo artistas digitales con conocimientos en aspectos técnicos- y docentes e investigadores (14%) provenientes de áreas técnicas, que dedican su tiempo libre a trabajar en proyectos OHW. 
El 47% de las compañías es liderado por emprendedores solos, comparado con el 52% que lo hace en equipo, lo que la autora atribuye a la ventaja de contar con una comunidad online fuerte de apoyo. 
Sólo el 5% de las compañías son lideradas por mujeres -con excepciones notables como Adafruit o LittleBits-, y sólo 10% las incluyen en los equipos fundadores, aunque sí participan en gran medida en hackerspaces, proyectos y eventos.

![evolución de start-ups de hardware](http://makingsociety.com/wp-content/uploads/2013/09/slide-growth-open-hardware-startups-e1378750427505.png)

Más de la mitad de las compañías se financian con sus propios recursos (62%) aunque cada vez es mayor el número de empresas que se financian parcial o totalmente a partir de crowdfunding (28%).
Cicero (2013) asocia al segmento de consumidores de éste último modelo (prosumidores creativos) a una evolución del mercado do-it-yourself.
Identifica adicionalmente algunas características comunes a los proyectos de hardware financiados vía crowdfunding:

- Modulares (utilizan protocolos comunes e interfaces estandarizadas)
- Orientadas a prosumidores (makers y early adopters)
- Productos de ultra nicho (prestaciones muy específicas) 
- Poco intensivos en R&D
- Enfocados a resolver necesidades existentes

El indudable éxito de las compañías de software de código abierto (FOSS) probaría que los modelos basados en la apertura pueden funcionar.
Sin embargo la extrapolación al rubro del hardware no es directa, ya que según Ticnq (2013):

- El costo marginal de producir una unidad en FOSS en cero, en hardware no dada la necesidad de materiales y espacios
- Las cadenas de suministro en hardware involucran múltiples organizaciones y sets de habilidades a comparación de FOSS
- Los estándares de calidad y seguridad que aplican al hardware no aplican a FOSS

Los sistemas de generación de valor en hardware varían entre iniciativas, en algunos casos aplicando más de un modelo, o modelos mixtos (Moritz, 2013).
Algunos autores los clasifican en primarios (desarrollo de hardware) y secundarios (actividades de soporte, expertise, talleres).

![tipología de modelos de negocio Moritz](../notas_bibliografia/moritz_bm.png)
*Clasificación de modelos de negocio para hardware abierto (Moritz, 2013)*

Tincq (2013) propone una tipología de modelos de negocio para hardware abierto que distingue entre seis tipos:

- Modelo 1: Basados en diseño

El modelo más común, enfocado a diseño e investigación y terciarizando la fabricación.
La organización puede proveer un artefacto ya ensamblado, kits que disminuyen la barrera de acceso a determinados dispositivos (OpenROV), o es parte de un ecosistema de fabricantes que venden productos basados en diseños abiertos (aún no desarrollado, por ejemplo Wikihouse).

Algunas iniciativas utilizan el modelo de licencia dual de FOSS, ofreciendo tanto la licencia abierta como la propietaria en caso de integración a proyectos propietarios.
Otro modelo de este tipo es el que posee un núcleo de producto abierto y ofrece extensiones o versiones propietarias del mismo (Cicero, 2013).

![business canvas Arduino segun Tincq](../notas_bibliografia/tincq_arduinobm.png)
*Modelo de negocio de Arduino (Tincq, 2013)*

- Modelo 2: Basados en fabricación

El principal valor en este caso está asociado a la fabricación y distribución o redistribución de productos OHW a precios accesibles. 
Al nombre de marca y la comunidad se agrega como activo la eficiencia industrial. 

Cicero (2013) agrega a esto que la ventaja de los grandes fabricantes por poseer los medios de producción se ha relativizado ya que el conocimiento, las herramientas y los diseños necesarios se encuentran accesibles a cientos de compañías e individuos; para el autor la capacidad de producción dejó de ser un factor diferencial en sí mismo. 
Por ello remarca que en este modelo, la ventaja reside en la elasticidad y capacidad de innovación de la compañía para generar nuevos productos.

Uno de los riesgos de la libre circulación de información es que los diseños pueden copiarse. 
Una de las estrategias utilizadas para contrarrestarlo es la de innovar a mayor velocidad que las copias: Sparkfun, fabricante de electrónica open source, es un buen ejemplo.
Para cuando los clones de sus placas están en el mercado, Sparkfun ya tiene una nueva versión publicada, ofreciendo una ventaja competitiva a sus clientes.

El etiquetado de productos 'open source' es una opción que fue utilizada en el pasado con malos resultados ya que compañías de diseño cerrado etiquetaban sus productos como open source.
OSHWA desarrolló un programa de certificación open source hardware para revertir este mal uso (Pearce, 2018).

> **Box 10: 3D Robotics - Mediodía y ocaso de los drones**
>
>3D Robotics es una empresa pionera en la creación de vehículos aéreos no tripulados (UAV), comúnmente conocidos como drones. Sus creaciones se basan en componentes de OSH.
>
>Jordi Muñoz -un joven mexicano emigrado a Estados Unidos- y Chris Anderson -editor de la revista WIRED- se conocieron en el foro open source DIY-Drones, comunidad donde comparten sus experiencias algunos aficionados a vehículos aéreos no tripulados. Allí, Jordi compartió con la comunidad su creación de un piloto automático con acelerómetros extraídos de su Nintendo Wii. Después de eso, su popularidad en el foro creció, llamando la atención de Chris Anderson, que le ofreció 500 dólares para seguir experimentando.
>
>En 2009 fundaron 3D Robotics con el objetivo de liderar el mercado de fabricación de drones y UAVS de calidad profesional a precios accesibles. En 2012, Anderson dejó la revista WIRED para ocupar el puesto de CEO junto con Jordi Muñoz, el mismo año que 3D Robotics anunció que cerraría parte de su código, lo cual fue tomado como una "traición" por parte de la comunidad de DIY Drones que se consideraba parte del proyecto (Cuartielles, 2014).
>
><img src="https://3dr.com/wp-content/uploads/2017/03/Solo_r10c-1024x443.jpg" width=70%>         
>_Fig. 16. Solo, el drone estrella de 3D Robotics (Fuente: 3Dr)_
>
>La empresa llegó a tener oficinas en la ciudad de San Diego y Berkeley en California, ventas y marketing en Austin, Texas y una planta de producción en Tijuana, Baja California, México, que producían alrededor de 15,000 pilotos automáticos al año, generando ganancias de alrededor de 20 millones de dólares anuales.
>
>La revista Forbes entrevistó a ex empleados de 3D Robotics que narraron cómo la competencia en precios de la compañía china DJI y los problemas internos impidieron que la empresa cumpliera aquella visión revolucionaria de sus inicios. Ya no producirá sus drones Solo, estrella de la compañía, despidió a más de 150 personas, gastó casi 100 millones de dólares de inversiones y lucha por sobrevivir con un fuerte cambio de modelo de negocio en que ahora se concentra en producir software. Muñoz dejó la empresa para fundar otra llamada mRobotics, también basada en San Diego, una abreviatura de Mayan Robotics.

- Modelo 3: Basados en el conocimiento y el expertise

Este modelo está inspirado directamente en la industria del software libre, su valor radica en el expertise y el servicio de soporte. 
En OHW esto se traduce a talleres de DIY (Tripalium, Open Source Ecology), la venta del producto más la "experiencia" de construirlo (Wikispeed) ó venta de servicios de consultoría para empresas que desean utilizar el producto en su cadena de valor (Arduino, Wikispeed).

<img src=https://i.pinimg.com/originals/85/c9/99/85c999a3b9c1a0541c68c52a217cbb81.png width=70%>    
_Fig 14. Turbina eólica abierta de Tripalium, una fundación que promueve la energía eólica (Fuente: Tripalium.org)_    

Otras compañías ofrecen servicios a usuarios particulares que se encuentran explorando distintos usos de hardware, como IoT (Cicero, 2013).

- Modelo 4: Sistemas de Producto-Servicio (a futuro)

Surgieron en 1959 con el modelo de impresión pay-per-copy instalado por Xerox, y están teniendo mayor difusión actualmente de la mano de conceptos como la economía social y la economía circular. 
Se basan en ofrecer el derecho de uso del producto en lugar de su propiedad, pero en hardware aún es incipiente.

- Modelo 5: Estandarización 

Consiste en abrir estratégicamente un producto clave que sea redituable en sí mismo para que su apertura impulse la creación denuevas tecnologías y lo convierta en un estándar de la industria. 
El ejemplo típico en este caso es el sistema operativo Android, de Google, y los motores Tesla, que permitieron a Tesla Motors incursionar en el mercado de las baterías y estaciones cargadoras.

- Modelo 6: Modelos de plataforma

Su valor radica en organizar un ecosistema de actores industriales (diseñadores, fabricantes, revendedores, consumidores, prosumidores, marcas, etc.) alrededor de una tecnología clave OHW o plataforma. 
Casos paradigmáticos: OpenDesk (ver Box 9) y OSVehicle. 
OSVehicle diseñó el motor y chasis Tabby -OHW, eléctrico y modular-, construyeron una "cadena de valor participativa" donde el mismo se distribuye de manera justa entre todos los participantes.

>**Box 8: Adafruit**
>
>Adafruit Industries es una compañía basada en open source hardware ubicada en la ciudad de Nueva York, fundada en 2005 por la hacker e ingeniera Limor Fried mientras estudiaba en el Massachusetts Institute of Technology. La empresa diseña y fabrica una serie de productos electrónicos y vende un amplio rango de componentes, herramientas y accesorios vía su tienda web. Los productos ofrecidos abarcan rangos de principiante -kits que producen sonidos al recibir una señal- a experto -como sofisticados microcontroladores para celulares y desarrolladores de videojuegos-.
>
><img src=https://www.wired.com/wp-content/uploads/blogs/geekmom/wp-content/uploads/2011/03/Wired-Cover.jpg width=50%>    
>_Fig. 13: Limor Fried, premiada como emprendedora del año en 2012, fue tapa de la revista de tecnología WIRED (Fuente: Wired)_
>
>Todos sus productos son fabricados en la planta del SoHo newyorquino, que cuenta con más de cien empleados. En 2013 entregaron 480 mil pedidos con más de un millón de productos, obteniendo ingresos por 22 millones de dólares. En 2016 registraron su pedido número un millón.
>El nombre Adafruit proviene del nickname "LadyAda" que Fried utilizaba online como homenaje a Ada Lovelace, la pionera en ciencias de la computación. La compañía además produce recursos educativos, incluyendo tutoriales escritos y videos en Youtube con el objetivo de entusiasmar a más personas para que se involucren en el desarrollo de tecnología, especialmente mujeres. En su sitio web oficial Fried declara: “Adafruit es una compañía 100% propiedad de una mujer”.


Pearce (2018) identifica ventajas y limitaciones del hardware abierto en términos de generación de valor y nuevos modelos de negocios.

Entre las ventajas resalta: 

- Reducción de costos asociados a tasas legales (patentes, abogados, juicios, acuerdos) que hacen que por ejemplo Apple o Google inviertan más en esto que en I+D (Covert, 2012)

- Reducción de costos asociados a soporte, dada la contribución de la comunidad en foros y otros eespacios

- Soporte más eficiente, rápido y menos costoso al facilitar la información necesaria para que otras compañías y 3rd parties lo brinden 

- Mejores empleados, como se ve en FOSS ya que sus nombres están asociados a su producción (Lerner and Triole, 2000; Marz, 2010)

Entre las limitaciones:

- El prosumidor debe tener una formación técnica mediana-alta para poder producir a partir de la documentación abierta, lo cual no es una realidad en la mayoría del ámbito científico aún

- Puede impedirse la comercialización aludiendo al cumplimiento de regulaciones de calidad

- Para proyectos más grandes y/o sofisticados la inversión inicial aún es importante y las agencias de financiamiento todavía no apoyan masivamente

- Existe presión real sobre las compañías para adoptar el modelo propietario dados los todavía escasos modelos exitosos

- Fabricar un producto o proyecto no garantiza que se forme una comunidad alrededor del mismo

- Un proyecto exitoso requiere desarrolladores dedicados, promoción y publicidad (Vickery, 2015). 


#### Modelos de negocio para hardware abierto en ciencia

Específicamente en modelos de negocio para hardware científico abierto, el principal aporte es de Pearce (2018), que categoriza los modelos de acuerdo a los usuarios a los que se dirigen dentro del ámbito científico, obteniendo tres tipos principales: makers, consumidores, terciarizadores.

- Tipo 1: grupos que fabrican sus propios equipos utilizando hardware abierto ('makers')
- Tipo 2: grupos que pagarían para que otros fabriquen sus equipos, incluye grupos de investigación en instituciones con altos presupuestos, plazos ajustados o poco personal, o en áreas por fuera de física o ingeniería donde puede resultar más difícil obtener el expertise. 
- Tipo 3: grupos que terciarizan experimentos a laboratorios o compañías especializados

Dentro de estos tres tipos detalla algunos de los que mencionaba anteriormente Tincq.

#### Tipo 1: makers

Estos modelos son análogos al tipo 2 de Tincq, basados en fabricación. 

a) Fabricantes de kits     
Actualmente para desarrollar hardware existen piezas que no pueden ser fabricadas con impresión 3D u otras herramientas, y que resulta más complicado conseguir. 
Esta inversión extra de tiempo abre la oportunidad a que las compañías provean todos estos componentes específicos en forma de kits para un diseño en particular.

b) Proveedores especializados de componentes     
Incluso entre usuarios que desarrollan sus propios productos la especialización es una necesidad, más allá de los kits estándar. 
Las compañías pueden proveer partes especializadas en materiales que comúnmente no están disponibles en el mercado (por ejemplo algunos materiales especiales para impresoras 3D).

c) Servicios de calibración y validación      
Las compañías peuden ofrecer servicios de calibración, validación o testeo de hardware. 
Aunque existen cientos de diseños abiertos, una pequeña parte está formalmente validada y aún menos calibrada.
A medida que este servicio comience a ofrecerse se espera que se produzca un salto en la adopción de hardware científico abierto.

#### Tipo 2: consumidores

a) Vendedores de hardware científico abierto (análogo al modelo 1 de Tincq)     
Se puede vender equipamiento abierto a través de pre-ventas y crowdfunding, en negocios especializados o tiendas onlines.
Un ejemplo de esto es Aleph Objects, una compañía que vende impresoras 3D Lulzbot de diseño abierto, que aunque podrían ser replicadas a partir de los planos, muchos consumidores prefieren comprar hechas.
La comunidad alrededor de su producto hace que Aleph Object tenga menos costos de I+D y más rápido lanzamiento de innovaciones al mercado, gracias a la información que proveen los usuarios (Zimmermann, 2014). 

Otra posibilidad es el “package model” que integra componentes abiertos a líneas de producción existentes; o el “secondary supplier model” (Buitenhuis and Pearce, 2012) que al abrir diseños propios baja el costo de tecnologías que se desarrollan en base a ellos. 
Un ejemplo de esto es la Nitrate Elimination Corporation (NECi), fabricante de enzimas para análisis químicos, que abrió los diseños de su fotómetro bajando el costo de otros métodos para detección de nitratos (Wittbrodt, et al. 2015).
Comercializan el fotómetro y promueven su uso en grupos de ciencia ciudadana y makers para que elaboren sus propios diseños ampliando el mercado.

b) Vendedores de servicios (análogo al modelo 3 de Tincq)     
Análogo a la industria de FOSS, vender expertise de forma tal que se divulgue el producto y se amplíe la base para otros servicios, como el caso de RedHat.

Para el modelo de servicios en ciencia Pearce propone cinco estrategias:

1. Vender suscripciones a un paquete de servicios alrededor de un producto. Particularmente útil para grandes centros de investigación en industria, gobierno o academia donde diferentes productos deberían ser mantenidos.

2. Ofrecer soporte y capacitación en instalación y operación de hardware y guardias para emergencias, reparaciones o actualizaciones. Puede proveer ingresos directos (cursos) o indirectos (publicado en sitios como Instructables que tienen ingresos por publicidad). 

3. Consultoría para realizar versiones más sofisticadas de equipos, aprovechando el expertise en últimas tecnologías disponibles. Puede ser útil en universidades ya que el esquema de trabajo financiado por subsidios es similar al actual.

4. Consorcio de productores para solucionar un problema específico en un campo (Bruns, 2001). Las firmas se benefician por participar en un estudio que no existiría individualmente.

5. Soporte al desarrollo de otras compañías de hardware abierto, como el caso de Seeed Studio. Seeed Studio provee los servicios en China para que las compañías lleven sus prototipos a mayor excala, utilizando procesos propios de ingeniería, manejo de la cadena de suministros, fabricación ágil y distribución, además de acceso a inversores.

#### Tipo 3: terciarizadores

Este modelo se puede comparar con el tipo 6 de Tincq, o modelos de plataforma.
Haciendo una analogía con plataformas como Etsy, propone la oferta de servicios de hardware científico abierto, como por ejemplo la realización de experimentos. 
Un ejemplo de este tipo es Science Exchange, una plataforma que conecta laboratorios avanzados con científicos que requieren realizar experimentos (Gould, 2015). 


> **Box 9: Open Desk**
>
>Opendesk se autodefine como una plataforma global para la producción local. Consiste en una herramienta de "producción abierta" que puede utilizarse para descargar, fabricar y comprar mobiliario. Cuenta con un catálogo de diseños específicamente realizados para la fabricación digital, por lo cual el objeto puede producirse localmente, de acuerdo a la demanda, en cualquier lugar del mundo.
>
>Cuánto de este proceso es realizado por el usuario depende un poco de sí mismo. Si se cuenta con la capacidad y herramientas para construir el diseño, se puede descargar y hacer el producto desde cero. En caso contrario, se puede contratar un maker desde la página, que fabricará el objeto para el cliente. Mientras mas trabajo se haga personalmente, mas bajo es el costo. Todo depende de donde se encuentre, si hay fabricantes locales disponibles y de si se tiene acceso a la maquinaria necesaria.
>
> <img src=https://d2mgbjyendvdw0.cloudfront.net/02628/02973/5ee268/opendesk_furniture_lean-desk_design-listing-page_listing-image-image-side-all-ply_full_2.jpg width=70%>       
> _Fig. 15: modelo de escritorio disponible para descargar (Fuente: OpenDesk.com)_
>
>Iniciada a partir de un petitorio en Crowdfunding en 2014, Opendesk es propiedad en parte de los miembros de la comunidad -diseñadores, clientes, fabricantes- e inversores privados. Por un lado, los diseñadores cuentan con un canal global de distribución, los makers consiguen nuevos clientes y un pago justo por su trabajo, y el cliente obtiene un producto que no posee el sobreprecio del mercado de diseño, además de producido de una forma social y ambientalmente más responsable.

## Políticas

Como se menciona anteriormente, el campo de desarrollo de hardware científico es reciente, sin embargo algunos autores comienzan a elaborar recomendaciones de políticas para su crecimiento. 

Baden (2015) identifica un esbozo de recomendaciones de políticas para el desarrollo del hardware científico abierto, orientadas principalmente a la educación e investigación:

1. Incoporar el hardware científico abierto en la currícula escolar oficial;
2. Aumentar cursos prácticos con hardware científico abierto para cientificos y docentes dentro de la currícula oficial;
3. Asegurar infraestructura de fabricación digital en las instituciones de investigación y educación;
4. Promover la inversión empresarial en modelos abiertos de desarrollo de producto.

Pearce (2017) recomienda cuatro direcciones para futuras políticas de hardware científico abierto en Estados Unidos a fin de aprovechar los retornos de inversión tanto para agencias de financiación como instituciones de investigación.
Asegura que ésto no sólo sería positivo para laboratorios si no también para empresas de tecnología, start-ups y formación de recursos humanos.
Se enfoca en cuatro medidas que permitirían un escalamiento horizontal, a través de una inversión inicial seguida de replicación digital de bajo costo:

1. Establecer una agencia ferederal que identifique las oportunidades estratégicas de inversión con alto ROI en términos de hardware científico abierto;
2. Promover el desarrollo de los equipos identificados, favoreciendo la compra de equipos abiertos validados en todas las dependencias del Estado y asegurando fondos para su desarrollo;
3. Crear una base de datos abierta de hardware científico abierto validado con toda su documentación asociada;
4. Proveer incentivos a emprendedores para escalar la producción de componentes de difícil acceso.

La comunidad GOSH (2018) identifica la necesidad de recomendar e implementar políticas que fomenten el crecimiento del movimiento, orientadas a la apertura institucional en universidades y organismos de investigación, y la disponibilidad de fondos.

En Latinoamérica en general aún no se multiplican las recomendaciones de políticas específicas para hardware científico abierto, con la excepción de Ecuador (FLOK, 2015), donde se identifica la necesidad de fomentar la innovación social a través del mismo. 
Particularmente son cuatro recomendaciones en la misma dirección que la propuesta de Pearce. 
En Venezuela en el 2004 se realizaron talleres que convocaron miembros del sector público y privado para la "Elaboración  de  Políticas  para  la Administración y Uso del Hardware en la Administración Pública".
El propósito fundamental de ese taller era el  “fortalecimiento  de  la  infraestructura  tecnológica  en  el  área  de manufactura, producción y comercialización de hardware, también fomentar el conocimiento y la capacidad de invención, comercialización de productos en el mercado interno y externo aprovechando nuestro potencial y ubicación geopolítica en el mundo.” (Córdova, 2004)


## Desafíos

El fenómeno del hardware científico abierto es relativamente reciente, con un crecimiento exponencial de iniciativas a partir de 2012 en áreas muy especializadas.
La comunidad Global por el Hardware Científico Abierto (2018) identifica tres áreas principales de trabajo: aprendizaje, sostenibilidad y crecimiento:    

Fomentar el aprendizaje y la investigación en las siguientes áreas:

- Diversidad de la comunidad
- Métodos de colaboración y coordinación
- Modelos de negocio
- Licencias abiertas y políticas de innovación 
- Métricas situadas para la evaluación de proyectos 

Relacionados a la sostenibilidad de las iniciativas:

- Desarrollo de modelos de gobernanza
- Colocar el hardware científico abierto en agenda institucional
- Obtener apoyo en términos de espacios e infraestructura
- Obtener apoyo en términos de fondos
- Disminuir las barreras de acceso de los usuarios
- Mejorar los controles de calidad y calibraciones

Relacionados al crecimiento de la comunidad:

- Aumentar el número y diversidad de participantes
- Desarrollar recursos educativos abiertos
- Desarrollar actividades de difusión

Pearce (2017) identifica tres obstáculos principales en el crecimiento del hardware científico abierto a mayor escala, que coinciden con algunos anteriormente mencionados.
En primer lugar, los recursos económicos para desarrollarlo son limitados, principalmente debido a que las agencias de financiación aún prefieren no correr riesgos y utilizar patentes para asegurar sus inversiones (Demsetz,  1973; McGaughey, 2002; Smith, 2007; May, 2013). 
El modelo de propiedad intelectual, fuertemente anclado en las agencias públicas y privadas que financian la compra de equipos, desacelera la innovación como se ha documentado por ejemplo en el área de la nanotecnología (Pearce,  2012b).  
En segundo lugar, debido a la naturaleza distribuida de la producción de hardware científico abierto, éste no se encuentra en los catálogos que se ofrecen a los consumidores, dificultando su difusión. 
Finalmente, las instituciones y organismos de investigación favorecen la compra de equipos propietarios debido a mecanismos burocráticos.
El bajo costo del equipamiento abierto permite una tasa de overhead mucho menor para las Universidades, que paradójicamente no lo ven conveniente (Pearce, 2016).

Desde el punto de vista de los usuarios, no todos los científicos se sienten cómodos con modelos abiertos de equipamiento, prefiriendo soluciones 'llave en mano'.
Otro factor no menos importante es la falta de información sobre demanda de equipamiento abierto, que algunas iniciativas están intentando cubrir (Chagas, 2019).
Existen aún obstáculos asociados a la barrera de ingreso relacionada al expertise, que aún es alta en algunos casos, pero también en términos de acceso a materiales, con diferencias entre países del norte y sur global.

## Oportunidades

Las ventajas de desarrollar hardware abierto que primero aparecen son las relacionadas a la eficiencia:

- En general los equipos suelen tener costos menores que sus pares propietarios, bajando los costos de investigación y habilitando estudios más potentes (Pearce, 2012);
- Es posible personalizar los diseños para responder a una variedad de situaciones, esta mayor flexibilidad acelera la experimentación y evolución de la ciencia experimental (Pearce, 2014);
- Los científicos no deben limitarse a las opciones de equipo disponibles en el mercado, lo que resulta valioso especialmente en disciplinas novedosas;
- Mejora el control sobre los laboratorios, cortando dependencias con monopolios de proveedores (Bruns, 2000; Kogut and Metiu, 2001)
- Posibilidad de contar con equipos siempre actualizados y con menor tasa de decarte dado que el usuario puede repararlos o acceder a asistencia técnica distribuida

Pero existen aportes en otros términos, relacionados a la democratización de las herramientas científicas:

- Acceso a la producción de conocimiento científico en laboratorios de recursos escasos
- Soporte para actividades de activismo  y ciencia comunitaria, como monitoreos ambientales comunitarios (Public Lab, )
- Involucrar nuevas voces y nuevos problemas de investigación en la producción de conocimiento científico (Kera, 2018)
- Facilitar la enseñanza y creatividad en áreas STEM en zonas de recursos escasos (Tech Academy)
- Fomentar el surgimiento de nuevas compañías basadas en modelos de negocio abiertos

***
> **Box: trend4africa**
***


## Bibliografía

Ver [aquí](chapter1_biblio.md)
