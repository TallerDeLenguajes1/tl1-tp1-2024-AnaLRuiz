# tl1-tp1-2024-AnaLRuiz
2. a) Investigar el archivo .gitignore ¿Por qué es conveniente incluirlo?
¿Cuándo se debe hacer?¿Cómo configuraría el archivo .gitignore?

.gitignore es un archico que especifica que o cuales archivos se deben ignorar.
Es conveniente incluirlo porque no todos los archivos que tenemos dentro de nuestro repositorio local vamos a necesitarlos en el repositorio remoto.Cuando subimos nuestro programa a github como repositorio remoto es necesario omitir datos o archivos de gran importancia o bien, que no harán un mayor cambio al funcionamiento en sí. Por ejemplo, un archivo donde tengas contraseñas de configuración ya sea de correo electrónico u otras configuraciones de servidor, o bien archivos que se generan por defecto según nuestro pc, como .DS_store en mac. Ambos son archivos que si necesitamos omitir, uno por seguridad de nuestro código y otro para no sobrecargar el código en si.
Para incluir un archivo .gitignore debemos crearlo desde el git bash con el comando touch, touch .gitignore , luego con un editor de texto agregamos en cada linea un archivo o carpeta que quieramos que Git lo ignore.Ademas necesitamos saber 3 caracteres :
    1. #: es usado para agregar comentarios
    2. /: especificas una ruta dentro del programa para omitir.
    3. *: es un comodin. Por ejemplo, si queremos omitir todos los archivos tipo texto (txt) dentro del programa, usamos *.txt en la configuración.

