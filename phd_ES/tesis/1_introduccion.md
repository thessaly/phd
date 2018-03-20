# Capítulo 1 - Introducción: FOSH ó Tecnologías libres

El concepto de software libre o como se denomina formalmente, Free Open Source Software -FOSS-, ya no resulta extraño para la mayoría de las personas en el siglo XXI. Sin embargo, el salto hacia el hardware libre, o diseño abierto de objetos, resulta aún complejo. En la última década, particularmente a partir de la disminución en los costos de los componentes electrónicos y la aparición de kits que minimizan la barrera de acceso al diseño de objetos con partes electrónicas, se produjo un boom de proyectos basados en Free Open Source Hardware -FOSH- (Berchon, 2013).

Al mirar el panorama de las comunidades que se encuentran desarrollando herramientas bajo los estándares libres o abiertos, el primer rasgo que salta a la vista es la heterogeneidad. Las motivaciones detrás de estos "hacedores" son diversas, abarcando un amplio espectro que va desde la figura del inventor hobbista y la tradición del “hágalo usted mismo” hasta comunidades con una orientación política claramente definida, anclada en el autonomismo, el mediactivismo y la ética hacker surgida en los 60-70 en el ámbito del MIT y la prehistoria de internet (Maxigas, 2012; Powell, 2012), pasando por nuevos “emprendedores” y corporaciones que comienzan a asimilar el modelo de apertura en los objetos físicos.

Varios autores consideran a la producción libre/abierta como un movimiento que puede llegar a cambiar las reglas del mercado de objetos de consumo como lo conocemos hoy: una visión de la producción distribuida, sin necesidad de depender de los grandes fabricantes tradicionales, creando cadenas de comercialización más cortas con insumos disponibles localmente (Powell, 2012; Cicero, 2013; Ivonov, 2014). Otros autores en cambio predicen un rumbo menos disruptivo, más similar al que tomó el software libre a partir de la llegada del código abierto y su inserción en las grandes corporaciones. ¿Cuáles son las implicancias de este nuevo modelo de producción en áreas tan diversas como ser educación, salud, ciencia, modelos de negocio? ¿Cómo regular estas nuevas formas de fabricación? ¿Deberían ser reguladas?

Este documento tiene la intención de reunir y discutir la literatura disponible sobre FOSH, a través de un hilo imaginario que conecta las distintas etapas de desarrollo de un proyecto de estas características. Comienza entonces con las distintas definiciones que hacen al concepto de hardware libre, para luego pensar qué razones movilizan a las personas a diseñar estos proyectos, cómo lo hacen, cuáles son los contextos más favorables para hacerlo, cuáles son los campos de aplicación donde surgen mayoritariamente y por qué, y finalmente qué beneficios y qué obstáculos se presentan en el camino, tanto en términos individuales como colectivos.

En líneas generales, la literatura aborda estas cuestiones desde el análisis de casos, siendo menor la cantidad de autores que realizan análisis sobre cuestiones de políticas o filosóficas del movimiento. Sin embargo podemos distinguir dos orientaciones a la hora de abordar la temática del FOSH: por un lado una visión más amplia, relacionada al concepto de información y conocimiento como bien común, que contempla el diseño abierto como una alternativa a las formas actuales de producción; una alternativa que permitiría el empoderamiento de las comunidades para solucionar sus problemas locales y equilibrar las diferencias de poder actuales (FLOK, 2012; Quilley, Hawreliak y Kish, 2016). Por otro lado, es evidente la existencia de una visión enfocada en los beneficios concretos que aporta la utilización de FOSH en términos de eficiencia, un lenguaje más cercano al ámbito de los negocios, a la idea de emprendedurismo y democratización de la innovación en el ámbito industrial (Raymond, 1988; Cicero, 2013; Benichou y Tincq, 2014).   

## ¿Qué?

