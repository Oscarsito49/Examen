
# Examen primera evaluación
## Ejercicio 3

### Índice:
[-Creación](#Creación)  
[-Configuración](#Configuración-del-archivo-de-configuración-virtualHost)  
[-Activación](#Activación-del-archivo-VirtualHost)  
[-Galeria Ejercicio 3](#Biblioteca-de-capturas-de-pantalla-ejercicio3)  

### Creación
El primer paso es crear la carpeta en la cual tendremos la página web.
![CleanShot 2024-11-11 at 16 59 15@2x](https://github.com/user-attachments/assets/83001bf6-e5fa-49d0-abad-b8a19a6fa2e5)  

El siguiente paso es crear y editar un index.html dentro de la carpeta donde alojamos la web.
![CleanShot 2024-11-11 at 17 03 25@2x](https://github.com/user-attachments/assets/25f50c92-18a8-448c-bfbc-59e920a3ec24)  

Esto es lo que pondremos dentro (es un mensaje generico solo de prueba:  
![html](https://github.com/user-attachments/assets/f2212f0e-aa13-4206-bbf9-a41ec8e85089)  

### Configuración del archivo de configuración virtualHost
Lo primero es entrar en el directorio de archivos de configuración de la siguiente manera:  
![CleanShot 2024-11-11 at 17 05 58@2x](https://github.com/user-attachments/assets/3c590eef-c6d7-49c6-a129-e079edd19402)  

Lo siguiente es hacer que el archivo default de virtualHost coincida con el nuestro:  
![CleanShot 2024-11-11 at 17 07 01@2x](https://github.com/user-attachments/assets/e3d6d03b-f022-4241-97b5-af8af08e9961)  

Y ahora procedemos a editarlo: 
![CleanShot 2024-11-11 at 17 07 36@2x](https://github.com/user-attachments/assets/8cdf763e-b9d8-4b3b-bd06-980411ee87bc)  

Así se ve el editor:  
![92conf](https://github.com/user-attachments/assets/bc9462e9-e205-4642-8050-452f066babe1)  
En este paso lo que hemos hecho ha sido:
* Configurar el `ServerName` del default a "daw.ejercicio3.com".
* Configurar el `ServerAdmin` a nustro correo electronico.
* Confifgurar el `DocumentRoot` con la ruta que hemos creado al principio.

Procedemos a abrir `/etc/hosts/` para añadir el ServerName que hemos puestro a nuestra IP.
![hosts](https://github.com/user-attachments/assets/eafbf79f-fba6-4864-ad2d-745e0066f788)  

### Activación del archivo VirtualHost
Por último deberemos de activar el VirtualHost con el siguiente comando y recibira una confirmación:  
![CleanShot 2024-11-11 at 17 13 22@2x](https://github.com/user-attachments/assets/67818ac1-f3d2-48dc-b343-ca5857292911)  

### Biblioteca de capturas de pantalla ejercicio3: 
![terminal](https://github.com/user-attachments/assets/75321fbb-0a78-4f1a-a02a-17658e590577)  

![92conf](https://github.com/user-attachments/assets/f31c508e-54fd-44f6-9125-eaa456115967)  

![hosts](https://github.com/user-attachments/assets/e53ce7a3-25cc-44e7-a69b-74afa883dd89)  

![html](https://github.com/user-attachments/assets/b89d81ac-cd7f-479a-b018-da250a3437d3)



## Bibliografía
[Configuración](https://ubuntu.com/tutorials/install-and-configure-apache#1-overview)  





