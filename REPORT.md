Una vez hemos hecho fork del repositorio: https://github.com/UNIZAR-30246-WebEngineering/lab6-microservices-config-repo  a nuestro github, lanzamos el descubridor de servicios y a continuación, los servicios accounts y web.

![](<docs/Captura de pantalla 2023-11-30 a las 20.15.52.png>)

![](<docs/Config server.png>)

A continuación, verificamos en el dashboard que efectivamente estos servicios han sido descubiertos por Eureka:
![](<docs/Captura Eureka.png>)

Ahora, es momento de modificar la configuración en nuestro repo de config que hemos forkeado, para que el servicio
accounts utilice el puerto 3333.

![](<docs/Captura Config-repo.png>)

Y al volver a lanzar el servicio accounts comprobamos que ahora el puerto que esta utilizando es el 3333:

![](<docs/Captura Eureka.png>)


