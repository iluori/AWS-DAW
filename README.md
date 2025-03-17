# AWS-DAW

Tienes que tener una clave de acceso a AWS Academy. En este caso entramos como “Student Login".

![Texto alternativo](./img/Picture1.png)

Hay que entrar con tu usuario y contraseña.

![Texto alternativo](./img/Picture2.png)

Le das a "Panel de Control" y seleccionas "curso".

![Texto alternativo](./img/Picture3.png)

Para activar AWS, en la página principal de Contenidos, seleccionas “Lanzamiento del Laboratorio para el alumnado de AWS Academy”. 

![Texto alternativo](./img/Picture4.png)

Una vez dentro en el botón Start Lab esperas a que inicialice, lo sabrás cuando al lado AWS se ponga la luz de color verde y aparezca un contador. No te olvides de darle a End Lab cuando termines para no gastar créditos innecesarios.

![Texto alternativo](./img/Picture5.png)
![Texto alternativo](./img/Picture6.png)

Le das a AWS

![Texto alternativo](./img/Picture7.png)

Buscas VPC y le das a crear VPC

![Texto alternativo](./img/Picture8.png)

Ponemos los siguientes items y le das a crear VPC

![Texto alternativo](./img/Picture9.png)

La vemos en "sus VPC"

![Texto alternativo](./img/Picture10.png)

Ahora vamos a crear dos subred.Damos al apartado Subredes y ahí al botón a la derecha que pone Creae Subred.
Rellenamos todo a nuestro gusto.

![Texto alternativo](./img/Picture11.png)

Y le das a agregar una nueva subre. Rellenas y le das a crear.

![Texto alternativo](./img/Picture12.png)
![Texto alternativo](./img/Picture13.png)

Deben aparecerte en tus Subredes.
Ahora vamos a crear una puerta de enlace a internet.

![Texto alternativo](./img/Picture14.png)

Rellenas con un nombre y le das a crear.

![Texto alternativo](./img/Picture15.png)
![Texto alternativo](./img/Picture16.png)

Le das a conectar a la VPC

![Texto alternativo](./img/Picture17.png)

Y conectas el Gateway

![Texto alternativo](./img/Picture18.png)
![Texto alternativo](./img/Picture19.png)

Ahora nos dirigimos a la sección Tablas de enrutamiento que hay a la izquierda en el Panel de VPC y le damos a Crear una tabla de enrutamiento. Ponemos un nombre, seleccionamos nuestra VPC y le damos a crear.

![Texto alternativo](./img/Picture20.png)

Buscamos en el buscados EC2 y le clicamos. Queremos lanzar una instancia. 

![Texto alternativo](./img/Picture21.png)
![Texto alternativo](./img/Picture22.png)
![Texto alternativo](./img/Picture23.png)

Volvemos a VPC. Entramos en subredes y cogemos la primera que hicimos, le damos a acciones y seleccionamos Editar la asociación de la tabla de enturamiento para poner la nuestra.

![Texto alternativo](./img/Picture24.png)

Volvemos a EC2 al apartado de instancias para conectarnos a la que habíamos creado.

![Texto alternativo](./img/Picture25.png)

Le doy a conectar para hacer la prueba con la misma cosa del ordenador (no SSH). Hacemos ping 8.8.8.8 y si devuelve cosas es que hay internet. Para actualizar ponemos sudo apt upgrade en el ubuntu. 
