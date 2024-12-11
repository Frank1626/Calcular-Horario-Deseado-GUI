# Web Scraping de Horarios `SSA Ingeniería - UNAM`
## Desarrollo
Los estudiantes de la `Facultad de Ingeniería` con el pasar de los semestres enfrentamos todos al mismo proceso academico el cual es el paso "___INSCRIPCIÓN POR INTERNET___", el cual sigue la misma dinamica como otras escuelas, el cual días atras en la fase de "___NÚMERO DE INSCRIPCIÓN, LISTA DE ASIGNATURAS
Y ELECCIÓN DE CAMPO___", nos entregan dos datos relevantes para este proyecto, los cuales son la raíz de la idea de programar esto. Ya que en dicha fase, nos entregan a todos los estudiantes nuestro numero de inscripción acompañado del a partir que horario nos podemos inscribir. En mi experiencia, muchos compañeros me han contado que siguen una estrategía similar para seleccionar un horario el cual consta

* Investigar a los profesores disponibles para la materia (CASO MUY EXTREMO): 
    
    Esto tiene como origen a la idea y experiencia vivida por compañeros que ya cursaron la materia, que relatan de alguna forma la calidad de estudio de algunos profesores, ya que unos son considerado bueno o malos con rasgos muy subjetivos. Actualmente el apoyo para esto es investigar en la plataforma de [MisProfesores](https://www.misprofesores.com/), el cual se corre riesgos de encontrar comentarios poco frutiferos para localizar profesores de calidad, ya sea por comentarios de odio contra ellos, poca trayectoria o el caso más comun, no hay nada de información de ellos. Sin embargo, se intenta investigar que profesores son convenientes para el estudio de cada uno.
* Horario acorde a nuestro tiempo disponible: 

    Esto se debe a que filtrar la información tiende a depender de nuestra disponibilidad en nuestro día a día, ya sea por que unos (como mi caso) trabajan y resulta complicado buscar el simple hecho de que haya materias disponibles al día que tenemos para estudiar o el horario (primordialmemnte). En mi camino por la universidad he encontrado a todo tipo de compañeros que solo puede estudiar pocos días a la semana, en horarios que conmumente se le conoce como tiempo completo, muy tempranos, muy tardes que no suelen seguir el concepto de horario "matutino" o "vespertino".

* Preferencia a profesores por su forma de enseñar es acorde a nosotros:

    Ya que con este "lote" de profesores que tenemos como preferentes son nuestra mayor busqueda de profesores que tienen clases que consideramos aptas por nosotros, ya sea poque maneja un plan de estudio mas relajado, es aquel que enseña perfectamente, es dinamico, X o Y razón.

El proyecto surge con la idea de facilitar el proceso de generar un horario (propuesta) rapido, previamente configurado con nuestras "exigencias", como lo sería un profesor de calidad, un horario acorde a mi situación, mis deseos de profesores, sin embargo aqui se consideran dos puntos importantes que se viven durante la inscripción ya que es muy comun que un profesor de nuestro horario propuesto antiguamente, al ser ocupado _descompensaba_ a nuestro horario, provocando que tenemos que indagar nuevamente a la plataforma de [horario](https://www.ssa.ingenieria.unam.mx/horarios.html) a encontrar un profesor que quede acorde a nuestras peticiones (previamente mencionadas), estar escribiendo a cada rato el codigo de la asignatura y ademas ver que los profesores aun tengan disponibilidad en sus grupos, ya que la pagina oficial tarda 5 minutos en refrescar la información, entonces queda esperar que esto no nos complique en nuestro nuevo intento por meter un profesor. 
## Caracteristicas principales
El programa (en desarrollo) busca ofrecer las siguientes soluciones:
- Automatizar la extracción de horarios de la pagina oficial de [horario, del portal de SSA Ingenieria - UNAM ](https://www.ssa.ingenieria.unam.mx/horarios.html) mediante la tecnica de Web Scraping
- Filtrar los grupos segun la disponibilidad en tiempo real (o al menos a la par que la plataforma se actualiza)
- Permite a los estudiantes organizar horarios basándose en sus preferencias.
    - Desde cursos que deseamos entrar (Sirve esto más para aquellos que tienen una variedad de posibilidades de asignaturas a la que se desea entrar)
    - Cursos previamente finalizados (sirve más para aquellos que ya cursaron alguna materia del bloque de asignaturas que pueden entrar), aunque esto se puede dejar vacio

Con este programa se espera que mis compañeros puedan ahorrar tiempo en escoger algun profesor y que no tengan que dar vueltas entre tantos grupos, minimizar los errores que se intenta evitar con el clasico "_empalme_" de grupos y crear horarios que se ajusten mejor a sus necesidades académicas.

## Requisitos Previos
- Python 3.8 o superior.
- Bibliotecas necesarias:
    - requests
    - charset_normalizer
    - io
    - pandas
    - datetime

## Instalación

## Uso 

## Configuración

## Ejemplos de Uso

## Contribuciones
Si deseas contribuir, abre un issue o crea un pull request.  
