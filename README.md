![Logo SigmaPCS](https://sigmapcs.com.mx/images/logo.png)

# Sigmapcs-boilerplate

Es una sencilla pero muy poderosa estructura para un proyecto web estático.
Los proyectos estáticos son muy utiles pero detrás de su aparente simplicidad
hay mucho trabajo tedioso que hacer por detrás: compilar archivos, crear
el bundle javascript, recargar automáticamente el navegador con los cambios, etc.
Y para cada proyecto hacer lo mismo una vez y otra vez y otra vez. Frustrante.

## Características de Sigmapcs-boilerplate:

* Usa gulp para automatizar tareas
* Esta basado en Sass, Pug y ES6.
* Compila Sass con autoprefixer y muestra los cambios en tiempo real
* Compila Pug y actualiza el navegador con cada cambio
* Compila ES6 con soporte para módulos ES6 (importar y exportar modulos)
* Detecta nuevos archivos añadidos al proyecto sin tener que reiniciar gulp
* Captura errores en Sass, Pug y Js evitando que gulp se detenga.
* Crea los sourcemaps de los archivos compilados
* Tiene una estructura lista de estilos (con Sass) basada en SMACSS y ITCSS
* Tiene una estructura lista para HTML (con Pug) que divide páginas e includes.
* Tiene una estructura lista para importar y exportar modulos ES6

## Modo de uso

1. Clone este repositorio (aun no tiene instalacion por npm o yeoman)
2. Ejecute `npm install` (asegurese de tener npm actualizado y Nodejs en v6 como minimo)
3. Ejecute `gulp`
4. Disfrute

## Estructura

1. La carpeta dev contiene la estructura de archivos con la que trabajará
2. La carpeta public contiene los archivos compilados que deberan llevarse a producción
3. Para Sass importe sus partials desde `styles.scss`, el orden está indicado en el mismo archivo
4. Para Pug, la carpeta `pages` contiene las paginas del proyecto y la carpeta `includes` los bloques.
5. Para Js, la carpeta `modules` contiene los módulos que serán importados desde `index.js`

Siéntase libre de usarlo y de reportar cualquier problema que encuentre o sugerencia que tenga.
Sigmapcs-boilerplate es gratis, open source y de la comunidad para la comunidad.

[SigmaPCS](https://sigmapcs.com.mx)
