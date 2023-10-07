# Comandos de git, linux, vscode
## Comandos linux

**cd** Comando para ingresar a un directorio.
```bash
cd    # Ir al directorio de inicio.
cd .  # Ir al mismo directorio.
cd .. # Ir al directorio anterior.
cd "" # El directorio al que quiero entrar.
```
**ls** Comando para mostrar una lista de los archivos y directorios del directorio donde se encuentra actualmente.
```bash
ls -a  #Para mostrar tanto documentos como directorios ocultos.
ls -l  #Para mostrar informacion mas detallada sobre los documentos y directorios.
ls -t  #Para ordenar la lista de archivos y directorios por fecha y hora.
ls -S  #Para ordenar la lista de archivos y directorios por tamano.
ls -r  #Para ordenar la lista de archivos y directorios en orden inverso.
ls -lt #Para listar en orden descendente de fecha de modificacion
ls -R  #Para listar los contenidos de directorios de forma recursiva (incluyendo subdirectorios).
ls -d  #Para listar unicamente directorios.
ls -p  #Para marcar los directorios con una barra diagonal (/).
ls  *  #Para listar archivos de un tipo especifico se pueden utilizar comodines.
ls -C  #Para mostrar la lista en columnas.
```
**pwd** Comando para mostrar la ruta completa del directorio actual.

**mkdir** Comando para crear un nuevo directorio.
```bash
mkdir -p #Para creae directorios aninados (subdirectorios).
mkdir -m #Para especificar los permisos que deseas establecer al crear el directorio
mkdir -- #Para indicar que los argumentos que siguen no son opciones.
```
**rmdir** Comando para eliminar un directorio vacío solamente elimina los que estan completamente vacios.
```bash
rmdir -p #Para eliminar directorios de forma segura junto con sus directorios padres vacíos si es necesario.
```

**rm** Comando para eleminar archivos y directorios de manera irreversible.
```bash
rm -d #Para eliminar directorios vacios.
rm -r #Para eliminar un directorio y su contenido de forma recursiva.
rm -i #Para que el comando "rm" te pregunte antes de eliminar cada archivo o directorio.
rm -f #Para eliminar archivos sin que "rm" te solicite confirmacion, junto con el comando sudo tambien permite eliminar directorios o archivos con permisos de super usuario.
```

**mv** Comando para mover archivos y directorios de una ubicacion a otra en el sistema de archivos.
```bash
mv -r #Para mover los directorios de manera recursiva incluyendo todos los archivos y subdirectorios dentro de ellos.
mv -i #Para que "mv" te pregunte antes de sobrescribir un archivo.
```

**date** Comando para mostrar o establecer la fecha y la hora del sistema.
```bash
date -d #Para especificar una fecha y hora personalizada que se mostrara en lugar de la fecha y la hora actual.
date -u #Para mostrar la fecha y hora en diferentes zonas horarias
```
**tree** Para mostrar una representacion grafica de la estructura de directorios y archivos en el sistema de archivos.
```bash
tree -L #Para limitar la profundidad de visualizacion.
tree -a #Para mostrar tambien archivos y directorios cuyos nombres comienzan con un punto.
tree -d #Para mostrar solo directorios y omitir la lista de archivos.
tree -J #Para generar la estructura de directorios en formato JSON.
tree -X #Para generar la estructura de directorios en formato XML.
tree -f #Para mostrar las rutas completas de los archivos junto a sus nombres en la estructura de directorios.
tree -v #Para ordenar la salida alfabeticamente.
tree -n #Para ordenar la salida numericamente.
```
**htop** Para monitorear y administrar procesos en tiempor real.

**code** Para abrir archivos y directorios en visual studio que es un popular editor de codigo fuente desarrollado por Microsoft.

**touch** Para crear archivos vacios o actualizar la marca de tiempo de archivos existentes.
```bash
touch -t #Para especificar una fecha y hora especificas para establecer la marca de tiempo de acceso y modificacion de un archivo.
```
**ip** Para administrar y configurar la red y las interfaces de red en un sistema.
```bash
ip a #Para mostrar informacion detallada sobre las interfaces de red de tu sistema.
ip route #Para mostrar la tabla de enrutamiento del sistema, que incluye las rutas utilizadas para dirigir el trafico de red hacia su destino.
```

## Comandos git
- git clone
- git init
- git pull
- git push
- git commit
- git add
- git rm

## VSCODE

Ctrl + Shift + V


## Sintaxis MarkDown
```markdown
*hola*
**hola en negrita**
[google](https://google.com) Esto es una URL

```