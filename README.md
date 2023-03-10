# masterpidgey-examen
# Parte 1
## Paso 1

- Crear el repositorio masterpidgey-examen <br>
![1.1](img/1.png)<br>
    -  Dándole al + de la barra de acceso te permite crear un repositorio.<br>
- Clonar el repositorio en local<br>
  ![1.2](img/2.png)<br>
    - Una vez obtienes el link de tu repositorio puedes clonarlo con el comando git clone.<br>
## Paso 2<br>
- Crea el documento README.md<br>
  ![2.1](img/3.png)<br>
      - El documento puede ser creado tanto automáticamente como manualmente, en mi caso lo he creado automáticamente durante la creación del repositorio<br>
## Paso 3<br>
- Añadir al README.md los comandos utilizados hasta ahora y hacer un commit inicial con el mensaje commit inicial.<br>
  ![3.1](img/4.png)<br>
  -  Tras añadir los comandos y las capturas he hecho **git add .**, ya que me añade todo el contenido de la carpeta; y, tras eso, he hecho el commit.<br>
## Paso 4<br>

- Subir los cambios al repositorio remoto.<br>
  ![4.1](img/5.png)<br>
    - Usando el comando push he subido a mi repositorio todos los ficheros.<br>

## Paso 5<br>

- Crear en el repositorio local un fichero llamado privado.txt.<br>
![5.1](img/6.png)<br>
  - Este documento será ignorado por la máquina después<br>
- Crear en el repositorio local una carpeta llamada privada.<br>
![5.2](img/7.png)<br>
  - Lo mismo pasará con la carpeta privada y sus contenidos <br>
- Realizar los cambios oportunos para que tanto el archivo como
la carpeta sean ignorados por git.<br>
![5.3](img/8.png)<br>
  - He creado un documento **.gitignore** y le he dado instrucciones de que ignore tanto la carpeta privada como el privado.txt.<br>
## Paso 6<br>

- Añadir fichero 1.txt al repositorio local.<br>
  ![6.1](img/9.png)<br>
    - Usando el comando touch he creado el  fichero 1.txt<br>

## Paso 7<br>
- Visualizar los commits realizados hasta el momento (el historial).<br>
![7.1](img/10.png)<br>
  - Usando git log consulto los cambios y veo que tengo tanto Innitial commit, que es el automático cuando github te crea el README.md, como el commit inicial, que es el que yo he hecho para que me suba los cambios de el susodicho documento.<br>
## Paso 8<br>
- Crear un tag v0.1.<br>
![8.1](img/11.png)<br>
  - Con el comando git tag he creado el tag v0.1<br>
## Paso 9<br>

- Subir los cambios al repositorio remoto.<br>
![9.1](img/12.png)<br>
  - De nuevo con git add . he añadido todos los ficheros, acto seguido he hecho un commit y luego un push.<br>

## Paso 10<br>
- Visualizar de nuevo los commits realizados hasta el momento (el historial).<br>
![10.1](img/13.png)<br>
  - Usando de nuevo el git log puedes ver  que hay un commit nuevo, llamado Second commit.<br> 
## Paso 11<br>

- Crear una tabla de este estilo en el fichero README.md
con la información del docente del módulo:<br>

|Nombre|Profesion|Institutos|Github|
|------|---------|----------|------|
|Máximo Fernández|Docente|Francesc de Borja Moll i CESUR|[maximofernandezriera](http://github.com/maximofernandezriera)|
<br>
![11.1](img/14.png)<br>
  - A la izquierda puedes ver como es en el propio código de Markdown y a la derecha como se verá en la página de portada del repositorio.<br>
## Paso 12<br>

- Poner a Máximo como colaborador del repositorio masterpidgey-examen<br>
![12.1](img/15.png)<br>
  -  Para añadir a un colaborador no tienes más que entrar a Settings, después abrir la pestaña de Collaborators y pulsar el botón verde que pone Add people.<br>
# Parte 2<br>

#### Tal y como vimos en la tarea correspondiente y siguiendo los pasos de este proyecto https://github.com/maximofernandezriera/first-contributions con el apoyo de la guía de DigitalOcean que conocemos https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github contribuye con algún cambio.<br>
# Proceso<br>
- Bifurca first contributions<br>
![1](img/16.png)<br>
  - Para bifurcar el repositorio debes darle al botón de fork que hay arriba a la izquierda. La imagen que yo he colgado muestra como está el documento una vez he hecho el fork <br>

- Clona el repositorio bifurcado<br>
![2](img/17.png)
  - De nuevo con git clone he clonado en mi sistema el repositorio,<br>
- Crea una rama (Branch)<br>
![3](img/18.png)<br>
  - Primero he abierto la carpeta y luego he creado una rama llamada add-marc-gomez.<br>
- Haz los cambios necesarios y confirma (Commit) esos cambios<br>
![4](img/19.png)<br>
  - He añadido un pequeño código de Python llamado Marcs_code que te indica si el día actual el par o impar.<br>
![5](img/20.png)<br>
  - En este caso he añadido específicamente Marcs_code.py, para no repetir lo mismo que puse anteriormente dos veces, e hice el commit llamándolo "Contribución de Marc Gómez Barceló".<br>

- Sube tus cambios a GitHub<br>
  ![6](img/21.png)
    - Con el comando git push los subo a Github.<br>

- Envía  tus cambios para ser revisados<br>
![7](img/22.png)
  - He añadido una pequeña descripción de lo que he hecho y he realizado el pull request.<br>