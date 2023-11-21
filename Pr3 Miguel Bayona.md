# Practica 3 - GIT 
## Historial de Cambios - Ramas

![](https://victorhckinthefreeworld.files.wordpress.com/2016/09/git_commit_fire.png?w=1024)

El historial de cambios se visualiza con la orden:
````
$git log

ó 
$git log --oneline
````
Para las ramas:
````
$git branch : mostrar ramas existentes
$git branch [name] : crear rama [name]
$git branch -d [name] : borrar rama [name]
$git checkout [name] : moverme a rama [name]
$git merge [name] : fusionar la rama actual con [name] 
$git log --oneline
````

1. Entrad en el directorio de la práctica2 (practica2git) y a partir de ahí realizaremos esta práctica

2. Cread la carpeta "unidades". 

    <img src="C:\Users\dam_bdpm\Videos\prt3\Imagen1.png">
    
3. Cread 2 Ramas, Windows y Ubuntu.

    <img src="C:\Users\dam_bdpm\Videos\prt3\Imagen2.png">

4.  Situaos en Windows y dentro de ella cread un fichero llamado windows1.txt con el siguiente texto:
```
Windows es el nombre de una familia de distribuciones de software para PC, teléfonos inteligentes, servidores y sistemas empotrados, desarrollados y vendidos por Microsoft y disponibles para múltiples arquitecturas, tales como x86, x86-64 y ARM.
```
<img src="C:\Users\dam_bdpm\Videos\prt3\Imagen3.png">

5. Añadid los cambios realizados a la zona de preparado
<img src="C:\Users\dam_bdpm\Videos\prt3\Imagen5.png">
 
6. Haced un commit con el comentario "Añadido fichero windows1"
<img src="C:\Users\dam_bdpm\Videos\prt3\Imagen6.png">

7. Mostrad de nuevo el historial de cambios del repositorio + push
<img src="C:\Users\dam_bdpm\Videos\prt3\Imagen7.png">
<img src="C:\Users\dam_bdpm\Videos\prt3\Imagen8.png">

8. Cambiad a la rama Ubuntu y dentro de ella cread un fichero llamado ubuntu1.txt con el siguiente texto:
```
Ubuntu es una distribución GNU/Linux basada en Debian GNU/Linux, que incluye principalmente software libre y de código abierto. Puede utilizarse en ordenadores y servidores. Está orientado al usuario promedio, con un fuerte enfoque en la facilidad de uso y en mejorar la experiencia del usuario.
```
<img src="C:\Users\dam_bdpm\Videos\prt3\Imagen9.png">

9. Añadid los cambios realizados a la zona de preparado
10. Haced un commit con el comentario "Añadido fichero windows1"
<img src="C:\Users\dam_bdpm\Videos\prt3\Imagen10.png">

11. Mostrad de nuevo el historial de cambios del repositorio + push
<img src="C:\Users\dam_bdpm\Videos\prt3\Imagen11.png">
<img src="C:\Users\dam_bdpm\Videos\prt3\Imagen12.png">

12. Volved a Windows y cread el fichero "windows2.txt" dentro de "unidades" con el texto:
````
Desde un punto de vista técnico, no son sistemas operativos, sino que contienen uno (tradicionalmente MS-DOS, o el más actual cuyo núcleo es Windows NT) junto con una amplia variedad de software; no obstante, es usual (aunque no necesariamente correcto) denominar al conjunto como sistema operativo en lugar de distribución. Microsoft introdujo un entorno operativo denominado Windows el 20 de noviembre de 1985 como un complemento para MS-DOS en respuesta al creciente interés en las interfaces gráficas de usuario (GUI).2​ Microsoft Windows llegó a dominar el mercado mundial de computadoras personales, con más del 90 % de la cuota de mercado, superando a Mac OS, que había sido introducido en 1984.

````
<img src="C:\Users\dam_bdpm\Videos\prt3\Imagen13.png">

13. Añadid los cambios a la zona de preparado
14. Haced commit de cambios con el comentario "añadido windows2.txt"
<img src="C:\Users\dam_bdpm\Videos\prt3\Imagen14.png">

15. Mostrad las diferencias entre los dos últimos commits de esta rama.
<img src="C:\Users\dam_bdpm\Videos\prt3\Imagen15.png">
<img src="C:\Users\dam_bdpm\Videos\prt3\Imagen16.png">

16. Añadid al fichero windows2.txt las lineas:
```
La versión más reciente de Windows es Windows 10 para equipos de escritorio, Windows Server 2019 para servidores y Windows 10 Mobile para dispositivos móviles. La primera versión en español fue Windows 2.1.
```
<img src="C:\Users\dam_bdpm\Videos\prt3\Imagen18.png">

17. Añadid los cambios a la zona de preparado
<img src="C:\Users\dam_bdpm\Videos\prt3\Imagen19.png">

18. Haced commit de los cambios con el comentario "Añadidas versiones a windows2.txt"
<img src="C:\Users\dam_bdpm\Videos\prt3\Imagen20.png">

19. Mostrad quien ha hecho cambios en el fichero windows2.txt
<img src="C:\Users\dam_bdpm\Videos\prt3\Imagen21.png">

20. Situaos en Master y haced merge para que quede todo en una única rama.
<img src="C:\Users\dam_bdpm\Videos\prt3\Imagen22.png">

21. Borrad las 2 ramas restantes
<img src="C:\Users\dam_bdpm\Videos\prt3\Imagen23.png">

22. Descargad el programa SourceTree y añadid el repositorio con el que estais trabajando para ver el eje cronológico
<img src="C:\Users\dam_bdpm\Videos\prt3\Imagen24.png">


<a href="https://github.com/bayonaa/Practica2Git">enlace al github</a><br>
Los fucheros que windows1.txt y ubuntu1.txt que estan junto a contenido.txt los he subido al principio pero los he tenido que borrar por un error.