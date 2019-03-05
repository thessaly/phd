# El movimiento de hardware Científico de Código Abierto (GOSH) en América Latina: ¿Una alternativa democrática de producción tecnológica?

## Plan de gestión de datos 

### Recopilación de datos

Se recopilarán datos de cada iniciativa de hardware de ciencia abierta de América Latina que haya participado en cualquiera de las reuniones del movimiento de Hardware Científico de Código Abierto (GOSH) hasta ahora (2016, 2017, 2018).

Esto incluye información general sobre cada proyecto (nombre, ubicación, repositorios web, año de inicio, miembros, objetivos y visión, herramientas utilizadas, métodos de comunicación, recursos, actividades) y sobre sus miembros (nombre, frecuencia y tipo de colaboración, especialidad, nivel de educación).

**Las fuentes de datos incluyen:**

a) Disponible públicamente en repositorios en línea (sitio web de GOSH, OSF, Docubriks, Kitspace, etc.)

b) Cuestionario en línea a través de LimeSurvey, una herramienta de software de código abierto

c) Entrevistas semiestructuradas.

**Formatos**

Para a) y b), los datos se almacenarán en formato de valores separados por comas (.csv). Cualquier mapa generado consistirá de código en formato GeoJSON. Para c), los datos se almacenarán en archivos de texto con formato MarkDown (.md).

La elección de estos formatos se basa en su aceptación por parte de la comunidad de ciencia abierta, los mínimos requerimientos de almacenamiento y la facilitación de una futura reutilización de datos. Los datos de b) yc) serán anonimizados previamente.

Los datos recopilados tendrán un seguimiento utilizando git para el control de versiones.

**Nombres y codificación**

a) archivos .csv: PROJECTNAME_PUBLIC

b) archivos .csv: PROJECTNAME_SURVEY; Archivos .md: PROJECTNAME_SURVEYTXT. Las preguntas se codifican y las respuestas se verifican con los métodos de validación de entrada de datos vía LimeSurvey.

c) archivos .md: PROJECTNAME_SE

### Documentación y Metadatos

Los datos se acompañarán de un resumen del proyecto y una referencia a los materiales de la comunidad de GOSH.

### Ética y Cumplimiento Legal

La recolección de datos a través de encuestas en línea y entrevistas semiestructuradas se realizará con previo consentimiento de los participantes. La identidad de los participantes estará protegida mediante la anonimización de los datos. El almacenamiento y las copias de seguridad de los datos se cifran mediante VeraCrypt.

Los datos se licenciarán bajo [Open Data Commons Attribution License (ODC-By)](https://opendatacommons.org/licenses/by/summary/index.html).

### Almacenamiento y copia de seguridad

Los datos se almacenarán en tres ubicaciones, con copia de seguridad automática:

1. Computadora portátil local

2. Disco duro de [CENIT](http://www.fund-cenit.org.ar/) (copia de seguridad)

3. Disco duro externo (copia de seguridad)

Todas las carpetas que contienen datos se cifrarán utilizando [VeraCrypt](https://www.veracrypt.fr/en/Downloads.html).

### Selección y Conservación

Los datos se pueden usar en el futuro para monitorear la evolución de la comunidad de Open Science Hardware, crear métricas de la comunidad, usar los proyectos para solicitar financiamiento, difundir el trabajo de GOSH, informar a los responsables de políticas y más.

El plan de conservación a largo plazo es publicar la tesis y sus datos relacionados en el [repositorio](https://ridaa.unq.edu.ar/) oficial de la Universidad Nacional de Quilmes 

### Compartir datos

Los datos se compartirán después de la publicación de la tesis a través de la Universidad Nacional de Quilmes [repositorio institucional](https://ridaa.unq.edu.ar/).

Además, se compartirá en [Zenodo](https://zenodo.org/), que proporciona un identificador persistente para los datos.

La publicación se anunciará en los sitios web y foros de la comunidad para que las personas interesadas puedan encontrarla.

### Responsabilidades y recursos

Responsable de la gestión de datos: Julieta Arancio (jarancio@fund-cenit.org.ar), que está llevando a cabo este trabajo de doctorado.

***

*Plan de Gestión de Datos realizado utilizando [DMP Online](https://dmponline.dcc.ac.uk/plans)*
