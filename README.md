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
| Comando      | Descripción                                              | Ejemplo de uso                                     |
|--------------|----------------------------------------------------------|----------------------------------------------------|
| alias        | Crea un alias para un comando.                          | `alias ls="ls -la"`                                |
| bind         | Asigna una nueva tecla a un comando.                   | `bind '"\C-a":beginning-of-line'`                 |
| break        | Sale de un bucle while o for.                          | `while true; do echo "Hola"; break; done`         |
| case         | Comprueba si una cadena coincide con patrones.         | `case $1 in (hola) echo "Hola";; *) echo "Otro";; esac` |
| continue     | Salta a la siguiente iteración de un bucle.            | `for i in *.txt; do if [ -f $i ]; then continue; fi; echo "Esto no se imprimirá"; done` |
| do           | Bloque de comandos para un bucle while o for.         | `while true; do echo "Hola"; break; done`         |
| echo         | Muestra un mensaje en la terminal.                    | `echo "Hola"`                                      |
| else         | Bloque de comandos para un condicional if.            | `if [ -f archivo.txt ]; then echo "Sí"; else echo "No"; fi` |
| eval         | Ejecuta un comando como si se hubiera escrito.        | `eval "echo $variable"`                           |
| export       | Exporta una variable al espacio de nombres.           | `export variable=valor`                           |
| for          | Itera sobre una lista de valores.                     | `for i in *.txt; do echo $i; done`                |
| if           | Comprueba si una condición es cierta.                 | `if [ -f archivo.txt ]; then echo "Sí"; else echo "No"; fi` |
| in           | Comprueba si una cadena está en una lista de cadenas. | `if [[ $cadena in *hola* ]]; then echo "Sí"; fi`  |
| read         | Lee una entrada del usuario.                          | `read -p "Introduce tu nombre: " nombre; echo "Hola $nombre"` |
| return       | Sale de un script.                                    | `function saludar { echo "Hola"; return; } saludar` |
| then         | Bloque de comandos para un condicional if.            | `if [ -f archivo.txt ]; then echo "Sí"; else echo "No"; fi` |
| until        | Itera sobre una lista hasta que una condición sea cierta. | `until [ -f archivo.txt ]; do echo "Esperando..."; sleep 1; done` |
| while        | Itera sobre una lista mientras una condición sea cierta. | `while [ -f archivo.txt ]; do echo "Sí"; done`   |
| while read linea; do echo $linea; done < archivo.txt | Itera sobre las líneas de un archivo. | `while read linea; do echo $linea; done < archivo.txt` |
