## Gestión de Usuarios

### 1\. Cómo matricular alumnado y profesorado de forma masiva

Una vez tenemos creada la estructura de cursos de nuestro centro, el siguiente paso será dar acceso a las personas que vayan a utilizar Aeducar y, en los casos que se requiera, proceder a su matriculación en los cursos correspondientes. El acto de matricular es tanto para alumnado, como para profesorado. Ambos se matriculan en el mismo curso pero con roles diferentes (student/editingteacher).  

Para que el alumnado y el profesorado de nuestro centro puedan trabajar con Aeducar, necesitarán tener una cuenta con la que acceder a la plataforma. 

En cada centro, la persona que realice las tareas de gestión de Aeducar será la encargada de la creación de estas cuentas. 

Para poder **crear un número elevado de cuentas de usuario** a la vez, moodle permite el uso de **ficheros CSV**. Estos fichero contienen la información de todas las personas que van a ser incorporadas a nuestro Aeducar.

Un fichero CSV podemos abrirlo con un programa de hojas de cálculo y veremos que en cada columna contiene los campos de la información requerida por la plataforma y en cada fila los valores para esos campos de cada una de las personas a incorporar.

Para la carga de alumnado y/o profesorado, **nos proporcionarán unas plantillas que simplemente deberemos completar.**

Entre los campos a completar para usuarios:

*   **username**: nombre de usuario. Debe ser único y no podrá haber dos personas con el mismo username en la plataforma. Usaremos el NIF y en el caso de menores que no lo tengan, el NIF de su madre o padre seguido del orden que ocupa entre sus hermanos en el centro.
    
*   **password**: campo que permite asignar contraseña a cada usuario en el momento de la carga de este archivo. Asignaremos de inicio _Cambiame1!_ (por ejemplo) y en la subida del archivo indicaremos que se fuerce al cambio de contraseña tras el primer acceso. 
    
*   **firstname**: nombre de la persona.
    
*   **lastname**: apellidos.
    
*   **email**: dirección de correo electrónico. En caso de ser un menor, se podrá aportar la dirección de correo electrónico de una de las personas adultas de la familia. Este correo electrónico puede repetirse, por ejemplo, para el caso de hermanos menores de edad que aporten el mismo correo electrónico de la madre o del padre.En caso de no disponer de correo electrónico, se  le asignará el proporcionado desde el equipo de Aeducar a este efecto.
    
*   **course1**: nombre corto de un curso en el que queremos que participe. Los cursos deberán existir previamente. Más adelante explicamos cómo se crean.
    
*   **role1**: es un campo opcional, para poder especificar el rol con el que se matricula en ese curso (student, editingteacher). Si no usamos este campo, por defecto se matricularán como estudiantes. 
    
*   **course2**: nombre corto de otro curso en el que va a participar.
    
*   **role2**: rol con el que matricula en este segundo curso
    
*   repetimos las columnas _**courseN**_ _**roleN**_ tantas veces como en cursos se vaya a matricular a esa persona.
    

Una vez hayamos preparado este fichero CSV, la carga de los usuarios es un proceso muy sencillo. Iremos a la opción _**Subir Usuarios**_ y solo tendremos que seleccionar nuestro fichero CSV y cargarlo. 

![](https://lh5.googleusercontent.com/ZKqW6AWEkBOFd0J7o7VTLdR860bgMZV_jkCN4aD1V3Kfe6qIO26MDJO-xFtv0PxAeE8XmaYt8YL2RQKZdX1yT9I8LSkWiR9iOvKhY-GVit2UCoIZ9OZyrnmvYhdjpqa49Zl4mbiP)

  

![](https://lh5.googleusercontent.com/NghbULRHV1WpCFVeUnHOKAR3Wh2LbskDrTglWjxxWbJ1AgM2Dn5wIqMU4Ue2ksGMraMHid_DHCe3LUR122ej9K6thdQ1B90MnkMpNfxwSi4vZm3DZPqLrJmMDzxXir_Ez8oad0MM)

Nos aseguramos que como _Delimitador CSV_ hemos elegido la coma (,) y que vamos a previsualizar un número de filas antes de que se proceda a la carga. Después pulsamos _**Subir usuarios.**_

_**Algunas consideraciones a tener en cuenta con los ficheros CSV**_

*   _Como hemos comentado, un fichero CSV es un fichero de texto plano que se compone de una serie de registros (filas) y cada registro se compone de una serie de campos (columnas)._
    
*   _Esta estructura de filas y columnas hace que sea posible abrirlo y editarlo fácilmente con un programa para hojas de cálculo (Calc, Excel, o las hojas de cálculo de Google Drive por ejemplo)._
    
*   _Como es un texto plano, es necesario utilizar un carácter que haga las funciones de delimitador, es decir, que separe los campos de un registro._
    

_Aquí es donde podríamos encontrarnos algún problema: el delimitador o separador definido en la plantilla CSV que se enviará a los centro es la coma. Por eso indicamos que se seleccione la coma en los ajustes de subida del fichero CSV._

_Es posible que, dependiendo con qué programa se edite ese fichero, al guardarlo aplique otro delimitador diferente, como el punto y coma. En ese caso, probad a abrirlo de nuevo y en las opciones de guardar fijaros bien cuál es el delimitador o separador que se usa. También es conveniente no utilizar caracteres especiales como la ñ o las tildes._

  

Nos llevará a la **página de previsualización** donde además de ver el listado de usuarios a cargar, debajo de este listado nos aparecerá una serie de configuraciones donde deberemos dejar los siguientes valores en los siguientes ajustes antes de pulsar Subir archivo:

*   Contraseña de nuevo usuario: campo requerido en el archivo
    
*   Estandarizar nombre de usuario: No
    

![](https://lh5.googleusercontent.com/GESSqtfjgG_gH7anK2xg1RA60keFEk_2VoKdHYOI88F5PtXqbv-DUPfcaL-ExJmbWD8344lbao6rd2-jLanndxz71m0fYmGTfDGuxMNXwEScAZlXGZThHmoEEBJSkXZUbg2t3j_I)

  

Una vez finalizado este proceso podremos comprobar desde _**Administración del sitio**_ >\> _**Usuarios**_ >\> _**Examinar lista de usuarios**_ que se han incorporado correctamente en nuestra plataforma Aeducar.