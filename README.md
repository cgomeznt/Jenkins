## Introducción a Jenkins


La integración continua es cuando un grupo desarrolladores trabajan en un mismo proyecto y estan constantemente modificando el codigo y subiendolo al repositorio (GIT, SVN, etc).

La intregración continua es una metodología de trabajo, donde cualquier miembro de un proyecto integra su desarrollo de manera frecuente o por lo menos una vez al día. Esta metodología ejecuta de forma automatica las pruebas de métrica y de calidad.

Estas integraciones se verifican compilando el código que se ha subido y que al finalizar obtiene una especie de ejecutable, este ejecutable es denominado “build”.

Una de las características de la integración continua es hacer las pruebas necesarias de la funcionalidad del código de acuerdo a las reglas de calidad, con el fin de detectar los errores lo mas pronto posible.

Por eso se recomienda hacer los "build" cada vez que se detecte un cambio en el repositorio.

Jenkins es un sistema corriendo en un servidor que es un contenedor de servlets, como Apache Tomcat. Soporta control de versiones como Git y tiene la posibilidad de instalar variedad de plugins para aumentar su funcionalidad.


* [Que es Jenkins](guia/Jenkins.rst)
* [Instalar Jenkins Centos 7](guia/Instalar_Jenkins_Centos_7.rst)
* [Auditoria de codigo Jenkins Scanners](guia/Auditoria_de_codigo_Jenkins_Scanners.rst)
* [Auditoria de codigo Jenkins Scanners HolaMundo](guia/Auditoria_de_codigo_Jenkins_Scanner_HolaMundo.rst)
* [Auditoria de codigo Jenkins Scanner for Ant](guia/Auditoria_de_codigo_Jenkins_Scanner_for_Ant.rst)






