# Programacion 3

## 1) ¿Qué es git?

Es un sistema de control de versiones, un sistema de control de versiones como su nombre lo indica es un sistema, un programa que controla o administra las distintas versiones de un programa.

## 2) ¿Por qué queremos utilizar git?

Porque quiere controlar un proyecto que va a crecer a medida que el tiempo va haciendo cambios en su proyecto, es decir, a medida que tu proyecto va creciendo vas a ir cambiando archivos, vas a ir modificando, como esta configurada tu aplicación, como está escrito el código, etc.

## 3) ¿Qué es el bash que instala git?
 
Es una herramienta de tipo consola que básicamente te permite manipular y gestionar todo el proceso a realizar con el proyecto.

## 4) Describa los estados (working directory, staging area, repository)

- working directory: es donde tú vas a trabajar con todos los archivos.
- staging area: donde vas a estar agregando todos los archivos que vas preparando para el guardado.
- En git vas a tener múltiples cambios de la versión 1, versión 2 quizas y en working directory vas a estar trabajando con tus archivos cuando estas creando la primera versión de tu software pues vas a ir pasando todos los archivos al staging área y finalmanete cuando estas decidido a poder guardar el cambio lo vas a pasar a un repositorio.

## 5)  Describa el flujo para crear un nuevo repositorio git.
- Primero creamos una carpeta, luego ubicarte en el Git Bash y escribir el comando *git init*, Luego en el Git Bash ponemos cd Desktop “apretamos enter”, luego cd Proyecto y entarmos ya al proyecto, luego ponemos ls y veremos dos archivos que cree, luego utiizamos git init para inicializar el proyecto como repositorio local.

## 6)  Describa el flujo para agregar un archivo simple al repositorio. 
 
El comando " add " marca los cambios que se incluirán en la próxima confirmación. Agrega cambios al "Staging Area" de Git, cuyo contenido puede ser envuelto en una nueva revisión con el comando " git commit".
Pero para añadir un archivo lo puedes hacer con el comando git add "nombre de archivo".

## 7)  Describa el flujo para cambiar el archivo agregado y guardar los cambios en el repositorio.
   
Inicializar con git init, añadir archivos con git add “archivo", luego confirmar los cambios en el repositorio con git commit ‘comentario’, ver el estado de un archivo git status, ver la diferencia entre archivos que están añadidos y los cambios mediante con git diff.

## 8) ¿Cómo hago para ignorar un archivo o carpeta?

Creamos una carpeta “Test” y escribimos un código de prueba, y creamos un archivo llamado “.gitignore” en el cual voy a nombrar todos los archivos y carpetas en cual quiero que ignore y le damos “enter” y en ese mismo archivo que creamos ponemos en este caso “test”, luego ponemos “git status” y nos aparecerá que no esta la carpeta test, pero aparece “.gitignore”, entoces ese si lo podemos agregar porque es como el listado de archivo que tengo que ignorar, luego lo agregamos “git add .gitignore”, luego ponemos “git status” y parece que ya esta agregado el “.gitignore”.

## 9) Explique qué es un branch. Dé un pequeño ejemplo de cómo haría uno.

De esta forma podemos ir abriendo ramas que parten bien de la rama principal (master) o de otra rama (branch).

- $ git branch nuevafuncionalidad

- $ git checkout nuevafuncionalidad

## 10)  ¿Qué hago con git add ?
    
debe usar el add el comando para agregar cualquier archivo nuevo o modificado al índice y tampoco afecta al repositorio de manera significativa: en realidad, los cambios no se registran hasta que ejecutas “git commit”.

## 11)  ¿Cómo cambiamos de un branch a otro?

  $ git branch
*  `master`

$ git branch login

$ git branch
  login
* `master`

$ git checkout login
Switched to branch 'login'

$ git branch
* `login`
-  master

## 12)   Investigue qué es Markdown y responda todas las preguntas anteriores en este lenguaje.

Es un lenguaje de marcado que facilita la aplicación de formato a un texto empleando una serie de caracteres de una forma especial. En principio, fue pensado para elaborar textos cuyo destino iba a ser la web con más rapidez y sencillez que si estuviésemos empleando directamente HTML. Y si bien ese suele ser el mejor uso que podemos darle, también podemos emplearlo para cualquier tipo de texto, independientemente de cual vaya a ser su destino.
Como explica "John Gruber" Markdown es realmente dos cosas: por un lado, el lenguaje; por otro, una herramienta de software que convierte el lenguaje en HTML válido.






