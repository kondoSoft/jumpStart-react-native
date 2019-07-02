# Node Version Manager

Nvm como ya habrás podido imaginar es un manejador de versiones específico para Node. Esto es necesario ya que cada versión de Node es diferente y puede contenter cambios que afecten el funcionamiento de tu programa, asi que es una herramienta fundamental.

Su instalación es muy sencilla, primero revisemos si tenemos instalado curl o wget.

Abre tu terminal y escribe `curl -v` si no lo tienes instalado intenta con `wget --version`, ya sea Mac OS o Linux tu equipo debe tener instalado al menos alguno de los dos.

Dependiendo de cual tengas puedes usar uno de estos comandos.

`curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash`

`wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash`

esto lo que hace es descargarlo y una vez descargado lo ejecuta como un script usando el comado bash nativo de la terminal.

Al terminar asegurate de abrir tu archivo `~/.bash_profile`, `~/.zshrc`, `~/.profile`, o `~/.bashrc` y agregar de ser necesario lo siguiente al final del archivo.

```
export NVM_DIR="${XDG_CONFIG_HOME/:-$HOME/.}nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
```

Con nvm puedes instalar varias versiones cambiarte de ellas a placer y rápido.