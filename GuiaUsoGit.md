# Guía básica del uso de Git <br>

## ¿Qué es Git? 

![](https://embarcados.com.br/wp-content/uploads/2015/02/imagem-de-destaque-39.png.webp)

[Git](https://es.wikipedia.org/wiki/Git) es un software de [control de versiones](https://es.wikipedia.org/wiki/Control_de_versiones) diseñado por [Linus Torvalds](https://es.wikipedia.org/wiki/Linus_Torvalds), pensando en la eficiencia, la confiabilidad y compatibilidad del mantenimiento de versiones de aplicaciones cuando estas tienen un gran número de archivos de código fuente. Su propósito es llevar registro de los cambios en archivos de computadora incluyendo coordinar el trabajo que varias personas realizan sobre archivos compartidos en un repositorio de código.


## ¿Qué es Github?

![](https://cdn.prod.website-files.com/5f5a53e153805db840dae2db/64e79ca5aff2fb7295bfddf9_github-que-es.jpg)

GitHub es una [forja](https://es.wikipedia.org/wiki/Forja_(software)) (plataforma de desarrollo colaborativo) para alojar proyectos utilizando el sistema de control de versiones Git. Se utiliza principalmente para la creación de código fuente de programas de ordenador. El software que opera GitHub fue escrito en [Ruby on Rails](https://es.wikipedia.org/wiki/Ruby_on_Rails). Desde enero de 2010, GitHub opera bajo el nombre de GitHub, Inc. Anteriormente era conocida como Logical Awesome LLC. El código de los proyectos alojados en GitHub se almacena generalmente de forma pública. El 4 de junio de 2018 Microsoft compró GitHub.

> [!NOTE]
> No debe confundirse con Git o [GitLab](https://es.wikipedia.org/wiki/GitLab).


## ¿Qué necesitamos para usar Github en nuestros proyectos?

1. Crearse una cuenta en [Github](https://github.com/).
2. Descargar Git Bash de la página oficial: https://git-scm.com/downloads
3. Crear carpeta en disco local de nuestro PC.
4. Hacer click derecho dentro de la carpeta y abrir la consola de Git Bash.
<br>


## Comandos habituales para trabajar con repositorios remotos

1. Iniciamos GIT en la carpeta donde esta el proyecto:
> `git init`
2. Para agregar repositorio:
> `git remote add origin` \<url>
3. Para añadir archivos a nuestro repositorio:
> `git add` \<archivo> o `git add .` si queremos añadir todos los archivos que tenemos en local.
4. Poner comentario de los cambios realizados:
> `git commit -m ""` \(entre comillas añadir el texto)
5. Subimos al repositorio:
> `git push`
6. Comprobamos el estado del repositorio:
> `git status`
<br>

## Clonar un repositorio
Copiar dirección del repositorio y usamos el comando 
> `git clone` \<dirección>
<br>

## Hacer un repositorio existente
Utiliza el menú desplegable de la esquina superior derecha de cualquier página y selecciona Nuevo Repositorio. Escribe un nombre para el repositorio. También puedes añadir una descripción al mismo. Elige la visibilidad del repositorio: público, interno o privado.
<br>
