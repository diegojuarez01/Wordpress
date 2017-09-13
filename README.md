Instalación Wordpress
===

# Descarga e instalación

1. Descarga la última versión WordPress.

2. Sube el contenido de la carpeta WordPress (no la carpeta sino el contenido de la misma) descomprimida a tu servidor.

3. Abre https://tudominio.es/wp-admin/install.php en tu navegador y sigue el proceso de instalación, facilitando la información de conexión con la base de datos que deberá facilitarte tu proveedor de alojamiento web. Con esto deberán crearse las tablas necesarias para tu sitio. 

4. Guarda la contraseña que utilices.

5. Nos redireccionara a la página de acceso. Accedemos con el nombre de usuario y contraseña elegidos durante la instalación.

# Instalar idioma

1. Descarga el paquete de WordPress que se corresponda con tu versión instalada.
2. Descomprime el paquete en una carpeta de tu ordenador.
3. Copia el archivo es_ES.mo que encontrarás en la carpeta /wp-content/languages a esa misma carpeta de tu instalación (si no existe la creas).

# Diferentes opciones para actualizar

### Antes de actualizar, debes de tener copias de seguridad de cualquier archivo modificado, como wp-config.php o .htaccess.

# Actualizar manualmente desde cualquier versión anterior de WordPress:

1. Elimina tus archivos de WP anteriores, guardando aquellos que hayas modificado.
2. Sube los nuevos archivos a tu servidor mediante FTP.
3. Dirige tu navegador a /wp-admin/upgrade.php.

# Actualizaciones automáticas desde la versión 3.0:

Actualizaciones automáticas lo encontrarás en ""Escritorio -> Actualizaciones"" o en el mismo "Escritorio".

# Posibles errores

Si hay algún error, debemos de revisar el archivo wp-config.php y volver a intentarlo, si vuelve a fallar debemos visitar los foros de soporte para buscar una solución.

Si, no puedes realizar la instalación anterior haz lo siguiente: 

Abre el archivo wp-config-sample.php y rellena los datos de la conexión a tu base de datos.

Guarda el archivo como wp-config.php.
