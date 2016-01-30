# Taller de Git
Antes de empezar se debe tener instalado Git en las computadoras
## Instalar Git

### Windows
[Descargar Git para Windows](http://git-scm.com/download/win)

### Mac
Para verificar si está instalado Git, puedes abrir el terminal y ejecutar `git`, en caso que no esté instalado te saldrá un prompt para instalar los command line tools de Xcode o sino lo puedes descargar directamente desde [aquí](http://git-scm.com/download/mac)


## Customizar la línea de comando
La línea de comando en Mac y Linux se la puede personalizar para que muestre información adicional del repositorio a simple vista, toda línea de comando tiene su perfil en un archivo oculto en la carpeta home: `~/.bash_profile`

Dentro de la carpeta utils, adjunto tres archivos que deberán tener para hacer que su vida sea más fácil con la línea de comando
- `bash_profile`
- `git-prompt.sh`
- `git-completion.bash`

Los cuales deberán ser pegados en la ruta home como archivos ocultos, que quiere decir esto? que haremos algo como lo siguiente en el terminal:
- `cp /ruta/al/archivo/git-prompt.sh ~/.git-prompt.sh`
- `cp /ruta/al/archivo/git-completion.bash ~/.git-completion.bash`
- Revisar si ya existe el archivo `.bash_profile` si no existe seguir con el mismo paso que los otros `cp /ruta/al/archivo/bash_profile ~/.bash_profile`, caso contrario, solo es necesario copiar el contenido de `bash_profile` en el archivo ya existente de `.bash_profile`
- Decirle al terminal que tiene que actualizar su perfil con `source ~/.bash_profile`