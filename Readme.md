Descarga la imagen "alpine" SIN ARRANCARLA y comprueba que está en tu equipo

sudo docker pull alpine

Comprobar: sudo docker images alpine


Crea un contenedor sin ponerle nombre. ¿está arrancado? Obtén el nombre

docker run -d alpine

docker ps (Muestra solo los arrancados por eso no lo muestra por lo tanto no está arrancado)
El nombre es reverent_hodgkin

Crea un contenedor con el nombre 'dam_alp1'. ¿Como puedes acceder a él?

sudo docker run -dit --name dam_alp1 alpine

Acceder a el contenedor:

sudo docker exec -it dam_alp1 sh


Comprueba que ip tiene y si puedes hacer un ping a google.com


ping google.com

ip=Se comprueba con el ping (216.58.209.78)

Crea un contenedor con el nombre 'dam_alp2'. ¿Puedes hacer ping entre los contenedores?



Sal del terminal, ¿que ocurrió con el contenedor?


¿Cuanta memoria en el disco duro ocupaste?


¿Cuanta RAM ocupan los contenedores? ¿Hay algún comando docker para saber esto?.
