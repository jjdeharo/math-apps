Herramienta gratuita para eXeLearning

# Convertidor de delimitadores matemáticos

Sube un proyecto `.elpx` o `.elp` y descarga una copia con los delimitadores matemáticos convertidos en `content.xml` (`.elpx`) o `contentv3.xml` (`.elp`). Todo el procesamiento se realiza en tu navegador: el archivo no se envía a un servidor.

## 1. Selecciona tu proyecto

**Arrastra aquí tu archivo .elpx o .elp** o haz clic para elegirlo desde tu dispositivo.

Todavía no has seleccionado ningún archivo.

Selecciona un archivo para empezar.

## 2. Cambios que se aplican

**Expresiones de bloque**\
`$$…$$` → `\[…\]`

**Expresiones en línea**\
`$…$` → `\(…\)`

## Privacidad y recomendaciones

El archivo original no se modifica. La herramienta abre el proyecto como ZIP, cambia únicamente `content.xml` (en `.elpx`) o `contentv3.xml` (en `.elp`) y vuelve a empaquetar el proyecto. Revisa el archivo resultante en eXeLearning antes de distribuirlo. Los signos `$` que parecen monedas (`5$`, `$5 y $10`, `cuesta 5$ y 10$`) no se convierten: una fórmula en línea debe empezar con un carácter que no sea espacio justo después del `$`, terminar con uno justo antes del `$` de cierre, y este no puede ir seguido de un número. Por eso, una fórmula como `$ x $` (con espacios) tampoco se convertiría; escríbela como `$x$`.

La biblioteca JSZip se carga desde una CDN, por lo que se necesita conexión a Internet para abrir la aplicación. Los archivos seleccionados se procesan localmente en el navegador.\
© 2026 Rubén Jiménez Jiménez · Distribuido bajo la [licencia Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0): puedes usar, copiar, distribuir y modificar la aplicación manteniendo el reconocimiento de autoría. Se ofrece «tal cual», sin garantías.