# **Git Cheat-Sheet**

## Indice
    1.¿Qué es Git?
    2.Tipos de repositorio Git
    3.Implementacion de Git
    4.Comandos mas usados
      -El Guardando cambios
      -Habilitación de la colaboración
    5.Comandos con Git desde Consola (CMD)
    6.Glosario de terminos

### ¿Qué es Git?
    Git es un software de control de versiones diseñado por Linus Torvalds. Software de código abierto Seguimiento de cambios en cualquier conjunto de archivos, generalmente utilizado para coordinar el trabajo entre programadores que desarrollan código fuente de forma colaborativa durante el desarrollo del software.

    ### Tipos de repositorio Git

    En Git hay 2 tipos de repositorios  el de desnudos y el de no desnudos.

![](Git.jpeg)

#### *Repositorios desnudos*

    Los equipos de desarrollo de software utilizan repositorios básicos para compartir los cambios realizados por los miembros del equipo. Los usuarios individuales no pueden modificar o crear nuevas versiones del repositorio.

#### *Repositorios no desnudos*

    Con repositorios no desnudos , los usuarios pueden modificar el repositorio existente y crear nuevas versiones. De forma predeterminada, el proceso de clonación crea un repositorio no vacío.

### Implementacion de Git

    La implementación JGit de Git es una biblioteca de software Java pura , diseñada para integrarse en cualquier aplicación Java. JGit se usa en la herramienta de revisión de código de Gerrit y en EGit, un cliente de Git para Eclipse IDE.
    
    Go-git es una implementación de código abierto de Git escrita en Go puro . Actualmente se usa para respaldar proyectos como una interfaz SQL para repositorios de código Git y proporciona cifrado para Git.
    
    La implementación de Dulwich de Git es un componente de software Python puro para Python 2.7, 3.4 y 3.5.
    
    La implementación libgit2 de Git es una biblioteca de software ANSI C sin otras dependencias, que se puede construir en múltiples plataformas, incluidas Windows, Linux, macOS y BSD. Tiene enlaces para muchos lenguajes de programación, incluidos Ruby , Python y Haskell . 
    
    JS-Git es una implementación de JavaScript de un subconjunto de Git.

## **Comandos mas usados**

![Instalacion de Visual Studio Code](https://code.visualstudio.com/)

### El Guardando cambios
<space>
Los cambios en el repositorio de Git se realizan mediante los comandos git addy . git commitEl git addcomando agrega archivos al área de preparación, mientras que el git commitcomando aplica los cambios preparados al repositorio.

El git addcomando utiliza la siguiente sintaxis:

    git add [file/directory name]

### Habilitación de la colaboración
Git te permite copiar y compartir repositorios con otros desarrolladores usando los comandos

    git pushy* *.git pull*

El git pushcomando le permite compartir todas las confirmaciones y archivos en el repositorio actual con uno o más repositorios remotos. El git pushcomando utiliza la siguiente sintaxis:

    git push [remote repository] [branch name]

**Dónde:**

*[remote repository]:* el nombre del repositorio remoto con el que desea compartir sus confirmaciones y archivos.
*[branch name]:* El nombre de la rama de su repositorio local que desea compartir.
Use el git pullcomando para copiar el contenido de un repositorio remoto y fusionarlo con su copia local: 
   
    git pull [remote repository]

### **Comandos con Git desde Consola (CMD)**

Cls para borrar historial del console.
Dir para la revisión de archivo que está en el escritorio. (En listar)
Cd para agregar una ruta de ubicación de archivo.

    Mkdir crear una carpeta nueva.
    CMD abrir la consola, cuando estas dentro de console, te dice la versión y los derechos reservados.

Rmdir para borrar una carpeta.
Cd.. Para dar atrás a una carpeta

#### **Configuración inicial** 

    git config --global user.name “Nombre”
    git config --global user.email “correo”
    git config --list

    git init (se hace una sola vez en el proyecto)
    git status verifica el dato actual que contiene el repositorio. (Nos dice el estado actual que tiene el proyecto).
    git add para inicializar.


    dir / ash para archivos ocultos.

    git commit
    git clone para subir proyecto a la nube.

    Code. Para abrir visual studio code.

Crear un indice y guardad en el historial, despues de hacer una tarea hay que hacer un commit

*git commit -a* "Introduccion a Git agregado"
git brach para crear ramas como la rama master y rama development.

*git lock*esto para ver un tipo de historial que vizualiza quien lo hizo y la fecha.
NO puede haber repositorios con el mismo nombre

## <space> **Glosario de terminos**

***Repositorio:*** Es una base de datos de contenido digital con un conjunto asociado de métodos de gestión, búsqueda y acceso de datos que permite el acceso independiente de la aplicación al contenido, como una biblioteca digital, pero con la capacidad de almacenar y modificar contenido además a la búsqueda y recuperación.

***Python:*** Es un lenguaje de programación de propósito general y de alto nivel.

***JavaScript:*** Es un lenguaje de programación que es una de las tecnologías centrales de la World Wide Web , junto con HTML y CSS .

 ***Mkdir*** crear una carpeta nueva.
 ***CMD*** abrir la consola, cuando estas dentro de console, te dice la versión y los derechos reservados.
***Cls*** para borrar historial del console.


***git commit -a*** "Introduccion a Git agregado"
git brach para crear ramas como la rama master y rama development.

***Rmdir*** para borrar una carpeta.
***Cd.. *** Para dar atrás a una carpeta.

***git lock***esto para ver un tipo de historial que vizualiza quien lo hizo y la fecha.NO puede haber repositorios con el mismo nombre.
