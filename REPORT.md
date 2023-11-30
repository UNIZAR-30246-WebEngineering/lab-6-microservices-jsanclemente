Una vez hemos hecho fork del repositorio: https://github.com/UNIZAR-30246-WebEngineering/lab6-microservices-config-repo  a nuestro github, lanzamos el descubridor de servicios y a continuación, los servicios accounts y web.
![](/Users/jsanclemente/Desktop/lab-6-microservices-jsanclemente/Captura de pantalla 2023-11-30 a las 20.24.16.png)

![](/Users/jsanclemente/Desktop/Captura de pantalla 2023-11-30 a las 20.33.04.png)

A continuación, verificamos en el dashboard que efectivamente estos servicios han sido descubiertos por Eureka:

![Captura de pantalla 2023-11-30 a las 20.25.01.png](Captura%20de%20pantalla%202023-11-30%20a%20las%2020.25.01.png)

Ahora, es momento de modificar la configuración en nuestro repo de config que hemos forkeado, para que el servicio
accounts utilice el puerto 3333.

![](/Users/jsanclemente/Desktop/Captura de pantalla 2023-11-30 a las 20.37.34.png)

Y al volver a lanzar el servicio accounts comprobamos que ahora el puerto que esta utilizando es el 3333:

![](/Users/jsanclemente/Desktop/Captura de pantalla 2023-11-30 a las 20.39.11.png)