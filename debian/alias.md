
## ALIAS

    - Crear alias para evitar memorizar comandos largos


### Ver todos los alias

    $ alias


### Crear alias

    - Crearlos es un proceso relativamente fácil y rápido. Cualquiera puede crear algunos de estos dos tipos:
        los temporales y los permanentes.


        - Permanentes

        Para mantener los alias entre sesiones, vas a tener que guardarlos en el archivo de perfil para la  configuración de shell de tu usuario. Estos podrían ser:

            Bash → ~/.bashrc
            ZSH → ~/.zshrc
            Fish → ~/.config/fish/config.fish

        La sintaxis que hay que utilizar en este caso, es la misma que cuando creamos uno temporal. La única diferencia viene del hecho de que esta vez lo guardaremos en un archivo. Entonces, por ejemplo, en bash, puedes abrir el archivo .bashrc con tu editor favorito:

            $ vim ~/.bashrc

        Editar el archivo y agregar los alias
       
        Ejemplos

            #Mis alias personalizados
            alias imagenes=”cd /home/sapoclay/Imágenes/”
            alias actualizarsistema=”sudo apt update && sudo apt upgrade”
            alias pingxbmc="ping 192.168.1.100"


        Al terminar guarda el archivo. Este archivo se cargará automáticamente en tu próxima sesión. Si quieres usar lo que acabas de escribir en la sesión actual, ejecuta el siguiente comando:

            $ source ~/.bashrc