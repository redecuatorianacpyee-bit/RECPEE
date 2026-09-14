# RECPEE-WEB

Sitio web estatico de la Red Ecuatoriana de Ciencias Planetarias y Exploracion Espacial (RECPEE), listo para subir directamente a Netlify.

## Estructura general

- `index.html`: contenido principal del sitio.
- `css/styles.css`: colores, diseno y responsive.
- `js/script.js`: menu movil, animaciones suaves y ano automatico.
- `images/`: logo, portada, fotos de directiva y recursos visuales.
- `netlify.toml`: configuracion basica para publicar en Netlify.

## 1. Donde cambiar el logo

Reemplace el archivo:

`images/logo/logo-recpee.png`

Si desea cambiar el icono del navegador, reemplace tambien:

`favicon.ico`

## 2. Donde cambiar las fotografias de la directiva

Coloque las fotos nuevas con estos mismos nombres dentro de:

- `images/directiva/presidente.jpg`
- `images/directiva/vicepresidente.jpg`
- `images/directiva/secretario.jpg`
- `images/directiva/tesorero.jpg`
- `images/directiva/vocal.jpg`

Si mantiene esos nombres, no hace falta tocar el codigo.

## 3. Donde modificar los nombres y cargos

Abra `index.html` y busque estos textos entre corchetes:

- `[NOMBRE DEL PRESIDENTE/A]`
- `[NOMBRE DEL VICEPRESIDENTE/A]`
- `[NOMBRE DEL SECRETARIO/A]`
- `[NOMBRE DEL TESORERO/A]`
- `[NOMBRE DEL VOCAL]`
- `[INSTITUCION]`
- `[DESCRIPCION]`

Reemplace cada marcador por la informacion oficial.

## 4. Donde modificar mision y vision

En `index.html` busque:

- `[INSERTAR AQUI LA MISION OFICIAL DE LA RECPEE]`
- `[INSERTAR AQUI LA VISION OFICIAL DE LA RECPEE]`

Tambien puede reemplazar la descripcion institucional:

- `[INSERTAR AQUI LA DESCRIPCION OFICIAL DE LA RECPEE]`

## 5. Donde agregar actividades

En `index.html` ubique la seccion `Actividades`.

Cada tarjeta ya tiene campos listos para editar:

- nombre
- fecha
- lugar
- descripcion
- boton de mas informacion

Si desea usar otra imagen, coloque el archivo dentro de `images/actividades/` y cambie la ruta de la imagen en la tarjeta correspondiente.

## 6. Donde colocar Facebook, Instagram, LinkedIn, YouTube y demas redes

En `index.html` busque estos marcadores:

- `[URL_PAGINA_OFICIAL]`
- `[URL_FACEBOOK]`
- `[URL_INSTAGRAM]`
- `[URL_LINKEDIN]`
- `[URL_YOUTUBE]`
- `[URL_X]`
- `[URL_TIKTOK]`
- `[CORREO_RECPEE]`

Cuando tenga las URLs oficiales:

1. Reemplace el texto del marcador.
2. Cambie el enlace `href="#"` por la URL real.
3. Mantenga `target="_blank"` y `rel="noopener noreferrer"` en enlaces externos.

## 7. Como probar la pagina localmente

No necesita instalar nada.

Puede abrir directamente:

`index.html`

con doble clic desde la carpeta `RECPEE-WEB`.

Tambien puede arrastrar `index.html` a su navegador.

## 8. Como subir la carpeta a Netlify

1. Comprima la carpeta `RECPEE-WEB` en un archivo ZIP.
2. Ingrese a Netlify.
3. Use la opcion de despliegue manual o arrastre el ZIP o la carpeta.
4. Netlify publicara el sitio usando `index.html` como pagina principal.

## 9. Como actualizar posteriormente la pagina

1. Abra la carpeta `RECPEE-WEB`.
2. Cambie textos, fotos o enlaces segun necesite.
3. Guarde los archivos.
4. Vuelva a comprimir la carpeta o suba la carpeta actualizada a Netlify.

## Recomendacion importante

Los datos oficiales de RECPEE no fueron inventados. Por eso el sitio incluye marcadores entre corchetes para que puedan reemplazarse luego sin romper el diseno.
