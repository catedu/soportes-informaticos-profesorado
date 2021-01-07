# Combinar correo electrónico

## A.- Con GMail y YAMM

{% youtube %}https://www.youtube.com/watch?v=-dAFP3YyAWo&feature=emb_logo{% endyoutube %}

### A1. Redacta tu GMail
Entra en tu correo electrónico y redacta tu correo, pero :

- Deja los destinatarios en blanco
- En tu redacción pon las palabras claves personalizadas que tengas. *En este ejemplo <<nombre>> y <<grupo>>*
- Cierra el correo sin enviar, se te guardará en **Borradores**

![](/assets/correo-gmail-yamm1.jpg)

### A2. Prepara tus destinatarios

Entra en Drive y abre una hoja de cálculo, importa tus datos, si tienes una hoja de cálculo de Excell simplemente copia y pega en esa hoja drive, lo importante es que :

- Tiene que ser hoja de cálculo de Google.
- Tiene que coincidir los nombres de las cabeceras de las columnas con las palabras claves que has puesto en tu correo electrónico. En este caso tiene que ser **nombre** y **grupo** pero **no vale** que ponga **Nombre** o **nombres** por ejemplo
- Tiene que haber una columna que ponga los correos electrónicos, no importa qué nombre tenga la cabecera, en este caso pone *email* pero puede ser *correo electrónicos*
- No importa que haya columnas que no se utilicen. *En este caso apellidos.*

![](/assets/correo-gmail-yamm2.jpg)

### A3. Instala el complemento YAMM

Vamos a Complementos->Descargar complementos - Buscamos YAMM Yet Another Mail Merge - Instalamos

![](/assets/correo-gmail-yamm3.jpg)

### A3. INICIAMOS LA COMBINACIÓN DE CORRESPONDENCIA

Entramos en el complemento instalado e iniciamos la combinación :

![](/assets/correo-gmail-yamm4.jpg)

Después de aceptar una ventana de cual es el plan que tienes con YAMM (el plan Free sólo son 50 emails) sale otra ventana que rellenamos el nombre del remitente y **seleccionamos el borrador, es decir el email creado en el punto A1**

![](/assets/correo-gmail-yamm5.jpg)

Nos da la opción de programar el envío para más adelante o enviarlo ahora o enviar un emmail de prueba

Si enviamos un e-mail de prueba y nos lo enviará a nuestra cuenta de GMail cómo quedaría el primer email del primer registro:

![](/assets/correo-gmail-yamm6.jpg)

Una vez hecha la comprobación podemos enviar ya los emails

## B CON UN PROGRAMA DE CORREO ELECTRÓNICO : THUNDERBIRD

### B1 Instalar Mail Merge

En https://addons.thunderbird.net/en-GB/thunderbird/addon/mail-merge/ podemos instalar esta extensión de thunderbird

![](/assets/correo-thunderbird1.jpg)

### B2.- Guardamos nuestros datos en CSV

Vamos a nuestra hoja de destinatarios que vimos en A2, ojo con los nombres de las cabeceras de las columnas que lo utilizaremos en nuestro email personalizado.

![](/assets/correo-thunderbird4.jpg)

Y lo grabamos en formato CSV (*Nota: Todos los programas de hojas de cálculo permiten esta opción, ya sea Google, Excell, Calc.. *)

![](/assets/correo-thunderbird2.jpg)

### B3.- Redactamos nuestro emails

Redactamos poniendo en **destinatarios el nombre de la columna entre ""{{ }}""** en nuestro caso se llama *email* y seguimos escribiendo con los campos personalizados también entre {{ }}

![](/assets/correo-thunderbird3.jpg)

### B4.- Mail merge

Nos vamos a Archivo-Mail Merge (también hay un botón arriba a la derecha) y rellenamos

1. Nuestro fichero fuente es un CSV tal y como hemos hecho en B2
1. Aconsejamos "Send Later" y así podemos previsualizar el resultado
1. Elegimos el fichero CSV
1. Si nuestra fuente es un Excell recomendamos poner Windows1258
1. La delimitación de campos puede ser ; o ,
1. La delmitación de texto puede ser ninguna o "
1. Hay que modificar los puntos 4, 5 y 6 hasta que en Preview se vea correctamente
1. Ok y lo pone en la bandeja de salida  


![](/assets/correo-thunderbird5.jpg)

### B5.- Previsualizar y enviar

Al darle en el *2 Enviar más tarde* combina todos los emails y los pone en la bandeja de salida.

![](/assets/correo-thunderbird6.jpg)

Si está todo correcto, enviamos ya todos:

![](/assets/correo-thunderbird7.jpg)
