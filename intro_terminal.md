# INTRODUCION A LA TERMINAL

## Estructura general de un comando de la terminal

```bash
>> command -arguments -modifiers
```

---

## Comandos de uso general

**man** - (_format and display the on-line manual pages_) Muestra en la terminal el formato y los diferentes posibles usos de los camandos de la terminal.

**pwd** - (_print working directory_) Retorna el path en el cual estamos ubicados.

---

## Comandos para listar directorios y archivos

**ls** - (_list directory content_) Lista los archivos el que estamos trabajando.

**ls -a** - lista todos los archivos del directorio en el que estamos trabajando incluyendo los archivos ocultos.

**ls -l** - (_long format_) Muestra los archivos en forma de lista. ademas de mostrar toda la información de estos. Tal como: user, grupo, permisos, tamaño, fecha y hora de creacion.

**ls -t** - (_time modified_) lista los archivos por fecha de modificación.

**ls -lh** - Muestra la misma información que ls -l pero con las unidades de tamaño en KB, MB.

**ls -R** - (_Recursive_) Muestra el contenido de todos los subdirectorios de forma recursiva

**ls -S** - (_Sort by size_) Ordena los resultados por tamaño de archivo

---

## Comandos para cambiar de ubicación

**cd [path/directory]** - (_Change directory_) se utiliza para cambiar de directorio. Luego del comando se debe especificar la ruta del directorio al que nos queremos mover.

--

## Comandos para copiar, mover y borrar directorios/archivos

**cp [path source file] [path target directory/file]** - (_copy files_) copiar un archivo hacia un directorio.

**rm [path file]** - (_remove_) eliminar un archivo.

**mv [path source directory/file] [path target directory/file]** - (_move_) mover un archivo o directorio, cambiar su ubicación.

**rmdir [path directory]** - (_remove directory_) eliminar un directorio. En este caso es importante resaltar que, para que el directorio pueda ser eliminado, no puede contener archivos u otros directorios en su interior.

**rm -R [path directory]** - (_remove recursive_) eliminar un directorio de forma recursiva. eliminando todas los archivos y directorios que se encuentran adentro de él.

---

## ¡Desafío!

El desafío de esta clase consiste en utilizar todos los comandos y recursos que estudiamos hasta ahora para organizar tu espacio de trabajo como desarrolladora.

1. Ve a tu carpeta personal (/home/tunombre).
2. Crea una carpeta llamada development y entra en ella.
3. Crea una nueva carpeta con el nombre del próximo curso que vas a tomar en Platzi y entra en ella. Te recomiendo escribir los nombres de carpetas o archivos en minúsculas y no usar espacios ni tildes para evitar dificultades (por ejemplo: prog_basica o programacion-basica).
4. ¡Ay, disculpa! Debíamos guardar las carpetas de los cursos en otro lugar. Mueve la carpeta de tu próximo curso a esta nueva ubicación: /home/tunombre/learning/tuproximocurso. Puedes mover la carpeta como prefieras, con el comando para mover directorios o los comandos de copiar y eliminar.
5. Cualquier duda o dificultad que te encuentres puedes dejarla en la sección de comentarios. Estaremos atentos para ayudarte.