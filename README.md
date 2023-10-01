# DOCUMENTACION DE LA PRÁCTICA  
Pasos a seguir para realizar la practica  
## 1.Creación de cuenta en GitHub  
En primer lugar debemos crear una cuenta en GitHub. Para ello accedemos al enlace https://github.com.  
Cuando veamos una ventana como la siguiente, buscaremos **Sign Up** en la esquina superior derecha.  

![Imagen 01Sig Up](https://github.com/rcanoc07/imgs/blob/main/UT1/01signin/01pagina%20inicio.png)  

Una vez hayamos clicado, podremos ver un menú interactivo en el que introduciremos en primer lugar, nuestro **email**. Pulsaremos en el botón **Continue**.  

![Imagen 02email](https://github.com/rcanoc07/imgs/blob/main/UT1/01signin/02email.png)  

Seguidamente tendremos que añadir una **contraseña** y pulsar el botón de nuevo.  

![Imagen 03contraseña](https://github.com/rcanoc07/imgs/blob/main/UT1/01signin/03contraseña.png)  

A continuación introduciremos un **nombre de usuario**, que será válido si no está ya en uso en la plataforma.  

![Imagen 04email](https://github.com/rcanoc07/imgs/blob/main/UT1/01signin/04user.png)  

Tendremos la opcion de que nos manden correos electrónicos con novedades y otras noticias, en mi caso lo niego escribiendo **"n"**.  

![Imagen 05notificaciones](https://github.com/rcanoc07/imgs/blob/main/UT1/01signin/05notificaciones.png)  

Para confirmar la creación de la cuenta, tendremos que verificarla realizando un [Captcha](https://www.google.com/search?q=que+es+captcha&rlz=1C1RXQR_esES1031ES1031&oq=que+es+captcha&gs_lcrp=EgZjaHJvbWUyCQgAEEUYORiABDIHCAEQABiABDIHCAIQABiABDIHCAMQABiABDIHCAQQABiABDIHCAUQABiABDIHCAYQABiABDIHCAcQABiABDIHCAgQABiABDIHCAkQABiABNIBCDMwNTdqMGo3qAIAsAIA&sourceid=chrome&ie=UTF-8&safe=active&ssui=on&bshm=rime/1).  

![Imagen 07captcha](https://github.com/rcanoc07/imgs/blob/main/UT1/01signin/07captcha.png)  

Ya podremos pulsar en el boton verde **"Create account"** que confirmará la creación de la cuenta.  

![Imagen 08create_account](https://github.com/rcanoc07/imgs/blob/main/UT1/01signin/08create_account.png)  

Una vez terminado, tendremos que **revisar** un codigo de verificacion que nos mandan por **correo**, debajo aparece un boton verde que dice **"Open GitHub"**, pulsando en él y añadiendo el número que aparece, verificaremos la cuenta.   

![Imagen 09codigo_verificacion](https://github.com/rcanoc07/imgs/blob/main/UT1/01signin/09codigo_verificacion.png)  

Veremos un menú para personalizar nuestra experiencia según el uso que la vayamos a dar a la plataforma, en mi caso lo omito pulsando **"Skip personalization"**  

![Imagen 10omitir_personalizacion](https://github.com/rcanoc07/imgs/blob/main/UT1/01signin/10omitir_personalizacion.png)  

Depués de ver una animacion galáctica, podremos ver por fin nuestro perfil en GitHub.  

![Imagen 12pagina_principal](https://github.com/rcanoc07/imgs/blob/main/UT1/01signin/12pagina_principal.png)

## 2.Crear repositorio vacio
Una vez estamos en la pantalla de la imagen anterior, nos fijaremos en la **zona central**, exactamente en el apartado **"Start a new repository"**. Añadiremos un nombre al repositorio, en mi caso **"ed"**, que son las siglas de Entornos de Desarrollo; y elegiremos la opcion **"Private"**, para que el repositorio solo sea visible por nosotros mismo y por las personas que nosotros añadamos como colaboradores.

![Imagen 13crear_repositorio](https://github.com/rcanoc07/imgs/blob/main/UT1/01signin/13crear_repositorio.png)  

>+ Para añadir colaboradores:
>   + Vamos a los ajustes del repositorio y buscamos el apartado **"Collaborators"**
>   + Pulsamos en **"Add people"**
>   + Introducimos el usuario del colaborador que vamos a añadir. En mi caso tengo que añadir a `luiscastelar`.

Cuando confirmemos la creación, veremos las instrucciones que tenemos que seguir para crear un nuevo repositorio o subir uno ya existente. En mi caso como es el primero, crearé uno nuevo, pero antes debemos tener instalada la aplicación **Git** en nuestro equipo.

### INSTALACIÓN GIT
1. En primer lugar, accederemos a este enlace: https://git-scm.com/downloads.
2. Seleccionaremos el sistema operativo que tenemos, en mi caso Windows.  
3. Ejecutaremos el archivo que se descarga y aparecerá el asistente de instalación.  
>*(Solo aparecen las pantallas en las que hay que cambiar parametros, las que no aparecen hay que pasarlas sin modificar nada)*.  

En la primera pantalla pulsaremos **Next** para empezar con la instalación.  

![Imagen 01install](https://github.com/rcanoc07/imgs/blob/main/UT1/02installgit/01.png)  

Seleccionaremos el editor de texto **nano** y pulsaremos sobre **Next**.

![Imagen 02nano](https://github.com/rcanoc07/imgs/blob/main/UT1/02installgit/02.png)  

En la siguiente pantalla, seleccionaremos la segunda opción para no dejar que Git decida por si que brach utilizar, lo haremos de forma manual nosotros, llamandola **`main`**.  

![Imagen 03brach](https://github.com/rcanoc07/imgs/blob/main/UT1/02installgit/03.png)  

Llegaremos al final de la configuración cuando veamos la siguiente pantalla en la que pulsaremos **Install**.

![Imagen 05install](https://github.com/rcanoc07/imgs/blob/main/UT1/02installgit/05.png)  

Una vez se complete la barra de progreso, veremos la ultima pantalla, en la que marcaremos las opciones como en la imagen y pulsaremos **Finish** para lanzar Git.  

![Imagen 06finish](https://github.com/rcanoc07/imgs/blob/main/UT1/02installgit/06.png)  

### VINCULAR REPOSITORIOS
Para poder vincular los repositorios, antes que nada debemos asociarlos con una **clave SSH**.  
Para ello ejecutamos la aplicacion **Git GUI** y pulsamos en **Help**; seguidamente en **Show SSH Key**.  

![Imagen 01help](https://github.com/rcanoc07/imgs/blob/main/UT1/03vincrepo/01.png)  

En una pequeña ventana veremos una clave con bastantes caracteres; la tenemos que copiar al portapapeles.  
*Si no aparece ninguna clave tendremos que pulsar en **Generate Key**.*  

![Imagen 02sshkey](https://github.com/rcanoc07/imgs/blob/main/UT1/03vincrepo/02.png)  

Ahora debemos ir a nuestro **perfil de GitHub** en la web e irnos a los **ajustes** de nuestro perfil.  

![Imagen 03settings](https://github.com/rcanoc07/imgs/blob/main/UT1/03vincrepo/03.png)  

Deberiamos ver un botón que diga **New SSH Key**, pulsaremos sobre él.  
>*En la captura ya aparecen varias claves asociadas, ya que a la hora de realizar la captura, ya estaba la práctica hecha y la documentacion esta siendo realizada en otros dispositvos* 

![Imagen 04newkey](https://github.com/rcanoc07/imgs/blob/main/UT1/03vincrepo/04.png)  

Copiaremos en el campo de la clave,  la clave que tenemos en el portapapeles y pulsamos en **Add SSH Key**.  

![Imagen 05sshkey](https://github.com/rcanoc07/imgs/blob/main/UT1/03vincrepo/05.png)  

Ya tendriamos el dispositivo vinculado mediante SSH con el repositotio.
  
## 3.Crear Git Local  
Una vez tengamos los programas instalados, abrimos **Git Bash** y configuraremos nuestro usuario con los siguientes comandos:
```  
git config --global user.name "username"
git config --global user.email "email"
```  
Tendremos que sustituir los valores entre comillas por nuestro nombre de usuario y correo asociado; `rcanoc07` y `rcanoc07@iescastelar.com` respectivamente, en mi caso.  

![Imagen 001configurarusernameemail](https://github.com/rcanoc07/imgs/blob/main/UT1/04bash/001.png)  

El siguiente paso sera situarnos en la carpeta de nuestro equipo en la que vamos a iniciar el repositorio. Lo haremos usando los comandos:  
```  
mkdir  
cd   
```  

![Imagen 02crearcarpeta](https://github.com/rcanoc07/imgs/blob/main/UT1/04bash/002.png)  

Ahora copiaremos y pegaremos el codigo que GitHub nos facilita para crear nuestro repositorio, con nuestra información ya incluida:
```  
echo "# ed" >> README.md  
git init  
git add README.md  
git commit -m "first commit"  
git branch -M main  
git remote add origin git@github.com:rcanoc07/ed.git  
git push -u origin main  
```  
+ Este fragmento de código:
    1. Crea un archivo README.md que incluye el nombre del repositorio
    2. Inicia el repositorio.
    3. Añade README.md al estado de espera.
    4. Crea el primer commit.
    5. Selecciona la rama *main* como principal.
    6. Añade el origen del repositorio remoto **rcanoc07/ed**.
    7. Sincroniza estos cambios con el repositorio remoto.

Como resultado veremos lo siguiente:  

![Imagen 03resultcopypaste](https://github.com/rcanoc07/imgs/blob/main/UT1/04bash/003.png)  
  
## 4.Crear README.md
Con las instrucciones anteriores, se nos crea un archivo README.md, que incluye el nombre del repositorio por defecto. Vamos a editarlo y a incluir en él, el **nombre de usuario** y el **correo corporativo @iescastelar.com**.  
Para ello lo abrimos con el editor nano.  

![Imagen 04abrirreadme](https://github.com/rcanoc07/imgs/blob/main/UT1/04bash/004.png)  

Una vez abierto, podremos borrar la línea que contiene e incluir nuestros datos. Una vez este modificado, pulsaremos `Ctrl+o` para guardar, `Intro` para confirmar el nombre y `Ctrl+x` para salir.  

![Imagen 05resultadoreadme](https://github.com/rcanoc07/imgs/blob/main/UT1/04bash/005.png)  

### 4.1.Crear README.md para documentar la práctica  
El siguiente paso es crear una carpeta llamada UT1, y dentro de ella crear un archivo para documentar la práctica.  
Para ello ejecutamos los siguientes comandos:
```  
mkdir UT1  
cd UT1/  
echo "DOCUMENTACION DE LA PRACTICA" >> README.md  
```  
Añado al archivo la frase "DOCUMENTACION DE LA PRACTICA" para identificarlo mejor posteriormente y una vez creado el archivo, compruebo su contenido utilizando
```  
cat README.md  
```  

![Imagen 06UT1/README.md](https://github.com/rcanoc07/imgs/blob/main/UT1/04bash/005.png)  

## 5.Clonacion del repositorio  
Ahora tenemos que clonar el repositorio a otra carpeta; en mi caso lo voy a clonar en una carpeta llamada clonación, ubicada en la carpeta repositorios. Para ello tenemos que seguir estos pasos:  
+ Ubicarnos en la carpeta *repositorios*  
+ Crear y acceder a la carpeta *clonacion*  
+ Clonar el repositorio

Usaremos el siguiente comando para realizar la clonacion:  
```  
git clone git@github.com:rcanoc07/ed.git  
```  
Una vez realizados los pasos podemos ver con el comando **ls** que dentro se ha guardado una copia del repositorio.  

![Imagen de la clonacion del repositorio](https://github.com/rcanoc07/ed/blob/main/UT1/img/repoclone.png)  

>*Esta imagen es la que se solicita en la practica*  

Se nos pide tambien que la subamos al directorio **./img**, asi que creamos dicho directorio y la subimos aplicando los siguientes comandos.

![Imagen 08 subir imagen a ./img](https://github.com/rcanoc07/imgs/blob/main/UT1/04bash/008.png)

Una vez tenemos almaceneda la foto, aplicamos los siguientes comandos:
```  
git add repoclone.png  
git commit -m ".img/repoclone.png"  
git push  
```  
>*En mi caso no existe este commit, por que lo hice junto a otros cambios*

Seguidamente accedemos al repositorio remoto desde la web y podremos observar la foto subida en el directorio `ed/UT1/img/`. Hacemos clic derecho sobre ella y podremos copiar su direccion de enlace.

![Imagen 12 Copiar enlace](https://github.com/rcanoc07/imgs/blob/main/UT1/04bash/012.png)

Ahora accederemos al README.md dedicado a la documentación de la práctica e incluimos la siguiente sentencia para enlazar la captura.
```  
![nombre_identificador](enlace_imagen)  
```

![Imagen 13 Foto enlazada](https://github.com/rcanoc07/imgs/blob/main/UT1/04bash/013.png)  
  
## 6.Crear archivo a.txt y sincronizar con el repositorio
Crearemos el archivo a.txt y lo editaremos con el editor **nano**. Incluiremos 3 líneas y lo guardaremos.

![Imagen 15 a.txt](https://github.com/rcanoc07/imgs/blob/main/UT1/04bash/015.png)  

Lo sincronizaremos con el repositorio remoto.
```  
git add a.txt  
git commit -m "añadido a.txt"  
git push  
```  

![Imagen 16 Sincronizar a.txt](https://github.com/rcanoc07/imgs/blob/main/UT1/04bash/016.png)

## 7.Modificar una línea en local y otra en web e intentar sincronizar
Una vez sincronizados los archivos, tendremos la **misma vesión** en **local** y en **remoto**. Modificaremos el **local** con el editor **nano** desde Git Bash, y el **web** accediendo mediante su interfaz grafica y activando el modo edicion con el **boton del lapíz**. Deberiamos tener algo similar a esto:

![Imagen 18 Modificar a.txt](https://github.com/rcanoc07/imgs/blob/main/UT1/04bash/018.png)

Desde la web, aparece un botón verde con el texto **Commit changes**, lo pulsamos para hacer un commit del archivo modificado en la web y le ponemos el comentario **"Update web a.txt"**. Debemos hacer lo mismo con el archivo en local, para ello hay que aplicar los mismos comandos que antes, pero modificaremos el comentario del commit:
```  
git add a.txt  
git commit -m "update local a.txt"  
git push  
```  
Cuando se ejecute el `push` veremos el siguiente error:

![Imagen 19 Modificar a.txt](https://github.com/rcanoc07/imgs/blob/main/UT1/04bash/019.png)

## 8.Solucionar el conflicto
La forma de solucionar el conflicto que he encontrado ha sido realizar un ```git pull```, de esta forma se sincroniza el documento local con el remoto, quedando el local con ambas modificaciones; y realizando a continuacion un ```git push``` para sincronizar el remoto con el local, que ya tenia todas las modificaciones. Podemos comprobar la veracidad de esta acción comprobando después del `git push` con un `cat a.txt`.

![Imagen 20 git push cat a.txt](https://github.com/rcanoc07/imgs/blob/main/UT1/04bash/020.png)

Como podemos ver en la imagen anterior, se realiza un `auto-merge`, por lo que no tendriamos que realizarlo de nuevo.
## 9.Captura de línea del tiempo
Para visualizar las líneas del tiempo existen varias aplicaciones, en mi caso voy a utilizar **GitFiend**. Esta aplicación se encuentra en Microsoft Store, por lo que solo tenemos que buscarla y pulsar sobre **Obtener**.

![Imagen 21 Obtener GitFiend](https://github.com/rcanoc07/imgs/blob/main/UT1/05gitfiend/04.png)

Una vez instalada, la iniciamos y abrimos el directorio del repositorio, para que detecte los archivos y pueda mostrarnos una línea del tiempo de nuestros archivos.

![Imagen 22 Línea del tiempo](https://github.com/rcanoc07/imgs/blob/main/UT1/05gitfiend/05.png)

>*En la imagen aparecen los commits creados hasta el momento en el que se está documentando esto, por la perdida de la imagen*

## 10.Regresa al punto 7 en la línea del tiempo y muestra el contenido de a.txt

En la siguiente imagen podemos ver el contenido que tiene el documento a.txt en ese punto de la línea del tiempo.

![Imagen 23 a.txt](https://github.com/rcanoc07/imgs/blob/main/UT1/05gitfiend/06.png)
