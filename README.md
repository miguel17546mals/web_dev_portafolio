# Portafolio desarrollador web

¡Bienvenido!

Este es mi portafolio como desarrollador web

## Lenguajes

* JavaScript
* CSS
* HTML

## Librerias

* Material icons
* Sass

### Sass

[Sass](https://sass-lang.com/) es un preprocesador de css que nos ayudara a construir de manera mas rapida y eficiente los estilos de la pagina.

#### Instalación

> sudo npm install -g sass

#### Compilado

Un solo archivo
> sass styles/scss/styles.scss  styles/css/styles.css

Compilado de varios archivos
> sass --watch styles/scss:styles/css

#### Creacion de hojas de estilos

Cada archivo nuevo se debera crear en styles/scss en su respectiva carpeta con la extension .scss se creara un archivo conocido como partial ejemplo `_styles.scss` empezando el nombre con guion bajo.

> nota: despues de crear el partial se importa en el archivo main.scss ejemplo `@import 'styles'`

### Material Design

[Material Design](https://material.io/resources/icons/?icon=query_builder&style=baseline) Material design es una normativa de diseño en esta ocasion solo usaremos los iconos que nos proporciona.

es tan facil de usar que solo tendras que copiar el codigo del icono que quieras usar:

> < span class="material-icons">
android
< /span >
