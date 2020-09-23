## Gestión de Cursos

### 5\. Carga masiva de cursos en Aeducar

Cuando es un único curso o unos pocos los que hay que crear, no hay problema en hacerlo según hemos visto en el apartado anterior.  

En cambio, cuando tenemos que preparar la **estructura completa de un centro**, por ejemplo, puede convertirse entonces en una tarea más pesada que podemos evitar preparando un **fichero CSV** con la información básica de los cursos a crear.

Es únicamente para la carga masiva de cursos. Las categorías deberán existir previamente.

El fichero CSV contendrá una fila por cada curso que vaya a ser creado. Los campos que debemos completar para cada curso son:

*   **shortname**: nombre corto del curso.
    
*   **fullname**: nombre completo del curso.
    
*   **category**: número de la categoría en la que queremos 
    
*   **summary**: resumen del curso
    
*   **visible**: a 1 si queremos que se cree y aparezca directamente visible.
    
*   **enablecompletion**: a 1 para habilitar tener el ajuste de Finalización de actividad, de gran utilidad en el trabajo con el alumnado.
    
*   **groupmodeforce**: a 1 para forzar el modo grupo en los cursos. 
    
*   **groupmode**: 0 para Sin grupos, 1 para Grupos separados y 2 para Grupos visibles.
    

### ![](https://lh4.googleusercontent.com/H37SiycxAcBlIz6BkNhfD3kJ7HaJ5FA0ALvShzUu8ahRiQU6qz2Qjy7jd9vx9AY0IKZHQfFvd0OU627dTPhIVUfT2z5A3EPICUDmRW81qNtBQIM8CnrKekjKM2E4QwXdZwh4iLrl)

Una vez creada la estructura de cursos en el fichero CSV, solicitaremos a través de la **plataforma de [soporte](https://moodle.catedu.es/mod/book/view.php?id=20163 "Soporte")** para Aeducar (ver Tema 3: [Soporte](https://moodle.catedu.es/mod/book/view.php?id=20163 "Soporte")) que suban este fichero a nuestra plataforma, ya que nuestra cuenta de gestión no tiene permisos suficientes para realizar esta acción.

Serán, bien asesorías de CATEDU o bien asesorías del Centro de Profesorado de referencia para nuestro centro educativo (con acceso con perfil de administración a nuestra plataforma), quienes atiendan nuestro ticket de petición de [soporte](https://moodle.catedu.es/mod/book/view.php?id=20163 "Soporte") y suban este fichero desde _Administración del sitio_ \> _Cursos_ \> _Subir cursos_.