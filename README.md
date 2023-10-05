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
- rm
- date
- tree
- htop
- code
- touch
- ip

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