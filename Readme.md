# TAREA 2 

### **Descarga la imagen "alpine" SIN ARRANCARLA y comprueba que está en tu equipo**


```bash
 sudo docker pull alpine 
```
**Comprobar:**
```bash
sudo docker images alpine
```
### **Crea un contenedor sin ponerle nombre. ¿está arrancado? Obtén el nombre**

**Creación del contenedor:**

```bash
docker run -d alpine
```

**Comprobación de si está arrancado:**

```bash
docker ps 
```
(Este comando muestra solo los arrancados, no lo muestra por lo tanto no está arrancado)

Para ver todos los contenedores utilizamos el mismo comando con la opcion de all, (-a)

```bash
docker ps -a
```

![salidaterminal](img/image-4.png)



**El nombre es *reverent_hodgkin***
