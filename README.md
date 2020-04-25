# ARC-CSS
### Arquitectura CSS
### Estructura HTML5

* Se utiliza el método 7 x 1 para organizar el código CSS.
   * ####abstract: Contiene archivos .scss que no son convertidos a .css, sólo se importan a otro archivo .scss. Contiene código como variables SASS, mixins y funciones.
      * _functions.scss
      * _mixins.scss
      * _placeholders.scss
      * _variables.scss

* Utilizamos SASS como pre-procesador.

* Estructura base HTML5
   * Nav
   * Header
   * Main
   * Footer

* Recursos de terceros:
   * Bootstrap 4.4.1 (CDN comentado - SASS)
   * FontAwesome 5 (CDN)
   * JQuery 3.4.1 (CDN)