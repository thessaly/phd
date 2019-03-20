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

Más allá de la terminología empleada, la definición hace referencia a dos comunidades: de Hardware Abierto (OSHWA) y de Obras Culturales Libres. 

La comunidad de [Open Hardware (OSHWA)](https://www.oshwa.org/) toma la siguiente definición de apertura:

>"Hardware abierto es aquel hardware cuyo diseño se hace disponible públicamente para que cualquier persona lo pueda estudiar, modificar, distribuir, materializar y vender, tanto el original como otros objetos basados en ese diseño.
>
>Las fuentes del hardware (entendidas como los ficheros fuente) habrán de estar disponibles en un formato apropiado para poder realizar modificaciones sobre ellas. Idealmente, el hardware de fuentes abiertas utiliza componentes y materiales de alta disponibilidad, procesos estandarizados, infraestructuras abiertas, contenidos sin restricciones, y herramientas de fuentes abiertas de cara a maximizar la habilidad de los individuos para materializar y usar el hardware. El hardware de fuentes abiertas da libertad de controlar la tecnología y al mismo tiempo compartir conocimientos y estimular la comercialización por medio del intercambio abierto de diseños".

Por otro lado, desde las [Obras Culturales Libres](https://freedomdefined.org), comunidad más amplia de personas y organizaciones alrededor de la cultura libre (ref), se enfatiza que para que una obra sea considerada libre debe cumplir con las siguientes cuatro libertades:

>
- la libertad de usar el trabajo y disfrutar de los beneficios de su uso
- la libertad de estudiar el trabajo y aplicar el conocimiento adquirido de él
- la libertad de hacer y redistribuir copias, totales o parciales, de la información o expresión
- la libertad de hacer cambios y mejoras, y distribuir los trabajos derivados
>

La obra debe estar cubierta por una licencia cultural libre, o su situación legal debe proporcionar las mismas libertades esenciales enumeradas anteriormente. Esto sin embargo no es condición suficiente, ya que una obra específica puede ser no-libre de otras maneras que restrinjan las libertades esenciales.

Especifican además criterios adicionales para que una obra sea considerada libre:

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

Este capítulo tiene la intención de introducir el concepto de hardware científico abierto a través de un hilo imaginario que conecta las distintas etapas de desarrollo de un proyecto de hardware científico abierto. Comienza con los orígenes y antecedentes, siguiendo con los factores macro que favorecieron el crecimiento exponencial de estas prácticas en los últimos años, para luego pensar qué razones movilizan a las personas a diseñar estos proyectos, cómo lo hacen, cuáles son los contextos más favorables para hacerlo, cuáles son los campos de aplicación donde surgen mayoritariamente y finalmente qué beneficios y qué obstáculos se presentan en el camino, tanto en términos individuales como colectivos.

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

## Orígenes

El movimiento por el software libre es uno de los pilares de las diversas ramas de la producción abierta y colaborativa.
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
A principios de los años 90 existía suficiente desarrollo como para crear un sistema operativo funcional, sin embargo el núcleo o kernel (Hurd) no estaba lo suficientemente desarrollado. 
Esto es lo que comenzó a desarrollar en 1991 Linus Torvalds, y que publicaría luego como Linux kernel bajo la licencia GPLv2, habilitando el uso de GNU-Linux a escala global.

Compartir de forma pública las innovaciones o mejoras realizadas de forma individual no constituye una novedad a través de la historia, ya que pueden rastrearse antecedentes en áreas tan diversas como la industria del hierro en el siglo XVIII (Allen, 1983) o el equipamiento médico (Von Hippel and Finkelstein,1979). 
Sin embargo el aporte del movimiento por el Software Libre a través del concepto de copyleft, sus licencias y la promoción del modelo de producción de pares sistematizó una forma de trabajar -e innovar- colaborativa, de libre circulación de la información. 
Según Mansell y Berdou (2008), GPL establece un proceso de governanza auto-propagador por fuera del control de autoridades nacionales, internacionales u organismos de regulación que usualmente controlan el diseño, producción y circulación del conocimiento y la información.
Esto inspiró otros movimientos en diversas áreas (open Source drugs, Open Design, Free Culture, Open Source Ecology para nombrar algunos), incluyendo el desarrollo de hardware.

Uno de los más importantes derivados del desarrollo del proyecto GNU y el trabajo de la Fundación por el Software Libre es el concepto de "Código abierto" (open source). 
Surge como respuesta de un grupo de programadores al término "software libre", dentro del mismo movimiento. 
El contenido político y la ambiguedad en inglés -que lo asocia a gratuidad- volvían difícil su adopción en el ámbito de los negocios. 
Es por esto que deciden generar un nuevo concepto, orientado a resaltar los beneficios en términos de colaboración y eficiencia, más cercano a la terminología empresarial.

En 1998 Eric Raymond -programador, autor de 'La Catedral y el Bazar', referencia en el ámbito open source-, hace un llamado público a la comunidad de software libre a adoptar el nuevo término y funda la asociación "Open Source Initiative". 
Contó con el apoyo de muchos personajes importantes de la comunidad en el primer "Open Source Summit" organizado por el editor especializado en tecnología Tim O'Reilly. 
Dentro de quienes apoyaron la iniciativa se encontraba Linus Torvalds. 
Richard Stallman se opone al concepto de código abierto ya que "resalta la posibilidad de crear software potente y de alta calidad, pero evita las ideas de libertad, comunidad y principios".

A modo de ejemplo de las controversias en la comunidad, en 2007 luego de años de discusiones en la comunidad de software libre se lanzó la GPLv3.
La mayor diferencia entre licencias es que la última prohíbe la 'tivoización', concepto acuñado por Stallman para referirse a dispositivos que utilizan software con licencia GPLv2 pero limitan las libertades del usuario mediante modificaciones de hardware. 
Torvalds se alejó de la discusión y no adoptó la GPLv3, por lo cual Linux sigue siendo GPLv2.

La visión del grupo disidente creció tanto en número como influencia convirtiéndose en hegemónica en la actualidad, con licencias específicas open source (ref) y un cada vez mayor número de compañías utilizando software de código abierto (ref), entre las cuales se encuentran grandes nombres como Google, Facebook o Microsoft. 
En los últimos años la definición de Código Abierto (ref) incluyó requerimientos adicionales a la libre disponibilidad del código, incorporando cláusulas de no discriminación a las personas, colectivos o grupos de trabajo.

***
>**Box2: Computadora Industrial Abierta Argentina**
>
>El Proyecto CIAA surgió en 2013 como una iniciativa conjunta entre el sector académico y la industria nacionales, con el objetivo de desarrollar un sistema electrónico abierto de uso general, donde absolutamente toda su documentación y el material para su fabricación estuviera libremente disponible en internet-(diagramas esquemáticos, diseño del circuito impreso, códigos fuentes de los programas, etc.-, que estuviera diseñado en base a criterios adecuados para su utilización en aplicaciones industriales, que no dependiera de una línea específica de procesadores, y que pudiera ser fabricado por la mayoría de las empresas PyMEs nacionales, lo que implicaba por ejemplo utilizar en el diseño circuitos impresos de no más de cuatro capas.
>
>El hardware, el firmware y el software de la CIAA, así como los documentos y archivos generados como parte de su desarrollo, son liberados bajo las condiciones de la Licencia BSD modificada, que permite la redistribución ilimitada del producto, con o sin modificaciones y para cualquier propósito, siempre que se mantenga la autoría del proyecto y la renuncia a garantías.
>
> La primera versión, CIAA-NXP, fue diseñada utilizando un microprocesador provisto por la empresa NXP Semiconductors. Más adelante se realizaron versiones para microprocesadores de otras compañías. Lo interesante del proyecto es que se trata de una computadora industrial y abierta, ya que su diseño está preparado para las exigencias de confiabilidad, temperatura, vibraciones, ruido electromagnético, tensiones, cortocircuitos, etc., que demandan los productos y procesos industriales. Actualmente la CIAA es fabricada y comercializada por distintas empresas argentinas.
>
>![EDU-CIAA-NXP](http://www.proyecto-ciaa.com.ar/devwiki/lib/exe/fetch.php?media=desarrollo:edu-ciaa:edu-ciaa-nxp.png)    
>_Fig. 2: EDU-CIAA-NXP, una versión de bajo costo de la CIAA-NXP pensada para la enseñanza universitaria, terciaria y secundaria (Fuente: CIAA)_
>
>Entre algunos de los proyectos que utilizan CIAA, se encuentran aplicaciones de automatización industrial, equipamiento médico, industria ferroviaria, maquinaria agrícola. Además, se diseñó una versión educativa de la plataforma, la EDU-CIAA, más simple y de menor costo, para lograr un impacto en la enseñanza primaria, secundaria y universitaria.
***

## ¿Quiénes desarrollan hardware abierto y por qué?

Una de las discusiones centrales en la literatura open source es la de entender por qué las comunidades desarrollan tecnologías abiertas, qué motivaciones encuentran para invertir tiempo y energía en proyectos que pueden -o no- monetizarse, o qué otro tipo de retribuciones reciben los colaboradores. 
Al mirar el panorama de las comunidades que se encuentran desarrollando hardware abierto para ciencia el primer rasgo que surge es la heterogeneidad. 

Las motivaciones detrás de estos "hacedores" son diversas, abarcando un amplio espectro que incluye la figura del inventor hobbista y la tradición del “hágalo usted mismo”, las comunidades con una orientación política claramente definida, ancladas tanto en el autonomismo como el mediactivismo o la ética hacker, hasta nuevos “emprendedores” y organizaciones que comienzan a experimentar con modelos de negocio basados en la apertura.

Esta sección intenta reconstruir los contextos y motivaciones de los grupos que consideramos más relevantes al análisis de la comunidad de hardware científico abierto.

### Cultura hacker
Como se mencionaba anteriormente, la filosofía del software libre es uno de los pilares del movimiento de hardware abierto y en particular de hardware abierto científico. 
En los años de surgimiento alrededor de 1980 el MIT fue uno de los lugares donde la cultura hacker comenzó y floreció; la visión de este grupo se ve expresada en uno de los textos claves de la época: *'Hackers: Heroes of the Computer Revolution'* (Levy, 1984).

El libro de Levy hace explícita una 'ética hacker' que incluye compromiso con la libre circulación de la información, la meritocracia y la creencia de que puede construirse un mundo mejor y más bello utilizando computadoras.
Numerosas aproximaciones a la cultura hacker invocan este hito aplicándolo a toda la comunidad y obviando las múltiples y diversas motivaciones que coexisten dentro de ella (Coleman, 2009).

El concepto de libertad, ya sea en términos de libertad de expresión, privacidad, meritocracia o poder de los individuos, es constituyente principal del discurso hacker (Coleman, 2004; Kelty, 2005, 2008). 
Sin embargo la articulación de estos conceptos liberales toma diferentes formas en la interacción con sistemas socio-técnicos diversos, creando un set de expresiones relacionadas pero diferentes en torno a la propiedad, el trabajo y la creatividad (Coleman y Golub, 2008).

Maxigas (2012) propone reconstruir estas identidades diversas a partir de una genealogía de dos de los espacios predominantemente habitados por la comunidad hacker: los hackerspaces y los hacklabs. 
La reconstrucción histórica de estas dos posiciones que realiza el autor resulta útil porque muestra dos aspectos del gradiente que dan origen a múltiples ensamblados que encontramos en la actualidad.
Además permite entender cómo sobre la figura de los hackerspaces, por ejemplo, se suman en los últimos años nuevas comunidades como la de Biohacking.

#### Hacklabs, autonomistas y mediactivistas 
El primero de los casos se centra alrededor del espacio de los ‘hacklabs’. Yuill (2008) los define como "*[...] espacios voluntarios que proveen acceso público y gratuito a computadoras y a Internet. Usualmente hacen uso de máquinas recuperadas y recicladas que corren GNU/Linux y a la vez que proveen acceso a computadoras, la mayoría de los hacklabs tienen talleres funcionando en un rango de temas que van desde el uso básico de la computadora e instalación de software GNU/Linux, hasta programación, electrónica y radiodifusión independiente (o pirata). Los primeros hacklabs se desarrollaron en Europa, usualmente surgiendo de tradiciones de centros sociales ocupados y media labs comunitarios. En Italia se les relaciona con los centros sociales autonomistas y en España, Alemania y en los Países Bajos con movimientos de ocupación anarquistas"*. 

Por un lado los movimientos autonomistas, tomando conceptos marxistas y anarquistas, tuvieron relevancia en los años '70 en Italia, Alemania y Francia con la premisa de proveer alternativas a las instituciones administradas por el Estado. 
Una de sus estrategias era el squatting u ocupación de inmuebles, donde una de las funciones de los espacios ocupados era la de 'centro social' donde se reproducían alternativas a las instituciones oficiales.

Otra de las prácticas era el medioactivismo, sobre una tradición de publicación independiente con hitos en la radiodifusión pirata y comunitaria desde los años '60. 
Las comunidades de medioactivistas apropiaron tecnologías de consumo masivo como grabadoras y otros productos electrónicos accesibles en los años '80, y luego computadoras personales. 
Su objetivo entre otros era bajar las barreras para la participación de la producción cultural y tecnológica, y establecer una infraestructura de comunicación distribuida para organizaciones anticapitalistas. 
Como tales, tuvieron un rol importante en el surgimiento del movimiento alternativo a la globalización: la iniciativa de mayor resonancia en este sentido fue la red Indymedia de comunicación independiente.

Estas dos tendencias se combinan en el origen de los hacklabs. Los centros sociales ocupados, en el corazón de la vida urbana, requerían de infraestructuras de comunicación como acceso público a internet y computadoras.
Los mediactivistas, por el otro lado, requerían estrategias para convocar, producir, enseñar y aprender.

Algunos ejemplos de hacklabs son Ultralab en Forte Prenestino, Italia, surgido a fines de los '90, que se autodefine como un 'patrón emergente' de la conjunción de necesidades tecnológicas de las comunidades que lo integran. 
Otro ejemplo más reciente es Hackney Crack House en Londres, que hasta 2012 proveía una red de área local y servidor al espacio ocupado donde se alojaba, y funcionaba como lugar de reunión para experimentar con distintas tecnologías.

Los hacklabs son espacios declaradamente políticos que aparecen en cada vez menor número, focalizados a desarrollar infraestructura de comunicaciones para las comunidades que los habitan, privilegiando la creatividad y el acceso a quienes generalmente se ven inhabilitados para ello.

#### Hackerspaces y expansión
El caso de los hacklabs describido anteriormente es un extremo del espectro político.
Existe un gradiente de variantes como ser fablabs, makerlabs, medialabs, innovation labs y espacios de co-working.
Los últimos dos (y también los fablabs), de surgimiento más reciente, se distinguen por estar inmersos en un contexto institucional (universitario, gubernamental, organización o empresa); su fin es la innovación en investigación o productos comerciales.
Lo que diferencia a los hackerspaces del resto de estos espacios es que están administrados por y para integrantes de la comunidad hacker.

La primer ola de hackerspaces se relaciona a la cultura universitaria ya mencionada del MIT y otros institutos en los Estados Unidos, donde se desarrollaban las primeras computadoras y sistemas operativos.
Por otro lado la escena se completaba con grupos que hacían ingeniería reversa de las nuevas tecnologías, en ese momento mayoritariamente redes telefónicas.
En Europa la historia está menos documentada pero uno de los hitos es la fundación del Chaos Computer Club en 1981, con fuerte foco en la investigación sobre seguridad informática y privacidad.

Una nueva ola de hackerspaces parece haber sido iniciada a partir de una serie de conferencias en 2007 y 2008, orientadas a los problemas prácticos de cómo se administra y organiza un espacio de estas características.
Resulta relevante ya que pone el concepto de hackerspace al frente y la creación de nuevos espacios en agenda. 

Estos nuevos espacios fomentan un modelo de membresía abierto con funciones de aprendizaje, producción y socialización.
Las actividades varían entre iniciativas, pero el autor detecta una progresión desde las tareas de desarrollo de software libre hacia las de hardware, primero con desarrollo de infraestructura de redes, luego microelectrónica y en algunos casos impresión 3D - fabricación digital.
El surgimiento de Arduino provocó una explosión de proyectos e interacción en este tipo de espacios, con medios como la revista MAKE y otros para difundirlos.

El desarrollo y expansión de los hackerspaces se alinea con la trayectoria del movimiento hacker, que gana cada vez mayor anclaje institucional.
El autor reconoce que la apertura a la interfaz física (mayoritariamente a partir de trabajo con microcontroladores) permitió el crecimiento masivo del modelo, ya que la colaboración en este tipo de proyectos se ve facilitada por la disponibilidad de espacios comunes. 
El contenido político es más difuso, más orientado a valores liberales, lo que le permite una flexibilidad y expansión hacia un espectro mayor: desde el público general a las empresas.

### Cultura Do-it-yourself (DIY)

Esta ampliación del espectro de los hackerspaces permite que confluyan con la cultura del **Hágalo Usted Mismo** (“Do it yourself” o DIY), mencionada antes con el desarrollo de Arduino, la revista MAKE y la MakerFaire organizadas en New York, San
Francisco y Nairobi.
Algunos antecedentes culturales de estas actividades incluyen las prácticas DIY de mitad de siglo XX en Estados Unidos (la figura del inventor o hobbysta), donde actividades previamente utilitarias se transformaron en ocio (Haring, 2006), y las actividades de radio aficionados (Douglas, 1987).

En la actualidad resulta útil la distinción que Hertz (2011) realiza sobre DIY utilitario y DIY hedonista. 
El primero responde a la necesidad de construir objetos con los materiales disponibles, muchas veces escasos o inapropiados, para resolver problemas de la vida cotidiana. 
Por ejemplo, el productor que cuando se enfrenta a una falla en una maquinaria intenta reemplazar la funcionalidad perdida con otros implementos, o el científico que en un laboratorio sin recursos desarrolla métodos alternativos para llegar a sus resultados. 

Sin embargo, esta motivación -la necesidad- no es la predominante dentro del movimiento “maker”, al menos en la escena de los países desarrollados. 
En estos espacios la comunidad maker se asocia a un DIY hedonista, ligado a la creciente disponibilidad y bajos costos de componentes electrónicos -como Arduino (ver Box 1)- que permiten construir artefactos de consumo personalizados. 
En este último caso predomina el elemento lúdico, la exploración personal y el aprendizaje de nuevos métodos.

Según Mark Frauenfelder -editor jefe de la revista MAKE, de referencia para el sector- las motivaciones de la comunidad maker responden a una insatisfacción con la cultura del consumo y del descarte, y a una revalorización del concepto japonés de *wabi-sabi* o la "*apreciación de la imperfección de los objetos*" (Suzuki, D.1959). 
Hertz suma a esto la motivación generada por reacción a la cultura de la caja negra (“black box”) típica de la fabricación en la era digital: la velocidad de las innovaciones en materia de tecnología implica que los objetos de consumo estén producidos basándose en componentes y procesos complejos. 

El concepto de caja negra implica que no es posible para el usuario comprender su lógica interna sino sólo el resultado de su funcionamiento, incluso siendo experto. 
Si un objeto se rompe o queda obsoleto, se vuelve inutilizable y genera dependencia de los fabricantes, lo cual es altamente frecuente dados los paradigmas de obsolescencia programada dominantes en la industria. 
Reemplazar partes es casi imposible para los consumidores, dada la alta especialización de la ingeniería y fabricación que el objeto conlleva. 
Este rol pasivo de los consumidores genera una reacción por parte de la comunidad DIY, que construye objetos de consumo con componentes simples y compartiendo información, algo que Frauenfelder engloba en el concepto de “vivir auténticamente”.

A nivel de comunidad, los "makers" cuentan con reuniones y exposiciones anuales -Maker Faire-, el desarrollo de un mercado cada vez más importante de componentes y kits electrónicos de fácil utilización (Powell, 2012) y la existencia de la revista MAKE, una especie de continuo de la revista Popular Mechanics de mediados del siglo XX, orientada a la clase media y las actividades hobbistas de tiempo libre. 
El papel de MAKE no es menor: varios autores le asignan el rol de moldear y normativizar el rumbo que toma la comunidad en base a las prácticas que se difunden a través de ella.

### Biohacking o DIY biology
Garage biology, biohacking y biología ciudadana son expresiones que describen un movimiento de amateurs realizando experimentos biológicos fuera de los ámbitos tradicionales como universidades o corporaciones.
Delfanti () analiza DIYbio, la iniciativa más reconocida, una red creada en 2008 compuesta de varios grupos en ciudades de Europa y Estados Unidos.
Tiene como objetivo proveer a los no expertos con un espacio de colaboración y protocolos y herramientas de código abierto para la investigación biológica.
Como tales, son parte del fenómeno de la producción abierta y colaborativa a través de plataformas online (Benkler, 2006).

Los miembros de la comunidad tienen relación con el movimiento hacker: desarrollan sus espacios bajo el modelo de hackerspaces o directamente instalan una sección 'bio' en hackerspaces existentes.
Están además inmersos en una red de emprendedores y start-ups que enfrentan al gran mercado de las compañías Bio.
En 2008 el movimiento comenzó con Mackenzie Cowell, un desarrollador web, y Jason Bobe, parte del proyecto Genoma en la escuela de Medicina de Harvard.
En 2010, cerca de 2,000 personas eran parte de la lista de correos y existían docenas de grupos comunitarios desde Massachusetts a Bangalore.

Las actividades incluyen proyectos de ciencia ciudadana simples como aislamiento de bacterias o extracción de ADN, pero también construcción de hardware científico abierto (Ward, 2010).
DIYbio dialoga con instituciones como universidades, compañías, medios y agencias gubernamentales preocupadas por cuestiones de ética y seguridad (Schmidt, 2008).
Los miembros son jóvenes biólogos, profesionales de la computación que desean experimentar en biología y artistas interesados en un abordaje crítico DIY a la biología.

En cuanto a cómo se definen, la comunidad nombra referencias como la cultura hacker, el DIY y el movimiento del Software libre, el espíritu lúdico y 'biopunk'.
Establecen comparaciones con el Homebrew Computer Club, el centro de operaciones hacker de los '70 en la Bahía de San Francisco, donde se encontraban Steve Wozniak, Bill Gates, Steve
Jobs y otros (Bloom, 2009; Economist, 2009; Golob, 2007; Johnson, 2008). 
Otros se definen como makers, artesanos, entusiastas, hobbistas o amateurs pero coinciden en la visión de la innovación norteamericana y la cultura de garage.

Como colectivo resaltan la importancia del rol educativo sobre las biotecnologías, especialmente frente a dudas sobre seguridad o ética en las prácticas (DIYbio 2010). 
La apertura es un requisito de la iniciativa a fin de volver el campo *'accesible para quien desee involucrarse'*.
El acceso a equipamiento científico es uno de los obstáculos de estas iniciativas, lo que las vuelve uno de los ámbitos más productivos del hardware científico abierto con ejemplos como OpenPCR (http://openpcr.org). 

### Innovaciones de usuario en ámbitos académicos
Von Hippel 1976

### Latinoamérica: el movimiento de tecnología apropiada
Fressoli 2017


## Enablers
Hablar de explosión proyectos ohw (Berchon, 2013):
- disminución en los costos de los componentes  (shenzhen)
- acceso a componentes
- acceso a servicio de fabricación post prototipado
- impresión 3d
- arduino
- kits pre armado
- acceso a conocimiento por masificación de internet

VON Hippel:

Users’ abilities to develop high-quality new products and services for them-
selves are improving radically and rapidly. Steady improvements in com-
puter software and hardware are making it possible to develop increasingly
capable and steadily cheaper tools for innovation that require less and less
skill and training to use. In addition, improving tools for communication
are making it easier for user innovators to gain access to the rich libraries of
modifiable innovations and innovation components that have been placed
into the public domain. The net result is that rates of user innovation will
increase even if users’ heterogeneity of need and willingness to pay for
“exactly right” products remain constant.

Today, in sharp contrast, user firms and increasingly even individual hob-
byists have access to sophisticated design tools for fields ranging from soft-
ware to electronics to musical composition. All these information-based
tools can be run on a personal computer and are rapidly coming down in
price. With relatively little training and practice, they enable users to design
new products and services—and music and art—at a satisfyingly sophisti-
cated level.

If one is designing a physical product, it is possible to create a design and
even conduct some performance testing by computer simulation. After
that, constructing a real physical prototype is still not easy. However, today
users do have ready access to kits that offer basic electronic and mechani-
cal building blocks at an affordable price, and physical product proto-
typing is becoming steadily easier as computer-driven 3-D parts printers
continue to go up in sophistication while dropping in price. Very excit-
ingly, even today home-built prototypes need not be poorly fashioned
items that will fall apart with a touch in the wrong place—the solution
components now available to users are often as good as those available to
professional designers.


I summarize this overview article by again saying that users’ ability to innovate
is improving radically and rapidly as a result of the steadily improving quality of
computer software and hardware, improved access to easy-to-use tools and com-
ponents for innovation, and access to a steadily richer innovation commons. Today,
user firms and even individual hobbyists have access to sophisticated programming
tools for software and sophisticated CAD design tools for hardware and electron-
ics. These information-based tools can be run on a personal computer, and they are
rapidly coming down in price. As a consequence, innovation by users will continue
to grow even if the degree of heterogeneity of need and willingness to invest in
obtaining a precisely right product remains constant.(Von Hippel, 2005)

***

## ¿Cómo se hace hardware abierto?

Una de las principales cuestiones que la literatura analiza es la diferencia entre el proceso de desarrollo del software y el de hardware. Mientras la virtualidad del software facilita la colaboración sin mediar distancias en un proceso bastante directo entre usuarios, la materialidad inherente al desarrollo de hardware implica que éste requiera de instancias discretas y potencialmente independientes de trabajo. Como se ve en algunos estudios de caso, esto determina cuellos de botella particulares, asociados principalmente al multi-expertise requerido para modificar un objeto y a la existencia de patentes en los objetos físicos. Al respecto, algunas organizaciones han comenzado a documentar protocolos de desarrollo de OSH, a manera de guías de buenas prácticas (Cenditel) o describiendo procesos exitosos (Ackermann, 2009).

Los pasos necesarios para construir hardware electrónico han ido mutando hacia formas automatizadas en los últimos años. Sin embargo aún se precisa contar con ciertos conocimientos y herramientas específicos.

Un primer paso consiste en obtener un **diagrama esquemático**, es decir un gráfico donde se especifican los componentes electrónicos (resistencias, capacitores, circuitos integrados)  a utilizar y sus conexiones, a través de un sistema de símbolos. En caso de ser necesario también se indica información sobre valores de cada componente (por ejemplo una resistencia de 10-kilohm). Sin embargo el esquemático no posee toda la información necesaria para fabricar una plaqueta de circuito impreso.

![esquemático](https://upload.wikimedia.org/wikipedia/commons/thumb/7/76/4_bit_counter.svg/1280px-4_bit_counter.svg.png)
*Fig. 3: Ejemplo de diagrama esquemático de un contador TTL (Fuente: Wikipedia)*

En la actualidad, todos los objetos electrónicos se fabrican utilizando plaquetas de circuito impreso, a diferencia del sistema de cableado punto a punto utilizado hasta los años 60. Los circuitos impresos aportaron un nivel mucho mayor de automatización en la fabricación: se eliminó el cableado, ya que las conexiones, constituidas por líneas de cobre, se encuentran integradas en un soporte no conductor -generalmente epoxy- que además sostiene los componentes. Esto permitió no sólo reducir el espacio que ocupa el circuito sino también integrar el uso de microchips, el corazón de las tecnologías como teléfonos móviles, computadoras, tablets y más.
<br>
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/67/PCB_design_and_realisation_smt_and_through_hole.png/1024px-PCB_design_and_realisation_smt_and_through_hole.png" width=80%>    
*Fig 4: ejemplo de diseño digital de circuito impreso (izq.) y circuito final (der.) (Fuente: Wikipedia)*

Hasta el advenimiento de las herramientas digitales, el paso del esquemático al circuito impreso requería cierta habilidad "artística" del fabricante: se utilizaba una “máscara” de cinta negra sobre una placa de acetato para indicar la ruta de conexiones más eficiente a fin de transformar el diagrama en una plaqueta. Actualmente este proceso se encuentra automatizado en dos pasos: primero se crea digitalmente a partir del diagrama una “**captura esquemática”**, es decir una representación lógica de los componentes y su interconexión. El producto de este proceso es un archivo conteniendo toda la información sobre el diagrama y un archivo “netlist” con datos sobre conexiones eléctricas entre componentes.

Los dos productos de la etapa anterior son luego traducidos en un segundo paso -en el que puede utilizarse o no el mismo software-, a fin de obtener un **diseño físico** posible de ser fabricado. Utilizando librerías de componentes -específicas, provistas por desarrolladores del software utilizado y compartidas por la comunidad- que proveen información detallada sobre tamaño, forma y conexiones, se diseña la configuración física final del circuito. Es un proceso orientado gráficamente, en el cual el diseñador ubica los componentes y las conexiones de la forma más eficiente posible -el software propone el arreglo más conveniente aunque siempre requiere retoques por parte del diseñador-. El producto de esta etapa es un set de archivos denominados "**Gerber**", en el formato utilizado por los fabricantes de circuitos impresos. Dado un set, el fabricante puede crear una o 100 mil copias de un circuito.

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

Los pasos descritos aplican al desarrollo de una plaqueta electrónica, presente en casi todos los artefactos que usamos a diario. Sin embargo, crear un artefacto requiere de otras instancias adicionales, como el diseño del aspecto, elección de los materiales, mecánica entre las partes, programación, etc. A diferencia del proceso colaborativo que da origen al software libre, en el caso del hardware la multiplicidad de conocimientos requeridos para comenzar a trabajar impone ciertas restricciones: salvo contadas excepciones, se requiere de trabajo en grupo donde actores de diversa formación aporten sus conocimientos.

Algunos autores enfatizan que uno de los criterios para que un desarrollo de hardware sea exitoso es que la comunidad de colaboradores sea lo suficientemente grande para asegurar un mínimo de aportes diversos.  Sin embargo, Buechley remarca que este proceso de colaboración se da de manera más descentralizada en hardware que en software, observándose mucho más frecuentemente múltiples iniciativas de pequeña escala, con una dinámica más "privada" de la colaboración, sobre grandes iniciativas a partir de comunidades numerosas. El carácter privado de la colaboración también es observado por Malinen en el caso del desarrollo del eCar finés: a la hora de construir hardware, es más común que la colaboración exitosa se pueda dar en pequeños grupos que al menos una vez se encuentran físicamente en lugares de trabajo.

Aunque los costos de las plataformas electrónicas como Arduino realmente disminuyeron y las volvieron accesibles en el último tiempo, todavía la velocidad de iteración -es decir cuán rápido se puede modificar un artefacto- sigue siendo un obstáculo en el desarrollo de hardware si lo comparamos con el de software. Por ello tanto Buechley como Malinen y Mellis coinciden en que otro aspecto clave a la hora de facilitar el proceso de desarrollo de hardware libre es la modularidad de los artefactos a desarrollar. Resulta mucho más sencillo modificar o diseñar un objeto si sus funciones se encuentran diferenciadas en módulos, ya que en caso contrario es necesario cambiarlo todo para modificar sólo una función.

En cuanto a las dificultades que se identifican en los procesos de desarrollo, principalmente son aquellas relacionadas a la dificultad de conseguir componentes -que no se encuentran disponibles en todos los países-, la necesidad de estandarización en el uso tanto de plataformas electrónicas como de software de diseño, que permita a los grupos interactuar de forma sencilla -en este sentido todos los autores remarcan la importancia de Arduino-, y en menor medida la dificultad para documentar y trackear los cambios entre versiones -para lo cual existen iniciativas de documentación por parte de distintas organizaciones-.

> **Box3: Open Source Ecology - Global Village Construction Set**     
> Open Source Ecology es una iniciativa de Marcin Jakubowski, un estudiante polaco de física nuclear en Estados Unidos, quien después de obtener su doctorado comenzó a trabajar en su propia finca en Missouri. Allí se dio cuenta que era incapaz de reparar por sí mismo el tractor con el que trabajaba debido al elevado costo de los repuestos, por lo que decidió crear ‘Global Village Construction Set’, siguiendo la filosofía del software libre.
>
> Global Village Construction Set es el desafío de crear 50 herramientas que cualquier finca necesitaría con el objetivo de ser sostenible y autónoma. Según Wikipedia, es "Una plataforma de alto rendimiento, modular, de bajo costo, do-it-yourself que habilita la fabricación de 50 máquinas industriales diferentes que se precisan para construir una pequeña y sostenible civilización con comodidades modernas".
>
>![Global village construction set](https://www.opensourceecology.org/wp-content/uploads/2014/02/gvcs-all-50.jpg)    
>_Fig. 6: El kit incluye un tractor, impresora 3D, cortadora láser, soldadora, aserradero, un horno de panadería, un pulverizador de suelo, una sembradora, un aerogenerador, entre otros (Fuente: Open Source Ecology)_
>
>La filosofía de Open Source Ecology es que el problema del acceso a las herramientas y maquinarias no está relacionado a la escasez de recursos sino a su distribución desigual. Volviendo accesibles los planos, esquemáticos y manuales, Open Source Ecology busca fabricar herramientas accesibles para todos, especialmente aquellos que habitan pequeñas comunidades.
>
>El proyecto ha estado funcionando durante los últimos 5 años, contando ya con alrededor de 20 prototipos. Ofrecen planos y manuales (incluyendo tutoriales en Youtube) sobre cómo fabricar las herramientas, además de talleres específicos en los sitios de interés. Al compartir los diseños online, permitieron que se creara una gran red de personas que colaboran el diseño de las máquinas, las mejoran y modifican para adaptarlas a nuevos usos. Una encuesta en 2014 registró 110 réplicas de los diseños provenientes de Global Village Construction Set en Estados Unidos, Chile, Nicaragua, Guatemala, China, India, Italia y Turquía
>
>![johndeere](https://image.slidesharecdn.com/openhardwarebusinessmodels-141115072738-conversion-gate01/95/business-models-for-open-source-hardware-23-638.jpg)    
>_Fig. 7: Comparación de costos entre maquinaria agrícola abierta y privativa (Fuente: Benjamin Tincq)_
>
>Open Source Ecology es una obvia inspiración para otros “makers” y emprendedores, pero además puede brindar lecciones a instituciones de investigación y desarrollo existentes. Existen enormes oportunidades en el acceso abierto a los planos técnicos de maquinaria agrícola, energía renovable y tecnologías de acceso al agua y saneamiento, que ya han sido desarrolladas por dichas instituciones de I+D. Abrir esos diseños podría ayudar a los actores locales a adquirir nuevos conocimientos, desarrollar sus propias herramientas e incluso ayudar a mejorar las que ya están disponibles.


## ¿En qué áreas se desarrolla hardware abierto?

#### Ciencia

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

#### Educación

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

#### Negocios

La explosión del OSHW abrió la puerta a múltiples modelos de negocio que utilizan parcial o totalmente la apertura como estrategia de monetización. Según un informe sobre el estado de situación de los emprendimientos OHW (Berchon. 2013), la mayoría se encuentran en los Estados Unidos (68%) -concentradas en los núcleos de desarrollo de hardware alrededor de las universidades y hackerspaces activos- seguido por Europa (19%) y Asia (7%). Sin embargo el rasgo más llamativo es que la mayoría de las iniciativas funcionan completamente online, siendo la colaboración, distribución y comunicación virtuales, por lo que la ubicación no sería un factor determinante para este tipo de emprendimientos.

Gran parte de las compañías basadas en OHW trabajaban en 2013 en el rubro de electrónica para hobbistas y educación (63%); muchas de ellas inspiradas por el éxito de modelos como Arduino o Raspberry Pi, desarrollando kits y placas compatibles. La segunda posición es para las herramientas de fabricación (15%), más específicamente impresión 3D (11%). El resto del mercado se encuentra fragmentado en nichos específicos: drones (3%), iluminacion (3%), sintetizadores de sonido (2%).

Hasta el año 2007 se lanzaba sólo una compañía OHW por año: ejemplos de ello son Parallax (1986), Solarbotics (1994), Lynxmotion (1995, luego comprada por RobotShop), ShopBot (1996), Egnite (1997), WIZnet (1998). Pero a partir de 2007 el número crece rápido -ver figura 12-. En promedio toma a los emprendedores dos años pasar de la idea del proyecto a un producto definido.

![](https://image.slidesharecdn.com/open-hardware-entrepreneurship-130909013556-/95/the-state-of-open-hardware-entrepreneurship-in-2013-9-638.jpg?cb=1380311117)    
_Fig. 12: número de empresas OHW lanzadas por año, a 2013 (Fuente: [Berchon, 2013](https://www.slideshare.net/makingsociety/the-state-of-open-hardware-entrepreneurship-in-2013?ref=http://makingsociety.com/2013/09/the-state-of-open-hardware-entrepreneurship-2013/))*_

En cuanto al perfil de los emprendedores, mayoritariamente poseen una formación en ingeniería (83%), diseño (17%) -incluyendo artistas digitales con conocimientos en aspectos técnicos- y docentes e investigadores (14%) provenientes de áreas técnicas, que dedican su tiempo libre a trabajar en proyectos OHW. El 47% de las compañías es liderado por emprendedores solos, comparado con el 52% que lo hace en equipo, lo que la autora atribuye a la ventaja de contar con una comunidad online fuerte de apoyo. Sólo el 5% de las compañías son lideradas por mujeres -excepciones notables como Adafruit o LittleBits-, y sólo 10% las incluyen en los equipos fundadores, aunque sí participan en gran medida en hackerspaces, proyectos y eventos.

Más de la mitad de las compañías se financian con sus propios recursos (62%) aunque cada vez es mayor el número de empresas que se financian parcial o totalmente a partir de crowdfunding (28%).

>**Box 8: Adafruit**
>
>Adafruit Industries es una compañía basada en open source hardware ubicada en la ciudad de Nueva York, fundada en 2005 por la hacker e ingeniera Limor Fried mientras estudiaba en el Massachusetts Institute of Technology. La empresa diseña y fabrica una serie de productos electrónicos y vende un amplio rango de componentes, herramientas y accesorios vía su tienda web. Los productos ofrecidos abarcan rangos de principiante -kits que producen sonidos al recibir una señal- a experto -como sofisticados microcontroladores para celulares y desarrolladores de videojuegos-.
>
><img src=https://www.wired.com/wp-content/uploads/blogs/geekmom/wp-content/uploads/2011/03/Wired-Cover.jpg width=50%>    
>_Fig. 13: Limor Fried, premiada como emprendedora del año en 2012, fue tapa de la revista de tecnología WIRED (Fuente: Wired)_
>
>Todos sus productos son fabricados en la planta del SoHo newyorquino, que cuenta con más de cien empleados. En 2013 entregaron 480 mil pedidos con más de un millón de productos, obteniendo ingresos por 22 millones de dólares. En 2016 registraron su pedido número un millón.
>El nombre Adafruit proviene del nickname "LadyAda" que Fried utilizaba online como homenaje a Ada Lovelace, la pionera en ciencias de la computación. La compañía además produce recursos educativos, incluyendo tutoriales escritos y videos en Youtube con el objetivo de entusiasmar a más personas para que se involucren en el desarrollo de tecnología, especialmente mujeres. En su sitio web oficial Fried declara: “Adafruit es una compañía 100% propiedad de una mujer”.

En cuanto a modelos de negocio posibles, la definición más amplia es la planteada por Benichou y Tincq (2014) donde establecen seis categorizaciones basadas en el valor: expertise/experiencia; diseño; fabricación; servicios; estandarización y modelo de plataforma.

1. **Basados en el diseño e investigación de productos**

Constituyen el modelo más común de negocio actual, donde la compañía se enfoca en el diseño e I+D de un producto, mientras delega su fabricación. Los activos más valiosos en este caso son la marca del producto y la comunidad generada alrededor de él. Existen variaciones según si lo que se comercializa son kits o ensamblados de partes (OpenROV; Open Energy Monitor); productos terminados (Arduino) ó productos basados en diseños compartidos por un ecosistema de fabricantes, gestionado por una fundación OHW -inspirado por un modelo más cercano al software libre- (Wikihouse)

2. **Basados en la producción**

El principal valor en este caso está asociado a la fabricación y distribución de productos OHW a precios accesibles. Al nombre de marca y la comunidad, se agrega como activo la eficiencia industrial. Simone Cicero (2013) agrega a esto que la ventaja de poseer los medios de producción se ha relativizado ya que el conocimiento, las herramientas y los diseños necesarios se encuentran accesibles a cientos de compañías e individuos; para el autor la capacidad de producción dejó de ser un factor diferencial en sí mismo. Por ello remarca que en este modelo, la ventaja reside en la elasticidad y capacidad de innovación de la compañía para generar nuevos productos.

Dependiendo del rubro, la variedad y velocidad de renovación del catálogo de productos resulta un factor de peso: por ejemplo en el rubro de electrónica (Sparkfun, Adafruit -ver Box 8-).

3. **Basados en el conocimiento y la experiencia**

Este modelo está inspirado directamente en la industria del software libre, su valor radica en la experiencia y el servicio. En OHW esto se traduce a talleres de DIY (Tripalium, Open Source Ecology), la venta del producto más la "experiencia" de construirlo (Wikispeed) ó venta de servicios de consultoría para empresas que desean utilizar el producto en su cadena de valor (Arduino, Wikispeed).

<img src=https://i.pinimg.com/originals/85/c9/99/85c999a3b9c1a0541c68c52a217cbb81.png width=70%>    
_Fig 14. Turbina eólica abierta de Tripalium, una fundación que promueve la energía eólica (Fuente: Tripalium.org)_    
    
4. **Sistemas de Producto-Servicio**

Surgieron en 1959 con el modelo de impresión pay-per-copy instalado por Xerox, y están teniendo mayor difusión actualmente de la mano de conceptos como la economía social y la economía circular. Se basan en ofrecer el derecho de uso del producto en lugar de su propiedad. En OHW aún es incipiente, pero el autor aduce que posee potencial. Cicero agrega que las compañías podrían beneficiarse a partir de un ofrecer el software como servicio asociado a un producto OHW, especialmente en el caso de los sistemas embebidos y la Internet de las Cosas (IoT) -aunque alega que el mercado aún no posee la madurez suficiente para llegar a ese lugar-.

5. **Estandarización y ¿apalancamiento?!**

Consiste en abrir estratégicamente un producto clave que sea redituable en sí mismo pero que su apertura implique un impulso para que la tecnología asociada a él se convierta en un estándar de la industria. El ejemplo típico en este caso es el sistema operativo Android, de Google, y los motores Tesla, que permitieron a Tesla Motors incursionar en el mercado de las baterías y estaciones cargadoras.

6. **Modelos de plataforma**

Su valor radica en organizar un ecosistema de actores industriales (diseñadores, fabricantes, revendedores, consumidores, prosumidores, marcas, etc.) alrededor de una tecnología clave OHW o plataforma. Casos paradigmáticos: OpenDesk (ver Box 9) y OSVehicle. OSVehicle diseñó el motor y chasis Tabby -OHW, eléctrico y modular-. Construyeron una "cadena de valor participativa" donde el mismo se distribuye de manera justa entre todos los participantes.
<br>

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

Un caso particular es del del modelo de negocio basado en **licencias duales**. Este sistema, altamente difundido en la industria del software, consiste en distribuir un producto tanto con licencia privativa como con licencia abierta. Es el caso de LEON, un microprocesador basado en tecnología SPARC-V que se distribuye tanto bajo licencia GPL abierta como con licencia privativa a fin de ser integrado en productos cerrados. Otra variante en este sentido consiste en modelos de negocio a partir de un núcleo de producto OHW cuyas extensiones y funcionalidades extra tienen carácter privativo.

Uno de los puntos más interesantes es el análisis de por qué aún el OHW no es masivamente adoptado en el mundo de los negocios, como sí es el OSW. La mayor parte de los autores coinciden en que los cambios no vendrán de las empresas tradicionales sino que una nueva camada de fabricantes irrumpirá en el panorama actual, debido principalmente a la rigidez organizacional de las grandes empresas. Cicero menciona que aunque las empresas líderes en hardware siguen siendo privativas -como Samsung o General Electric- existen industrias emergentes como la de los drones o UAV que están siendo enteramente desarrolladas bajo el concepto de hardware abierto y modular, con proyectos surgiendo día a día.

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

#### Personalización del consumo - DIY
***
**A completar**
Para el autor es esperable que aparezcan nuevos jugadores en el mercado de la producción de hardware que más allá de estar basados o no en la filosofía de apertura, aprovecharán la ventaja otorgada por la creciente modularización que el OHW trae a la industria -como hizo Google con el FLOSS-. Este escenario de fabricantes lo suficientemente elásticos en infraestructura sería compatible con un nuevo tipo de demanda, ágil, ultra customizada, orientada por la comunidad y a los prosumidores.

Según Cicero en los próximos años deberíamos poder observar transformaciones radicales en el concepto de "fábrica": la producción será descentralizada y potencialmente desvinculada de las marcas y fabricantes, acercándose al concepto defendido por FLOK sobre desarrollo endógeno y soberanía tecnológica. En este sentido Powell coincide con Cicero aunque resulta más escéptico respecto al beneficio social en otros aspectos -por ejemplo democratización en el acceso a la tecnología-. Ambos plantean que la inserción del modelo OHW en la industria traería ventajas relacionadas a la sustentabilidad al favorecer la desaparición de la obsolescencia programada en los productos de consumo .

Los principales obstáculos que se pueden identificar en el uso de OHW para modelos de negocio son los relacionados a las patentes -en muchos casos salvados por el dual licensing-, la falta de modularidad en los diseños actuales -que dificulta su intervención- y la necesidad de generar confianza en el consumidor acerca de la calidad de los productos de diseño abierto. Dependiendo del modelo de negocio analizado, si la orientación es hacia desarrollo de productos, el peso de la marca y el tamaño de la comunidad son factores limitantes: si la base es la producción entonces la oferta de un catálogo variado y renovado es un factor diferencial. En el caso de los modelos de licencia dual, algunos autores señalan que un obstáculo puede ser el lock in por parte de los usuarios con filosofía OHW, especialmente en el segmento profesional.



## Beneficios

A partir de la automatización de los procesos de desarrollo de los últimos años, y más específicamente a partir de la aparición de software no privativo capaz de generar archivos legibles para la industria de los circuitos impresos (set Gerber) surgió una nueva cadena de suministro basada en muy bajos costos de producción. Al día de hoy algunas compañías permiten que todo el proceso se realice a través de su página web: el usuario puede recibir los circuitos impresos en su casa unos días después de haber subido los archivos Gerber al servidor del fabricante. Todos los autores coinciden en lo revolucionario de contar con herramientas que permiten construir tecnología a los usuarios, aunque esto no necesariamente implique la independencia de los grandes fabricantes.

La disminución en los costos de producción para los *makers* impacta principalmente en la capacidad de experimentar. Es posible aumentar la velocidad de iteración, crear, fallar y volver a crear, sin que esto perjudique demasiado al inventor. La aparición de toolkits bajó la barrera de ingreso al mundo del desarrollo del OHW, posibilitando que no-expertos puedan también desarrollar sus productos, acarreando un boom de ventas para los proveedores de suministros electrónicos. El acceso de estos no-expertos se evidencia en sitios como Instructables, donde se observa una gran cantidad de proyectos del tipo DIY hedonista.

Algunos autores mencionan como beneficio social la capacidad de los desarrollos OHW de empoderar a las comunidades al contribuir a la soberanía tecnológica, aumentar la utilidad social y apropiabilidad en el uso de las tecnologías. Resaltan el valor educativo que deviene del trabajo necesariamente colaborativo y uso de nuevas herramientas, y el desarrollo de tecnologías que puedan responder mejor a las necesidades reales de sus comunidades de referencia. Estos beneficios se observan particularmente en los usos del OHW relacionados a la educación, la ciencia y la salud.

> **Box 5: Precious Plastic**
>
>Precious Plastic es una iniciativa de Dave Hakkens, un diseñador holandés, que surgió como proyecto final de graduación de la Academia de Diseño en 2013. Su objetivo es proveer a las personas de los medios necesarios para reciclar plástico en sus casas, sin depender de los recicladores industriales, considerando que el plástico es un material valioso que actualmente se considera un desperdicio contaminando agua y suelos en todo el mundo. El material reciclado se puede emplear tanto para fabricar objetos acabados como para obtener materia prima para otros procesos, como impresión 3D.
>
>Luego de dos años de trabajo junto a su equipo salió a la luz la versión 2.0 del proyecto. La idea central es que cualquier persona pueda fabricar las máquinas del set fácilmente con materiales accesibles en cualquier lugar del mundo. El diseño es modular para facilitar su construcción; también difunden videos tutoriales y la documentación necesaria a través de su página web, bajo licencia abierta.
>
>![preciousplastic](https://preciousplastic.com/images/hero-machines.png)    
>_Fig. 9: Set de máquinas que integran el proyecto: trituradora, extrusora, una máquina de inyección y una compresora (Fuente: comunidad Precious Plastic en Facebook)._
>
>El proyecto se difundió principalmente a través de un video en Facebook, en el cual Hekkens explica los conceptos detrás del mismo y solicita difusión. La comunidad se aglutina alrededor de un foro web (www.preciousplastic.com) donde se intercambian consejos y preguntas. Actualmente existen réplicas en 34 países alrededor del mundo.

Existe otra serie de beneficios asociados al desarrollo de OHW, relacionados con la sustentabilidad del actual sistema de producción y consumo. Algunos autores consideran la posibilidad de que se genere una disminución en el consumo a partir de una mayor conciencia sobre el desarrollo de los productos y su consecuente customización (Ivonov 2014), en lo que constituye una visión al menos controvertida del panorama.

Por otro lado, sí se observa un potencial real de alterar la obsolescencia programada de los productos provenientes del circuito de comercialización convencional, a partir de la transparencia de los diseños. Otro punto a remarcar es el potencial aumento de las tasas de reparabilidad de los objetos a partir de la intervención en el diseño y el conocimiento de ingeniería reversa -la obtención de información a partir de un producto ya terminado, a fin de determinar de qué está hecho, qué lo hace funcionar y cómo fue fabricado-.

Si a estas variables  -obsolescencia programada y tasa de reparabilidad- sumamos la visión de algunas organizaciones sobre el favorecimiento de la producción descentralizada y las cadenas cortas de comercialización, el desarrollo de OHW podría tener un potencial impacto positivo en el balance de materiales del sistema actual, reduciendo la generación actual de residuos electrónicos.

## Desafíos

Los principales obstáculos asociados al desarrollo de open hardware son la barrera de ingreso, que aún es alta en usuarios no familiarizados con electrónica -aunque ha mejorado a partir de la llegada de Arduino y la venta de toolkits-. Aunque existe una tendencia creciente a la modularización, proceso que facilita notablemente el acceso al desarrollo, aún no está muy extendida. Otro factor no menos importante que disminuye la tasa de generación de OHW tiene que ver, como se mencionaba anteriormente, con la dificultad de trabajar de forma interdisciplinaria a través de medios virtuales. Los procesos de documentación y tracking de cambios realizados por los usuarios aún no se encuentran totalmente naturalizados, con la consecuente dificultad de garantizar la replicabilidad en la que se basa la colaboración.

Además, la información virtual contenida en los archivos de diseño (set Gerber) hoy por hoy no encuentra una forma de vincularse concretamente a un objeto físico, dificultando la identificación de productos basados en OHW. En este sentido existen organizaciones que realizan esfuerzos para contrarrestarlo, a partir de iniciativas de etiquetado más o menos exitosas.

> **Box 4: RepRap**
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

Existen obstáculos a nivel empresarial y de tipo político: al día de hoy aún es necesario depender de un gran fabricante que pueda proveer los circuitos impresos. Algunos grandes fabricantes ven en el OHW una amenaza a su negocio -empresas que por ejemplo no quieren perder su capacidad para hacer obsolescencia programada de objetos-. En este sentido para el hardware se vuelve mucho más intrincado el problema de licencias y patentes, comparado con la industria del software.

En casos específicos como la ciencia y la educación, los principales obstáculos tienen que ver con la rigidez institucional: el tiempo que los científicos dedican a estos desarrollos aún no es visualizado como tiempo productivo por los sistemas de evaluación profesional, aunque comienzan a observarse iniciativas de revistas especializadas que podrían constituir un camino hacia la formalización y valoración de esos esfuerzos.

## Licencias

Las licencias disponibles hoy son las siguientes:

a) TAPR
La [Tucson Amateur Packet Radio](https://en.wikipedia.org/wiki/Tucson_Amateur_Packet_Radio) -TAPR, una organización internacional de radios amateur- definió el concepto de "hardware libre" en lo que constituyó el primer mecanismo de regulación de propiedad intelectual para este tipo de desarrollos. En esta licencia se lo define como “**una cosa -artefacto físico, ya sea eléctrico o mecánico- cuya información de diseño se encuentra disponible y utilizable por parte del público, de forma tal que permite a cualquier persona fabricarla, modificarla, distribuirla o utilizarla**” (TAPR, 2007).

b) Balloon     
c) HW Design Public      
d) Solderpad     
e) CERN OHL


## Políticas

Políticas de HW Libre en Venezuela

En otro documento FLOK, 2015 menciona para Ecuador a fin de fomentar la innovación social en materia de OHW:

Identificar oportunidades para la realización de las metas estratégicas nacionales y de un alto retorno de la inversión (ROI) en HL de uso científico.
Realizar una búsqueda activa de fondos para desarrollar HL. Esto se puede lograr con la combinación de recursos propios del Estado y medios tradicionales como subvenciones, concursos públicos, empresa privada, etc., así como los más recientes de crowdfunding y análogos.
Fomentar la economía popular a través de proyectos de innovación ciudadana basados en HL.
Proporcionar incentivos fiscales para que los empresarios del Ecuador comiencen a producir estos equipos. El gobierno aprobará políticas de adquisición preferencial para HL"hecho en Ecuador".

Baden 2015 hace referencia a recomendaciones de políticas, en su texto sobre OHWScience:
a) Incoporar open labware a curricula escolar
b) aumentar cursos hands on para cientificos y docentes
c) aumentar infraestructura para que todos tengan impresora 3d a mano (en universidades por ej)
d) incentivar a empresas a invertir en modelos abiertos de diseño de producto

***
## Bibliografía

Baden, T., Chagas, A. M., Gage, G., Marzullo, T., Prieto-Godino, L. L., & Euler, T. (2015). Open Labware: 3-D Printing Your Own Lab Equipment. PLoS Biology, 13(3), 1–12. http://doi.org/10.1371/journal.pbio.1002086

Berchon, M. (2013). The State of Open Hardware Entrepreneurship 2013. Retrieved from[ http://makingsociety.com/2013/09/the-state-of-open-hardware-entrepreneurship-2013/](http://makingsociety.com/2013/09/the-state-of-open-hardware-entrepreneurship-2013/)

Bordignon, F. R. A., & Iglesias, A. A. (2015). Diseño y construcción de objetos interactivos digitales: experimentos con la plataforma Arduino, 131.

Gautam, A., Bareja, D., Virdi, S. K., Shekar, S., & Verma, G. (2016). Implementaion of high performance home automation using arduino. Indian Journal of Science and Technology, 9(21), 1–5. http://doi.org/10.17485/ijst/2016/v9i21/94842

http://makingsociety.com/2011/03/zach-gage-conceptual-artist-and-arduino-enthusiast/

Pearce, J. M. (2014). Open-source Lab. How to Build Your Own Hardware and Reduce Research Costs.

Richard M. Stallman. (n.d.). Free Hardware and Free Hardware Designs. Retrieved from https://www.gnu.org/philosophy/free-hardware-designs.html

Valera, A., Soriano, A., & Vallés, M. (2014). Plataformas de Bajo Coste para la Realización de Trabajos Prácticos de Mecatrónica y Robótica. RIAI - Revista Iberoamericana de Automática E Informática Industrial, 11(4), 363–376.

Rubow, E. (2008). Open Source Hardware. Journal Article.

Society, B. C.-F. (2015). Hardware - Ecosistemas de innovación y producción basados en hardware libre. Journal Article.

McNamara, P. (2007). Open Hardware. TIM Review. Journal Article.

Raymond, Eric S. (1997). The Cathedral and the Bazaar: Musings on Linux and Open Source by an Accidental Revolutionary. O'Reilly Media.

Powell, A. (2012). Democratizing production through open source knowledge: from open software to open hardware. Media, Culture & Society, 34(6), 691–708. Journal Article.

Himanen, P. (2001). The Hacker Ethic and the Spirit of the Information Age. Max Weber Studies.

Coleman, E. G., & Golub, a. (2008). Hacker practice: Moral genres and the cultural articulation of liberalism. Anthropological Theory, 8(3), 255–277.
