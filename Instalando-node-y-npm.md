# Instalando Node y Npm

Node es básicamente una implementación de Javascript del lado del servidor. Tradicionalmente Javascript corre sobre el navegador, pero Node nos permite ejecutarlo como un comando de un servidor o tu equipo, de esta manera podremos usar javascript para hacer procesos en el equipo.

React native usa node como servidor de archivos y para poder corre react-native hay que instalarlo.

Nosotros solo usaremos `nvm install v10` lo que instalara la version 10.16.0 que a la fecha es la mas estable. Una vez hecho esto la definiremos como la default para nuestro uso. `nvm alias default v10.16.0`

Ahora solo verifiquemos que sea la ultima versión la que estamos usando. `node -v`
Y revisemos que npm este instalado correctamente. `npm -v`