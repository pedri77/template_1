# template_1
Template Bootstrap 4
![BOOTSTRAP 4](https://designmodo.com/wp-content/uploads/2016/03/bootstrap-4-coming.png)
[BOOTSTRAP 4](https://v4-alpha.getbootstrap.com/)

## Índice
1. Boostrap 4 VERSIÓN BETA 
2. Documentación
3. Enlaces

## Bootstrap 4 versión beta

Bootstrap es un framework web responsive que ya va por su versión 4. 

Bootstrap se puede descargar de dos maneras, compilado o mediante el código fuente original.

La forma ms fácil de empezar con este framework es realizar los enlaces hacia su CDN en nuestro documento HTLM:

 ~~~
!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://cdn.rawgit.com/twbs/bootstrap/v4-dev/dist/css/bootstrap.css">
  </head>
  <body>
 ~~~


**Recordar poner al final del BODY:**

 ~~~
<script src="https://code.jquery.com/jquery-3.1.1.slim.min.js" integrity="sha384-A7FZj7v+d/sdmMqp/nOQwliLvUsJfDHW+k9Omg/a/EheAdgtzNs3hpfag6Ed950n" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/tether/1.4.0/js/tether.min.js" integrity="sha384-DztdAPBWPRXSA/3eYEEUWrWCy7G5KFbe8fFjk5JAIxUYHKkDx6Qin1DkWx51bBrb" crossorigin="anonymous"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/js/bootstrap.min.js" integrity="sha384-vBWWzlZJ8ea9aCX4pEW3rVHjgjt7zpkNpZk+02D9phzyeVkE+jo0ieGizqPLForn" crossorigin="anonymous"></script>
 ~~~

En todas las versiones anteriores Bootstrap usaba como preprocesador Less y en la 3.0 introdujo Sass, sin embargo en esta versión alpha 4 se ha decidido prescindir de Less por ahora y usar solamente Sass como preprocesador css.

Antes Bootstrap usaba Normalize.css para resetear los estilos css que traen por defecto los navegadores.

Ahora usa el módulo Reboot para tener todos los selectores genéricos y estilos reseteados en un solo fichero SCSS.

En esta nueva versión desaparece Normalize.css en favor de [Reeboot](http://v4-alpha.getbootstrap.com/content/reboot/)


## Docuemtación

[Docs](http://v4-alpha.getbootstrap.com/getting-started/introduction/)
[Ejemplos](http://v4-alpha.getbootstrap.com/examples/)
[Temas](https://themes.getbootstrap.com)

## Enlaces

[FUNNYFRONTEND](http://funnyfrontend.com/bootstrap-4-alpha-novedades-y-ejemplos/)
[Get Starter](http://v4-alpha.getbootstrap.com/getting-started/introduction/)
