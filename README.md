# ARC-CSS
### Arquitectura CSS
### Estructura HTML5

* Se utiliza el método 7 x 1 para organizar el código CSS.
   * <strong><u>Abstract:</u></strong> Contiene archivos .scss que no son convertidos a .css, sólo se importan a otro archivo .scss. Contiene código como variables SASS, mixins y funciones.
      * _functions.scss
      * _mixins.scss
      * _placeholders.scss
      * _variables.scss


   *  <strong><u>Base:</u></strong> Contiene archivos .scss (_base.scss) para importar a style.scss. Contiene código para estilos de etiquetas HTML como p, a, body, etc. La tipografía puede ir en esta sección, así como también el archivo reset para restablecer los estilos del navegador.
      *  _animation.scss
      *  <strong>_base.scss</strong>
      *  _reset.scss
      *  _typography.scss

   * <strong><u>Componentes:</u></strong> Contiene archivos .scss para importar a style.scss. Contiene código para estilos de componentes separados e individuales del layout, como botones y carrusel.
     * _buttons.scss
     * _carousel.scss
   
   * <strong><u>Layout:</u></strong> Contiene archivos .scss (_layout.scss) para importar a styles.scss. Contiene código para estilos de layout de HTML, como Footer, Header, Main, Nav, etc.
     *  _footer.scss
     *  _forms.scss
     *  _header.scss
     *  <strong>_layout.scss</strong>
     *  _main.scss
     *  _nav.scss
   * <strong><u>Pages:</u></strong> Contiene archivos .scss (_pages.scss) para importar styles.scss. Contiene código para estilos de páginas, como por ejemplo, home (_home.scss).
     *  _home.scss
     *  <strong>_pages.scss</strong> 

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