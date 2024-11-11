
# Examen primera evaluación

## Resumen
Este documento detalla el proceso del examen de la primera evaluación de despliegue de aplicaciones web. Se describen ejercicios como SSH virtualHost o como MarkDown (este propio documento). Al final, se ofrece una conclusión la cual incluye una valoración personal sobre el aprendizaje obtenido y las dificultades durante el examen.

##Palabras clave:
1. ****
2. ****
3. ****
4. ****
5. ****
6. ****

### Índice Global:
[-Resumen](#Resumen)  
[-Palabras clave](#Palabras-clave)  
[-Contexto](#Contexto)  
[-Motivación](#Motivación)
[-Ejercicio 2](#Ejercicio-2)
[-Ejercicio 3](#Ejercicio-3) 
[-Conclusión](#Conclusión) 
[-Bibliografía](#Bibliografía) 

## Contexto:
Este documento/examen se lleva a cabo en un entorno académico, en el cual los estudiantes aprenden (en esta asignatura) sobre despliegue de aplicaciones web. El objetivo de esta actividad es redactar el examen realizado.
 
## Motivación: 
El motivo principal de este documento es redactar el proceso del examen con algunos detalles personales. Este documento nos ayudara de cara al restultado del examen para poder aprender de nuestros errores y corregirlos. 


## Ejercicio 2

### Índice Ejercicio 2:
[-Creación](#Creación)  
[-Configuración](#Configuración-del-archivo-de-configuración-virtualHost)  
[-Activación](#Activación-del-archivo-VirtualHost)  
[-Galeria Ejercicio 3](#Biblioteca-de-capturas-de-pantalla-ejercicio3)  

### Conexión
El primer paso es conectarse al otro equipo (nos deberia de salir un mensaje de confrmación):  
![CleanShot 2024-11-11 at 17 38 49@2x](https://github.com/user-attachments/assets/0f54b78b-6a8c-415b-8a90-9491d3664fd9)  

### Comando `whoami` para ver quienes somos (en nuestro caso nos devuelve "usuario"): 
![CleanShot 2024-11-11 at 17 40 45@2x](https://github.com/user-attachments/assets/a914bbed-a4bc-49d5-9b2f-007f2f69b288)

### Entrar al Escritorio y ver que archivos hay:  
![CleanShot 2024-11-11 at 17 41 35@2x](https://github.com/user-attachments/assets/747f4b35-d9db-4385-ae94-6f1881f4024f)  

### Crear el documento y modificarlo: 
![CleanShot 2024-11-11 at 17 42 11@2x](https://github.com/user-attachments/assets/ad7d23ba-4f61-49c1-a56b-1b298d543725)  

### Comprobar que ahora sale el nuestro: 
![CleanShot 2024-11-11 at 17 42 57@2x](https://github.com/user-attachments/assets/98f2134a-0770-448b-8ba8-f4e8f2a800a5)  

### Resultado:  
![ej2 resultado](https://github.com/user-attachments/assets/0b8e3410-079a-4665-a466-63ee95c8ec89)

### Biblioteca de capturas de pantalla ejercicio3: 
![Ejercicio2bueno](https://github.com/user-attachments/assets/560cebba-0d37-4eca-a79b-ec3be0d2b99c)  

![ej2 resultado](https://github.com/user-attachments/assets/2e494c48-5a9f-4cfd-a7ac-2c2da202df9a)  


## Ejercicio 3

### Índice Ejercicio 3:
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

## Conclusión  
En general me ha parecido un examen muy entretenido. Aunque tengamos la teoria a disposición no puedes venir sin tener ni idea ya que te encuentras con problemas que tienes que saber resolver. Aún con el chuletario me parece que ha estado a buen nivel el examen. La teoria me ha costado un poco ya que habia algún tecnicismo que no sabía. En mi opinión muy buen examen con muy buenos contenidos 10/10.

## Bibliografía
* [Configuración](https://ubuntu.com/tutorials/install-and-configure-apache#1-overview)  
* [Practica Por Parejas](https://github.com/Oscarsito49/prueba/blob/master/apache.md)




