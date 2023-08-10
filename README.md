| Comando                | Descripción                                                | Ejemplo de uso                             |
|------------------------|------------------------------------------------------------|--------------------------------------------|
| clear                  | Limpia la pantalla de la sesión de consola actual.        | `clear`                                    |
| cd <ruta de directorio>| Cambia el directorio actual.                              | `cd ~/Ulacit`                              |
| ls <directorio>        | Lista archivos y directorios.                             | `ls ~/Ulacit`                              |
| cp <origen> <destino>  | Copia archivo o directorio.                               | `cp -r ~/Ulacit/* ~/`                      |
| echo                   | Imprime cadena de texto.                                 | `echo "Hola"`                              |
| man <comando>          | Muestra ayuda del comando.                               | `man ls`                                   |
| pwd                    | Muestra directorio actual.                               | `pwd`                                      |
| mkdir <directorio>     | Crea directorio nuevo.                                   | `mkdir ~/Ulacit`                           |
| rm <archivo>           | Elimina archivo.                                          | `rm ~/Ulacit/archivo.txt`                  |
| rmdir <directorio>     | Elimina directorio vacío.                                 | `rmdir ~/Ulacit`                           |
| mv <origen> <destino>  | Mueve archivo o directorio.                              | `mv ~/Ulacit/archivo.txt ~/`               |
| cat <archivo>          | Muestra contenido de archivo.                            | `cat ~/Ulacit/archivo.txt`                 |
| grep <palabra> <archivo>| Busca palabra en archivo.                               | `grep "Hola" ~/Ulacit/archivo.txt`         |
| sort <archivo>         | Ordena contenido de archivo.                             | `sort ~/Ulacit/archivo.txt`                |
| uniq <archivo>         | Elimina entradas duplicadas.                             | `uniq ~/Ulacit/archivo.txt`                |
| head <archivo>         | Muestra primeras líneas de archivo.                      | `head -n 5 ~/Ulacit/archivo.txt`           |
| tail <archivo>         | Muestra últimas líneas de archivo.                       | `tail -n 5 ~/Ulacit/archivo.txt`           |
| wc <archivo>           | Cuenta líneas, palabras y caracteres en archivo.         | `wc ~/Ulacit/archivo.txt`                  |
| find <directorio>      | Busca archivos/directorios que coincidan con criterio.   | `find ~/Ulacit -type f -name *.txt`        |
| tar <archivo>          | Comprime o descomprime archivos/directorios.             | `tar -czvf archivo.tar.gz ~/Ulacit`       |
| gzip <archivo>         | Comprime archivo.                                         | `gzip ~/Ulacit/archivo.txt`                |
| chmod <permisos> <archivo> | Cambia permisos de archivo.                           | `chmod 777 ~/Ulacit/archivo.txt`           |
| chown <propietario> <archivo> | Cambia propietario de archivo.                     | `chown root:root ~/Ulacit/archivo.txt`     |
| chown <grupo> <archivo> | Cambia grupo de archivo.                                | `chown root:wheel ~/Ulacit/archivo.txt`    |
| su <usuario>           | Cambia a usuario especificado.                           | `su root`                                 |
| sudo <comando>         | Ejecuta comando como root.                               | `sudo rm -rf ~/Ulacit`                    |
| reboot                 | Reinicia el sistema.                                      | `reboot`                                  |
| shutdown               | Apaga el sistema.                                         | `shutdown -s`                             |
| poweroff               | Apaga el sistema sin apagar servicios.                    | `poweroff`                                |
| login                  | Inicia sesión en el sistema.                              | `login`                                   |
| logout                 | Cierra sesión en el sistema.                              | `logout`                                  |
| exit                   | Sale del shell.                                           | `exit`                                    |
| help                   | Muestra ayuda para un comando.                            | `help ls`                                 |
| man <comando>          | Muestra documentación del comando especificado.          | `man ls`                                  |