La [Tucson Amateur Packet Radio](https://en.wikipedia.org/wiki/Tucson_Amateur_Packet_Radio) -TAPR, una organización internacional de radios amateur- definió el concepto de "hardware libre" en lo que constituyó el primer mecanismo de regulación de propiedad intelectual para este tipo de desarrollos. En esta licencia se lo define como “**una cosa -artefacto físico, ya sea eléctrico o mecánico- cuya información de diseño se encuentra disponible y utilizable por parte del público, de forma tal que permite a cualquier persona fabricarla, modificarla, distribuirla o utilizarla**” (TAPR, 2007). El término, que en inglés puede prestarse a confusión, no implica la gratuidad del desarrollo, sino la libertad (“*free as in freedom”*) para que los usuarios puedan acceder a la información necesaria para replicar el objeto, modificarlo y distribuirlo.

Uno de los aspectos principales en la definición de hardware libre viene dado por la extrapolación a partir del software: se lo define por extensión del "FOSS" -por Free Open Source Software-, término utilizado pragmáticamente para englobar tanto al Movimiento de Software Libre como al Software de Acceso Abierto, que si bien comparten modelos de desarrollo similares, tienen diferencias en sus aspectos filosóficos. El software libre se enfoca en las libertades filosóficas que les otorga a los usuarios mientras que el software de código abierto se basa en las ventajas de su modelo de desarrollo. Esto tiene implicancias en sus prácticas: no todo el software de código abierto es libre, aunque sí todo el software libre es necesariamente de código abierto.

Algunos autores (McManara, 2007; Pearce, 2014; FLOK, 2012; Rubow, 2008) utilzan las cuatro libertades definidas por la [Free Software Foundation](https://www.gnu.org/philosophy/free-sw.es.html) (FSF) para enmarcar al hardware libre: libertad de uso, de estudio y modificación, de distribución, y de redistribución de las mejoras. Estos cuatro principios fueron generados por el Movimiento del Software Libre en los ‘80-’90, identificado con la figura de Richard Stallman y el Proyecto GNU, concebido en 1983 como un modo de retomar el espíritu cooperativo que prevalecía en la comunidad informática en sus comienzos y posibilitar la cooperación eliminando los obstáculos impuestos por los dueños de software privativo. Este proyecto político inicial se diferencia de una corriente surgida posteriormente dentro del ámbito del software libre, el Software de Código Abierto, más identificada con la figura de Linus Torvalds y el desarrollo comercial de Linux. Esta última hace foco en la democratización de la innovación generada por el hecho de que el código sea abierto y compartido, y en cómo ello vuelve más eficientes y eficaces los desarrollos, insertándose plenamente en la industria. Según Eric Raymond, históricamente esta última corriente fue ganando terreno, desplazando al concepto de Software Libre hacia los márgenes, orientando la comunidad hacia preceptos menos puristas o radicales y volviendo a los miembros con posturas anti-comerciales una minoría dentro del espectro (Raymond, 1997).

Estas heterogeneidades presentes en la comunidad de FOSS pueden también rastrearse en el FOSH, tanto en términos de  su concepción filosófica como de las comunidades de prácticas que participan y el tipo de actividades de conocimiento, productivas y de uso involucradas. Como se mencionaba en la introducción, dentro del mismo ámbito co-existen proyectos con un origen motivado por la ética hacker -más relacionada a la corriente del software libre- junto a desarrollos claramente orientados a nuevos modelos híbridos de negocio que aprovechan las ventajas de eficiencia que brinda el hardware libre -relacionados al concepto de acceso abierto-.

>**Box 1: Arduino**  
>  
>Arduino es una plataforma de prototipado libre compuesta por una placa electrónica de entradas y salidas simple y un entorno de desarrollo que utiliza un lenguaje de programación fácil de usar. Los diseños del hardware y el software se encuentran liberados bajo licencia Creative Commons CompartirIgual 2.5 (Share-A-Like), lo que habilita a compartir, adaptar e incluso distribuir comercialmente los objetos creados en base a Arduino, siempre y cuando se indiquen las modificaciones realizadas y se mantenga el mismo tipo de licencia. Arduino funciona además como "marca", ya que se comercializan placas oficiales que pagan por llevar el nombre Arduino y otras que no y se definen como “Arduino-compatibles”.
>
> En su origen, Arduino fue pensado por un equipo de cinco personas en el Ivrea Interaction Design Institute en Turín, Italia, con el objetivo de contar con una herramienta sencilla de utilizar para estudiantes, que les permitiera fabricar objetos sin tener que contar con conocimientos avanzados de electrónica. Actualmente, además de la plataforma, Arduino es una comunidad organizada alrededor de su sitio web, donde más de 300 mil usuarios de distintas partes del mundo comparten sus diseños, recomendaciones y preguntas.
>
>![reprap](https://upload.wikimedia.org/wikipedia/commons/f/f8/Reprap_Darwin.jpg)    
>_Fig. 1: Versión 1.0 (Darwin) de RepRap, la impresora 3D autorreplicable basada en Arduino (Fuente: Wikipedia)_
>
>Arduino posee algunas ventajas que lo volvieron una de las ‘estrellas’ del hardware libre, viralizando su uso en cientos de proyectos a escala global y motorizando así la nueva ola del movimiento maker. Los atributos que destacan en Arduino son, principalmente: bajos costos -la placa más sencilla cuesta menos de 25 dólares-, compatibilidad en todos los sistemas operativos -Windows, Macintosh, Linux-, utilizar un lenguaje de programación simple para los novatos pero con funcionalidades potentes para los expertos, y la posibilidad de contar con código abierto tanto en software como hardware, posibilitando el intercambio entre usuarios y sumando modificaciones y nuevas funcionalidades en base a experiencias de otros.
>
>Arduino es empleado, entre otros usos, para crear instrumental de laboratorio económico y adaptado a las necesidades de los científicos
>(Baden et al, 2015; Pearce, 2012), por docentes para enseñar programación y robótica a estudiantes (Bordignon, 2015; Valera et al, 2014), por músicos y artistas para experimentar y realizar nuevas instalaciones (Juan Cortés; Zach Gage), por ingenieros y diseñadores para prototipar nuevos artefactos (Gautam et al, 2016; Karvinen y Karvinen, 2011) y por ejemplo, construir dispositivos de accesibilidad -como anteojos o calzado para no videntes-.

Definir al hardware libre como una extensión del FOSS genera algunas controversias. El mismo Richard Stallman (Stallman, 2015) declaró que los principios del software libre pueden aplicarse a los diseños, esquemáticos, ficheros y demás información que forma parte de la creación de un objeto, pero que no sería posible aplicar estos principios al circuito físico en sí mismo. Toda la literatura coincide en que éste es el punto más difícil de conciliar (González y Gómez-Arribas, 2003; Rubow, 2008; McManara, 2007; FLOK, 2015), ya que mientras que los desarrollos de software libre sortean la barrera material -toda la información está contenida en código digital que puede ser modificado sin más medios que una computadora-, diseñar y fabricar un objeto implica dar un salto hacia el mundo concreto de las cosas, generando un artefacto único en un espacio específico. Dentro del universo de artefactos a replicar también existen diferencias: algunos objetos son más fácilmente replicables que otros, algunos diseños están explícitamente fabricados bajo la premisa de que puedan armarse ‘en casa’ ([Pinguino](http://www.pinguino.cc/) y ReDuino).

Aunque el concepto de FOSH hace referencia al hardware - es decir las partes físicas tangibles de un sistema informático; sus componentes eléctricos, electrónicos, electromecánicos y mecánicos- resulta pertinente remarcar que el universo de objetos que están siendo "liberados" no sólo contempla sistemas informáticos. La cultura libre se expande también a la socialización de los diseños de objetos mecánicos, muebles, casas y otras herramientas que no necesariamente incluyen componentes electrónicos para funcionar. Es por esto que algunas comunidades comienzan a utilizar el término [“tecnologías libres”](https://forum.openhardware.science/t/1-sesion-latinoamericana-en-gosh-2017-resumen/330) a fin de ampliar las posibilidades de inclusión de nuevos desarrollos.

Por estas razones, en el campo de las tecnologías libres se plantea desde un inicio la necesidad de distinguir cuáles son los componentes que se abren -planos, esquemáticos, materiales- y se enfrentan desafíos distintos a los del software, especialmente en el ámbito de las licencias y de los costos de producción.

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

## ¿Por qué desarrollar hardware libre?

Una de las discusiones centrales en la literatura es la de entender por qué las comunidades desarrollan hardware libre, qué motivaciones encuentran para invertir tiempo y energía en proyectos que pueden -o no- monetizarse, o qué otro tipo de retribuciones reciben los colaboradores. En este sentido es imprescindible considerar que la heterogeneidad de comunidades de práctica hace que estas motivaciones sean muy variadas.

Dentro del ámbito de las tecnologías Libres/Abiertas, Powell (2008), Hertz (2011), Maxigas (2012) y Cuartielles (2013) identifican principalmente tres:

1. La ética hacker y los movimientos autonomistas/mediactivistas, condensados en el espacio de los hacklabs -explícitamente políticos-

2. Otra corriente sin una política abiertamente definida, relacionada a la cultura de acceso abierto y la defensa de los valores liberales más cercanos al Chaos Computer Club alemán, representados en los hackspaces;

3. Y por último la cultura del Do-it-yourself, más identificada con el movimiento maker/hobbysta

El primero de los casos se centra alrededor del espacio de los ‘hacklabs’. Yuill (2008) los define como "*[...] mayoritariamente, espacios voluntarios que proveen acceso público y gratuito a computadoras y a Internet. Usualmente hacen uso de máquinas recuperadas y recicladas que corren GNU/Linux y a la vez que proveen acceso a computadoras, la mayoría de los hacklabs tienen talleres funcionando en un rango de temas que van desde el uso básico de la computadora e instalación de software GNU/Linux, hasta programación, electrónica y radiodifusión independiente (o pirata). Los primeros hacklabs se desarrollaron en Europa, usualmente surgiendo de tradiciones de centros sociales okupados y media labs comunitarios. En Italia se les relaciona con los centros sociales autonomistas y en España, Alemania y en los Países Bajos con movimientos de okupación anarquistas"*. Los movimientos autonomistas tomaron un rol de relevancia en los años 70 en Italia, Alemania y Francia, bajo la premisa de que la clase trabajadora podía ser un actor histórico independiente ante el Estado y el Capital, construyendo sus propias estructuras de poder a través de la auto-valorización y apropiación, entre otras cosas, de los espacios.

La mayoría de los hacklabs funcionan en espacios ocupados, una de las prácticas características autonomistas que atravesó fuertes resistencias en Europa durante los años ‘90 y consiguió algunas conquistas en los años posteriores (Usher, 2010). En la génesis de los hacklabs, Maxigas (2012) identifica también al mediactivismo, tendencia que puede rastrearse en las prácticas de las radios piratas de los ’60 hasta los conflictos de copyright contemporáneos protagonizados por Pirate Bay. Las comunidades de radios piratas fueron evolucionando con el surgimiento de tecnologías emergentes y el acceso masivo a internet, con el propósito de generar comunicación alternativa, apuntando a bajar las barreras para la participación de la producción cultural y tecnológica conjuntamente con establecer una infraestructura de comunicación distribuida para organizaciones anticapitalistas. Como tales, tuvieron un rol importante en el surgimiento del movimiento de globalización alternativa: algunas iniciativas populares en este sentido fueron Indymedia, OrfeoTV y en menor medida Telestreet -donde participaba el filósofo italiano Franco Bifo Berardi-.

Los hacklabs, espacios ocupados de confluencia entre mediactivistas y okupas (Ultralab en Roma, Hackney Crack House en Londres) contienen

Esta historia arrastra una serie de consecuencias. Primeramente, que los hacklabs encajaban orgánicamente en el ethos anti-institucional cultivado por la gente en los espacios autónomos. En segundo lugar, estaban incrustados en el régimen político de los espacios y eran sometidos a las mismas formas de frágil soberanía política que dichos proyectos desarrollaron. Tanto Forte Prenestino y Mare Street han escrito y desescrito formas de comportarse que se esperaba que las usuarias siguieran. Esta última okupación había promocionado "políticas de lugares más seguros", declarando por ejemplo que la gente que exhibía comportamientos sexistas, racistas o autoritarios debiera esperar ser confrontada y si fuese necesario, excluida. En tercer lugar, la lógica politizada de las okupaciones y mas específicamente la ideología detrás del anarquismo apropiativo, tuvo también sus consecuencias.Por último, el estado de okupación fomenta un ambiente de complicidad. Consecuentemente, ciertas formas de ilegalidad son vistas como al menos necesarias, o algunas veces hasta deseables

primer lugar, existen comunidades que desarrollan tecnologías libres motivadas por lo que varios autores denominan "**ética hacker**" (Powell, 2008; Coleman, 2008; Himanen, 2001). Surgida en el ámbito del MIT en los años 60-70, fue descrita por Steven Levy en 1984 en lo que se considera un clásico de la era dorada del hacking, “*Hackers: Heroes of the computer revolution*”. Levy menciona los siguientes principios como pilares de la ética hacker: libertad de la información, meritocracia, desconfianza de la autoridad y la creencia de que puede construirse un mundo mejor y más bello utilizando computadoras. La discusión acerca de qué es la libertad o qué es ser libre se encuentra en la base de la filosofía hacker, razón por la cual Coleman y Golub (2008) remarcan su cercanía a las ideas del liberalismo. Los conceptos liberales de libre albedrío, libertad de expresión, el individuo, la privacidad y la meritocracia son frecuentemente invocados por la comunidad: “*Creemos en la libertad de expresión, en el derecho a explorar y aprender haciendo, y en el tremendo poder del individuo*” declara una editorial hacker ([Revista 2600](https://www.2600.com/)).

Sin embargo, esta tendencia liberal convive con prácticas heterogéneas y conceptos que aparentemente son contradictorios. Esto es particularmente notorio en el caso del movimiento de software libre, que plantea la noción del conocimiento como un bien común del cual la comunidad se beneficia, considerando que privatizar el acceso a la información constituye un acto antiético, ya que permite a los individuos beneficiarse a expensas de la comunidad. Sus principios sobre garantizar el libre acceso a la información, la reciprocidad, el compartir y la apertura científica, fueron expresados por Stallman al formar el Free Software Movement en 1984 a partir de su trabajo en el MIT. Es por ello que Stallman desarrolla GPL, la licencia pública GNU a fin de crear una "zona segura" para evitar que las corporaciones privaticen el desarrollo de software a través de licencias de propiedad intelectual. Esta preocupación por el libre acceso a la información en el caso del software puede rastrearse hasta el hardware libre, particularmente en las discusiones abiertas acerca de si es posible garantizar el libre acceso a la información contenida en todos los componentes de un objeto, o sólo en algunos. Dentro de este grupo de motivaciones podemos mencionar al **Proyecto RepRap**, **Precious Plastic** o el **Global Village Construction Set**.

Por otro lado, existe un grupo de iniciativas cuyas motivaciones se basan en las ventajas relacionadas a la eficiencia y los posibles modelos de negocio que se habilitan a partir de la aparición del hardware libre. El origen de estas motivaciones puede remontarse a 1998, cuando fue acuñado el término "open source software" -software de código abierto-. Esta variante surge del Movimiento de Software Libre, como mencionamos en la introducción, pero  haciendo hincapié en en la eficiencia del modelo de desarrollo colaborativo del código abierto para crear las mejores soluciones a un problema determinado. Eric Raymond, uno de sus máximos exponentes, argumenta que “*el disfrute obtenido por programar y la reputación ganada por hacerlo bien son mejores incentivos para producir software que un salario*”. El libre acceso a la información sigue siendo una preocupación en este caso, pero el énfasis no está puesto en formar una comunidad con valores y normas comunes, sino en que la mejor manera de obtener el mejor desarrollo es a través de un mercado eficiente donde el incentivo para concretarlo sean la motivación y reputación individuales de los programadores -que sólo pueden ser garantizadas con el acceso abierto al código-. En este sentido se ubican varios de los desarrollos más importantes dentro del Hardware Libre, un punto de inflexión que Cuartielles (2013) señala como “estar cometiendo los mismos errores que se cometieron en el ámbito del Software Libre a principios de los ‘80”. Empresas como **Makerbot **-pionera en el desarrollo de impresoras 3D que aprovechó innovaciones realizadas por la comunidad RepRap- o **3D Robotics** -que provee drones a bajos precios- comenzaron siendo desarrollos de hardware libre que actualmente cierran parte de su proceso para evitar “ser copiados por terceros”. El mismo Cuartielles, parte del equipo creador de Arduino, argumenta que la apertura total en hardware no es posible, pero que un giro hacia el acceso abierto en lugar del hardware libre no beneficiaría a la comunidad, si no a las corporaciones. Las motivaciones que motorizan a este grupo son aquellas relacionadas a la capacidad de volver rentable la apertura: difundir un objeto de diseño abierto implica menores costos, mayor uso por parte de la comunidad y por lo tanto mayor publicidad, mayor tasa de innovación, capitalización de las mejoras públicas en términos privados y posibilidad de contar con una comunidad que da soporte ante posibles fallas o problemas en el diseño. A nivel comunidad cuentan con asociaciones como la **Open Source Hardware Association**,  que organiza anualmente el Open Hardware Summit y otras asociaciones enfocadas principalmente en cuestiones de licencias.

Finalmente, se puede identificar dentro del campo del HW Libre a una comunidad claramente definida como "movimiento maker" con una fuerte influencia de la cultura del **Hágalo Usted Mismo** (“Do it yourself” o DIY). Resulta útil en este punto la distinción que Hertz (2011) realiza sobre DIY utilitario y DIY hedonista. El primero responde a la necesidad de construir objetos con los materiales disponibles, muchas veces escasos o inapropiados, para resolver problemas de la vida cotidiana. Por ejemplo, el productor agropecuario que cuando ve que se rompe una maquinaria intenta reemplazar la funcionalidad perdida con otros implementos, o el científico que en un laboratorio sin recursos desarrolla métodos alternativos para llegar a sus resultados. Sin embargo, esta motivación -la necesidad- no es la que caracteriza al “maker”, o al menos no al que predomina en los países desarrollados y las comunidades establecidas. La comunidad maker estaría más motivada por un tipo de DIY hedonista, ligado a la creciente disponibilidad y bajos costos de componentes electrónicos -como Arduino (ver Box 1)- que permiten construir artefactos de consumo personalizados. En este último caso, la utilidad o la significancia del producto se ve opacada por la satisfacción que genera hacerlo.

Según Mark Frauenfelder -editor jefe de la revista MAKE, de referencia para el sector- las motivaciones de la comunidad maker responden a una insatisfacción con la cultura del consumo y del descarte, y a una revalorización del concepto japonés de *wabi-sabi* o la "*apreciación de la imperfección de los objetos*" (Suzuki, D.1959). Hertz suma a esto la motivación generada por reacción a la cultura de la caja negra (“black box”) típica de la fabricación en la era digital: la velocidad de las innovaciones en materia de tecnología implica que los objetos de consumo estén producidos basándose en componentes y procesos complejos. No es posible para el usuario comprender su lógica interna sino sólo el resultado de su funcionamiento, incluso siendo experto. Cuando un objeto se rompe o queda obsoleto, se vuelve inutilizable y genera dependencia de los fabricantes, lo cual es altamente frecuente dados los paradigmas de obsolescencia programada dominantes en la industria. Reemplazar partes es casi imposible para los consumidores, dada la alta especialización de la ingeniería y fabricación que el objeto conlleva. Este rol pasivo de los consumidores genera una reacción por parte de la comunidad DIY, que construye objetos de consumo con componentes simples y compartiendo información, algo que Frauenfelder engloba en el concepto de “vivir auténticamente”.

A nivel de comunidad, los "makers" cuentan con reuniones y exposiciones anuales -Maker Faire-, el desarrollo de un mercado cada vez más importante de componentes y kits electrónicos de fácil utilización (Powell, 2012) y la existencia de la revista MAKE, una especie de continuo de la revista Popular Mechanics de mediados del siglo XX, orientada a la clase media y las actividades hobbistas de tiempo libre. El papel de MAKE no es menor: varios autores le asignan el rol de moldear y normativizar el rumbo que toma la comunidad en base a las prácticas que se difunden a través de la misma.  

## ¿Cómo se hace FOSH?

Una de las principales cuestiones que la literatura analiza es la diferencia entre el proceso de desarrollo del software y el de hardware. Mientras la virtualidad del software facilita la colaboración sin mediar distancias en un proceso bastante directo entre usuarios, la materialidad inherente al desarrollo de hardware implica que éste requiera de instancias discretas y potencialmente independientes de trabajo. Como se ve en algunos estudios de caso, esto determina cuellos de botella particulares, asociados principalmente al multi-expertise requerido para modificar un objeto y a la existencia de patentes en los objetos físicos. Al respecto, algunas organizaciones han comenzado a documentar protocolos de desarrollo de OSH, a manera de guías de buenas prácticas (Cenditel) o describiendo procesos exitosos (Ackermann, 2009).

Los pasos necesarios para construir hardware electrónico han ido mutando hacia formas automatizadas en los últimos años. Sin embargo aún se precisa contar con ciertos conocimientos y herramientas específicos.

Un primer paso consiste en obtener un **diagrama esquemático**, es decir un gráfico donde se especifican los componentes electrónicos (resistencias, capacitores, circuitos integrados)  a utilizar y sus conexiones, a través de un sistema de símbolos. En caso de ser necesario también se indica información sobre valores de cada componente (por ejemplo una resistencia de 10-kilohm). Sin embargo el esquemático no posee toda la información necesaria para fabricar una plaqueta de circuito impreso.

![esquemático](https://upload.wikimedia.org/wikipedia/commons/thumb/7/76/4_bit_counter.svg/1280px-4_bit_counter.svg.png)
_Fig. 3: Ejemplo de diagrama esquemático de un contador TTL (Fuente: Wikipedia)_

En la actualidad, todos los objetos electrónicos se fabrican utilizando plaquetas de circuito impreso, a diferencia del sistema de cableado punto a punto utilizado hasta los años 60. Los circuitos impresos aportaron un nivel mucho mayor de automatización en la fabricación: se eliminó el cableado, ya que las conexiones, constituidas por líneas de cobre, se encuentran integradas en un soporte no conductor -generalmente epoxy- que además sostiene los componentes. Esto permitió no sólo reducir el espacio que ocupa el circuito sino también integrar el uso de microchips, el corazón de las tecnologías como teléfonos móviles, computadoras, tablets y más.

![pcb](https://upload.wikimedia.org/wikipedia/commons/thumb/6/67/PCB_design_and_realisation_smt_and_through_hole.png/1024px-PCB_design_and_realisation_smt_and_through_hole.png)
_Fig 4: ejemplo de diseño digital de circuito impreso (izq.) y circuito final (der.) (Fuente: Wikipedia)_

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
>![Global village construction set](http://opensourceecology.org/w/images/thumb/9/90/GVCS.jpg/762px-GVCS.jpg)    
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


## Obstáculos

Los principales obstáculos asociados al desarrollo de open hardware son la barrera de ingreso, que aún es alta en usuarios no familiarizados con electrónica -aunque ha mejorado a partir de la llegada de Arduino y la venta de toolkits-. Aunque existe una tendencia creciente a la modularización, proceso que facilita notablemente el acceso al desarrollo, aún no está muy extendida. Otro factor no menos importante que disminuye la tasa de generación de OHW tiene que ver, como se mencionaba anteriormente, con la dificultad de trabajar de forma interdisciplinaria a través de medios virtuales. Los procesos de documentación y tracking de cambios realizados por los usuarios aún no se encuentran totalmente naturalizados, con la consecuente dificultad de garantizar la replicabilidad en la que se basa la colaboración.

Además, la información virtual contenida en los archivos de diseño (set Gerber) hoy por hoy no encuentra una forma de vincularse concretamente a un objeto físico, dificultando la identificación de productos basados en OHW. En este sentido existen organizaciones que realizan esfuerzos para contrarrestarlo, a partir de iniciativas de etiquetado más o menos exitosas.

> **Box 4: RepRap**
>
>La construcción de una impresora RepRap constituye muchas veces uno de los primeros momentos de aprendizaje de los entusiastas de la fabricación digital.  
>
>De forma similar a Linux, RepRap comenzó en 2005 como un proyecto universitario del Dr. Adrian Bowyer de la Universidad de Bath, con el objetivo de construir una impresora auto-replicable. Es decir, una impresora que pudiera imprimir las partes para construir una nueva impresora. A partir de la colaboración online en blogs y wiki, los usuarios fueron construyendo copias del primer prototipo, realizando modificaciones que documentaban y ponían a disposición online.
>
>![reprap Mendel](https://upload.wikimedia.org/wikipedia/commons/c/c7/RepRap_%27Mendel%27.jpg)    
>_Fig. 8: RepRap 2.0, versión Mendel (Fuente: Wikipedia)_
>
>Uno de los disparadores del boom de la impresión 3D ha sido la expiración de las patentes de los equipos originales de impresión (The Economist 2013), creados en la década de los ochenta. Por ejemplo, en 2009 expiró la patente del proceso de modelado por deposición fundida (conocidas como FMD por su sigla en inglés) que utiliza filamentos plásticos. La caída de las patentes permitió una explosión de experimentación con nuevas impresoras, de la cual surgió RepRap, que utilizando el modelo open source permite que cualquier usuario realice modificaciones y mejoras en las máquinas. Desde ese momento, la impresoras 3D FDM se convirtieron en un objeto de escritorio y su costo se redujo hasta menos de los mil dólares en los modelos fabricados por los usuarios (Mins 2013).
>
>En 2011 nació el grupo conocido como "Clone Wars" dentro de la comunidad RepRap, con el fin de documentar en español todo lo necesario para que cualquier persona pueda construir su propia impresora 3D.

Existen obstáculos a nivel empresarial y de tipo político: al día de hoy aún es necesario depender de un gran fabricante que pueda proveer los circuitos impresos. Algunos grandes fabricantes ven en el OHW una amenaza a su negocio -empresas que por ejemplo no quieren perder su capacidad para hacer obsolescencia programada de objetos-. En este sentido para el hardware se vuelve mucho más intrincado el problema de licencias y patentes, comparado con la industria del software.

En casos específicos como la ciencia y la educación, los principales obstáculos tienen que ver con la rigidez institucional: el tiempo que los científicos dedican a estos desarrollos aún no es visualizado como tiempo productivo por los sistemas de evaluación profesional, aunque comienzan a observarse iniciativas de revistas especializadas que podrían constituir un camino hacia la formalización y valoración de esos esfuerzos.

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
>![preciousplastic](https://scontent.faep11-1.fna.fbcdn.net/v/t1.0-9/13166073_934169426680288_9203599104270471372_n.jpg?oh=7fb980b2495f858b97aefe43811804de&oe=5B4485DF)
>_Fig. 9: Set de máquinas que integran el proyecto: trituradora, extrusora, una máquina de inyección y una compresora (Fuente: comunidad Precious Plastic en Facebook)._
>
>El proyecto se difundió principalmente a través de un video en Facebook, en el cual Hekkens explica los conceptos detrás del mismo y solicita difusión. La comunidad se aglutina alrededor de un foro web (www.preciousplastic.com) donde se intercambian consejos y preguntas. Actualmente existen réplicas en 34 países alrededor del mundo.

Existe otra serie de beneficios asociados al desarrollo de OHW, relacionados con la sustentabilidad del actual sistema de producción y consumo. Algunos autores consideran la posibilidad de que se genere una disminución en el consumo a partir de una mayor conciencia sobre el desarrollo de los productos y su consecuente customización (Ivonov 2014), en lo que constituye una visión al menos controvertida del panorama.

Por otro lado, sí se observa un potencial real de alterar la obsolescencia programada de los productos provenientes del circuito de comercialización convencional, a partir de la transparencia de los diseños. Otro punto a remarcar es el potencial aumento de las tasas de reparabilidad de los objetos a partir de la intervención en el diseño y el conocimiento de ingeniería reversa -la obtención de información a partir de un producto ya terminado, a fin de determinar de qué está hecho, qué lo hace funcionar y cómo fue fabricado-.

Si a estas variables  -obsolescencia programada y tasa de reparabilidad- sumamos la visión de algunas organizaciones sobre el favorecimiento de la producción descentralizada y las cadenas cortas de comercialización, el desarrollo de OHW podría tener un potencial impacto positivo en el balance de materiales del sistema actual, reduciendo la generación actual de residuos electrónicos.

## Los usos del OSH

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
>![syringe-pump open source](http://www.appropedia.org/images/0/08/Double-pump.jpg)    
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
>_Fig. 10. Las explicaciones siguen un criterio lógico que permite al estudiante ir probando si su desarrollo es o no exitoso._
>
>**FALTA IMAGEN**    
>A medida que el desarrollo del juguete va requiriendo mayores capacidades, las instrucciones van entrando en mayor detalle: valores de verdad y condiciones lógicas, sentencias de programación específicas, etc.
>
>**FALTA IMAGEN**    
>_Fig. 11. El funcionamiento del minipiano puede chequearse online vía Youtube._

Otra rama de la educación donde comienza a evidenciarse el potencial del OSHW, cercano a la robótica, es en el diseño de sistemas embebidos. Un sistema embebido es una combinación de hardware y software que trabaja junto con algún sistema mecánico o electrónico diseñado para cumplir una función específica. Por lo tanto, se usa para dotar de "inteligencia" a un artefacto, por ejemplo electrodomésticos. Miles de millones de microprocesadores se fabrican por año en el mundo, sin embargo 99% de ellos permanece invisible para los consumidores, siendo su destino los sistemas embebidos.

En este ámbito se puede observar una motivación cercana al movimiento *maker*, relacionada a la corriente del aprendizaje construccionista y su leitmotiv de "aprender haciendo", basada en las ideas de John Dewey, Maria Montessori, y Jean Piaget. Los educadores que adhieren a esta orientación plantean que enseñar en la práctica el uso del hardware y su intervención permite tener una perspectiva más amplia sobre el funcionamiento de las tecnologías digitales y deja de lado la visión de los objetos cotidianos como cajas negras cerradas y mágicas para pasar a percibirlos como resultado de un diseño premeditado. Además, hacen hincapié en la valoración del error como método de aprendizaje, generando un espacio seguro donde los estudiantes pueden tomar información a partir de experimentos fallidos.

En el ámbito local es importante mencionar el trabajo de Bordignon e Iglesias, donde proponen una serie de experimentos basados en Arduino para aplicar en clase. Trabajando con sistemas embebidos, detallan la información necesaria para que en distintos niveles del ciclo educativo los estudiantes puedan desarrollar desde un semáforo o un termómetro hasta juegos con electrónica de mayor complejidad (ver Box 7).

#### Negocios

La explosión del OSHW abrió la puerta a múltiples modelos de negocio que utilizan parcial o totalmente la apertura como estrategia de monetización. Según un informe sobre el estado de situación de los emprendimientos OHW (Berchon. 2013), la mayoría se encuentran en los Estados Unidos (68%) -concentradas en los núcleos de desarrollo de hardware alrededor de las universidades y hackerspaces activos- seguido por Europa (19%) y Asia (7%). Sin embargo el rasgo más llamativo es que la mayoría de las iniciativas funcionan completamente online, siendo la colaboración, distribución y comunicación virtuales, por lo que la ubicación no sería un factor determinante para este tipo de emprendimientos.

Gran parte de las compañías basadas en OHW trabajaban en 2013 en el rubro de electrónica para hobbistas y educación (63%); muchas de ellas inspiradas por el éxito de modelos como Arduino o Raspberry Pi, desarrollando kits y placas compatibles. La segunda posición es para las herramientas de fabricación (15%), más específicamente impresión 3D (11%). El resto del mercado se encuentra fragmentado en nichos específicos: drones (3%), iluminacion (3%), sintetizadores de sonido (2%).

Hasta el año 2007 se lanzaba sólo una compañía OHW por año: ejemplos de ello son Parallax (1986), Solarbotics (1994), Lynxmotion (1995, luego comprada por RobotShop), ShopBot (1996), Egnite (1997), WIZnet (1998). Pero a partir de 2007 el número crece rápido -ver figura 12-. En promedio toma a los emprendedores dos años pasar de la idea del proyecto a un producto definido.

**FALTA IMAGEN**    
_Fig. 12: número de empresas OHW lanzadas por año (Fuente: Berchon. 2013)*_

En cuanto al perfil de los emprendedores, mayoritariamente poseen una formación en ingeniería (83%), diseño (17%) -incluyendo artistas digitales con conocimientos en aspectos técnicos- y docentes e investigadores (14%) provenientes de áreas técnicas, que dedican su tiempo libre a trabajar en proyectos OHW. El 47% de las compañías es liderado por emprendedores solos, comparado con el 52% que lo hace en equipo, lo que la autora atribuye a la ventaja de contar con una comunidad online fuerte de apoyo. Sólo el 5% de las compañías son lideradas por mujeres -excepciones notables como Adafruit o LittleBits-, y sólo 10% las incluyen en los equipos fundadores, aunque sí participan en gran medida en hackerspaces, proyectos y eventos.

Más de la mitad de las compañías se financian con sus propios recursos (62%) aunque cada vez es mayor el número de empresas que se financian parcial o totalmente a partir de crowdfunding (28%).

>**Box 8: Adafruit**
>
>Adafruit Industries es una compañía basada en open source hardware ubicada en la ciudad de Nueva York, fundada en 2005 por la hacker e ingeniera Limor Fried mientras estudiaba en el Massachusetts Institute of Technology. La empresa diseña y fabrica una serie de productos electrónicos y vende un amplio rango de componentes, herramientas y accesorios vía su tienda web. Los productos ofrecidos abarcan rangos de principiante -kits que producen sonidos al recibir una señal- a experto -como sofisticados microcontroladores para celulares y desarrolladores de videojuegos-.
>
>![tapa wired](https://www.wired.com/wp-content/uploads/blogs/geekmom/wp-content/uploads/2011/03/Wired-Cover.jpg)    
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

![image alt text](https://i.pinimg.com/originals/85/c9/99/85c999a3b9c1a0541c68c52a217cbb81.png)

_Fig 14. Turbina eólica abierta de Tripalium, una fundación que promueve la energía eólica (Fuente: Tripalium.org)_

4. **Sistemas de Producto-Servicio**

Surgieron en 1959 con el modelo de impresión pay-per-copy instalado por Xerox, y están teniendo mayor difusión actualmente de la mano de conceptos como la economía social y la economía circular. Se basan en ofrecer el derecho de uso del producto en lugar de su propiedad. En OHW aún es incipiente, pero el autor aduce que posee potencial. Cicero agrega que las compañías podrían beneficiarse a partir de un ofrecer el software como servicio asociado a un producto OHW, especialmente en el caso de los sistemas embebidos y la Internet de las Cosas (IoT) -aunque alega que el mercado aún no posee la madurez suficiente para llegar a ese lugar-.

5. **Estandarización y ¿apalancamiento?!**

Consiste en abrir estratégicamente un producto clave que sea redituable en sí mismo pero que su apertura implique un impulso para que la tecnología asociada a él se convierta en un estándar de la industria. El ejemplo típico en este caso es el sistema operativo Android, de Google, y los motores Tesla, que permitieron a Tesla Motors incursionar en el mercado de las baterías y estaciones cargadoras.

6. **Modelos de plataforma**

Su valor radica en organizar un ecosistema de actores industriales (diseñadores, fabricantes, revendedores, consumidores, prosumidores, marcas, etc.) alrededor de una tecnología clave OHW o plataforma. Casos paradigmáticos: OpenDesk (ver Box 9) y OSVehicle. OSVehicle diseñó el motor y chasis Tabby -OHW, eléctrico y modular-. Construyeron una "cadena de valor participativa" donde el mismo se distribuye de manera justa entre todos los participantes.

> **Box 9: Open Desk**
>
>Opendesk se autodefine como una plataforma global para la producción local. Consiste en una herramienta de "producción abierta" que puede utilizarse para descargar, fabricar y comprar mobiliario. Cuenta con un catálogo de diseños específicamente realizados para la fabricación digital, por lo cual el objeto puede producirse localmente, de acuerdo a la demanda, en cualquier lugar del mundo.
>
>Cuánto de este proceso es realizado por el usuario depende un poco de sí mismo. Si se cuenta con la capacidad y herramientas para construir el diseño, se puede descargar y hacer el producto desde cero. En caso contrario, se puede contratar un maker desde la página, que fabricará el objeto para el cliente. Mientras mas trabajo se haga personalmente, mas bajo es el costo. Todo depende de donde se encuentre, si hay fabricantes locales disponibles y de si se tiene acceso a la maquinaria necesaria.
>
> ![escritorio](https://d2mgbjyendvdw0.cloudfront.net/02628/02973/5ee268/opendesk_furniture_lean-desk_design-listing-page_listing-image-image-side-all-ply_full_2.jpg)
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
>![solo](https://3dr.com/wp-content/uploads/2017/03/Solo_r10c-1024x443.jpg)
>_Fig. 16. Solo, el drone estrella de 3D Robotics (Fuente: 3Dr)_
>
>La empresa llegó a tener oficinas en la ciudad de San Diego y Berkeley en California, ventas y marketing en Austin, Texas y una planta de producción en Tijuana, Baja California, México, que producían alrededor de 15,000 pilotos automáticos al año, generando ganancias de alrededor de 20 millones de dólares anuales.
>
>La revista Forbes entrevistó a ex empleados de 3D Robotics que narraron cómo la competencia en precios de la compañía china DJI y los problemas internos impidieron que la empresa cumpliera aquella visión revolucionaria de sus inicios. Ya no producirá sus drones Solo, estrella de la compañía, despidió a más de 150 personas, gastó casi 100 millones de dólares de inversiones y lucha por sobrevivir con un fuerte cambio de modelo de negocio en que ahora se concentra en producir software. Muñoz dejó la empresa para fundar otra llamada mRobotics, también basada en San Diego, una abreviatura de Mayan Robotics.

Para el autor es esperable que aparezcan nuevos jugadores en el mercado de la producción de hardware que más allá de estar basados o no en la filosofía de apertura, aprovecharán la ventaja otorgada por la creciente modularización que el OHW trae a la industria -como hizo Google con el FLOSS-. Este escenario de fabricantes lo suficientemente elásticos en infraestructura sería compatible con un nuevo tipo de demanda, ágil, ultra customizada, orientada por la comunidad y a los prosumidores.

Según Cicero en los próximos años deberíamos poder observar transformaciones radicales en el concepto de "fábrica": la producción será descentralizada y potencialmente desvinculada de las marcas y fabricantes, acercándose al concepto defendido por FLOK sobre desarrollo endógeno y soberanía tecnológica. En este sentido Powell coincide con Cicero aunque resulta más escéptico respecto al beneficio social en otros aspectos -por ejemplo democratización en el acceso a la tecnología-. Ambos plantean que la inserción del modelo OHW en la industria traería ventajas relacionadas a la sustentabilidad al favorecer la desaparición de la obsolescencia programada en los productos de consumo .

Los principales obstáculos que se pueden identificar en el uso de OHW para modelos de negocio son los relacionados a las patentes -en muchos casos salvados por el dual licensing-, la falta de modularidad en los diseños actuales -que dificulta su intervención- y la necesidad de generar confianza en el consumidor acerca de la calidad de los productos de diseño abierto. Dependiendo del modelo de negocio analizado, si la orientación es hacia desarrollo de productos, el peso de la marca y el tamaño de la comunidad son factores limitantes: si la base es la producción entonces la oferta de un catálogo variado y renovado es un factor diferencial. En el caso de los modelos de licencia dual, algunos autores señalan que un obstáculo puede ser el lock in por parte de los usuarios con filosofía OHW, especialmente en el segmento profesional.

***
# Secciones pendientes

## Usos
#### Personalización del consumo - DIY

Pendiente

## Oportunidades - Enablers

(No sé si esta sección tendrá sentido. Es para poner algo sobre por qué pensamos que hay posibilidades para que el OH crezca. Por ejemplo rol de las TICs’ del crecimiento del OSS de las Comunidades de Práctica asociadas al OSS que allanaron el camino?, no sé). Por ahí algo de los textos sociales ayuda con esta parte

Acá se podría hablar de  la relación con el movimiento de software libre,  la creciente cultura DIY: como estas prácticas  impulsan la experimentación con nuevas  tecnologías. ETC. Un buen ejemplo  a retomar  es  el caso de Rep rap  en fabricación digital  para mostrar como las  impresoras open hardware  permitieron masificar  el acceso a la  nueva tecnología. Lo  mismo se podría decir con el caso de drones.

## Regulaciones y Licencias

Las licencias disponibles hoy son las siguientes:

a) TAPR
b) Balloon
c) HW Design Public
d) Solderpad
e) CERN

FLOK, 2015 elabora una serie de propuestas específicas para HW libre a fin de orientar hacia la sociedad del conocimiento.

La regulación debe prestar atención al hardware desarrollado bajo todo tipo de licencias, con el objetivo de que su expansión favorezca el crecimiento de la economía del conocimiento

1. Documentación. El hardware debe ponerse en circulación con docu- mentación que incluya archivos de diseño y debe permitir la modi- ficación y distribución de los mismos.

2. Alcance. La documentación del hardware deberá especificar clara- mente qué parte del diseño, si no todo, se libera bajo la licencia.

3. Programas informáticos necesarios. Si el diseño bajo licencia nece- sita de un paquete informático, éste debe liberarse bajo una licen- cia aprobada por la OSI (Open Source Initiative) o debe contar con suficiente documentación de su interfaz de programación.

4. Obras derivadas. La licencia deberá permitir modificaciones y obras derivadas y permitirá que éstas se distribuyan bajo los mismos tér- minos que la licencia de la obra original. La licencia permitirá la fa- bricación, venta, distribución y uso de productos creados a partir de los archivos de diseño, los archivos en sí mismos, y los derivados de cualquiera de los anteriores.

5. Libre redistribución. La licencia no podrá restringir a nadie de la venta o distribución de la documentación del proyecto. La licencia no podrá requerir el pago de derechos de autor por la mencionada venta. La licencia no podrá requerir ningún derecho de autor o tasa relacionada a la venta de obras derivadas.

6. Atribución. La licencia podría requerir que los documentos deriva- dos y notificaciones de derechos de copia (copyright) asociadas con los dispositivos atribuyan la autoría del/los autor/es licenciante/s a la hora de distribuir ficheros de diseño, bienes manufacturados y/o productos derivados de los mismos.

7. No discriminación a personas o grupos. La licencia no puede discri- minar ninguna persona o grupo de personas.

8. No discriminación a campos de aplicación. La licencia no puede restringir a nadie de hacer uso del trabajo (incluyendo el objeto manufacturado) en un campo específico de aplicación.

9. Distribución de la licencia. Los derechos proporcionados por la li- cencia deberán ser aplicados a todos aquellos a los que sea redistri- buido el trabajo sin la necesidad de ejecutar una licencia adicional.

10. Los derechos proporcionados por la licencia no dependen de que el trabajo licenciado sea parte de un producto determinado. Es decir, si una parte de una obra licenciada se usa y distribuye bajo los tér- minos de la licencia, todos aquellos a los que se les redistribuya la obra deberán tener los mismos derechos que proporcione la obra original.

11. La licencia no debe restringir otro hardware o software.

12. La licencia será neutra en términos tecnológicos.

También presentan recomendaciones:

1. Incluir [habilidades de] diseño dentro de las redes de innovación e incubadoras de negocio

2. Crear lineamientos, códigos de prácticas, marcos legales y espacios experimentales para promover el uso de open design

3. Aumentar el empleo de diseño o de diseñadores en la innovación dentro del sector público. Apoyar una mayor participación de diseñadores en espacios donde la innovación social y los servicios públicos representan retos críticos

4. Levantar el nivel de alfabetización en diseño para todos los ciudadanos, promoviendo una cultura del aprendizaje de diseño en los distintos niveles del sistema educativo

Y exigen medidas concretas más simples:
- Catalogo HW Libre
- Crear labs ciudadanos
- Oficina de evaluación de tecnologías libres para transicionar a sw y hw libre en el estado

Menciona como inspiración:
MobiStation (UNICEF Stories, 2013) es un prototipo abierto desarrollado por UNICEF Uganda en 2013 para mejorar la educación primaria. MobiSta- tion es un juego multimedia, alimentado por energía solar, complementa- do con un computador portátil, proyector y escáner, todos ellos conteni- dos en un maletín. Funciona proyectando libros electrónicos, vídeos didác- ticos y otros contenidos multimedia en las escuelas rurales y centros de sa- lud.

El computador portátil One Laptop Per Child está basado en software libre y es de consumo energético eficiente, con un coste cercano a unos cien USD, que en ocasio- nes se cubrían además desde contextos con mayor poder adquisitivo

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
