# LABORATORIO 1 CVDS

## PARTE I (Trabajo Individual).

### 1. Crea un repositorio localmente.

![Imagen punto 1](Images/1.png)

### 2. Agrega un archivo de ejemplo al repositorio, el README.md puede ser una gran opción.

![Imagen punto 2](Images/2.png)

### 3. Averigua para qué sirve y como se usan estos comandos git add y git commit -m “mensaje”

	- git add. Mueve los cambios del directorio de trabajo al área del entorno de ensayo.
	- El comando git commit captura una instantánea de los cambios preparados en ese momento del proyecto.

### 4. Abre una cuenta de github, si ya la tienes, enlazala con el correo institucional.

![Imagen punto 4](Images/4.png)

### 5. Crea un repositorio en blanco (vacío) e GitHub.

![Imagen punto 5](Images/5.png)

### 6. Configura el repositorio local con el repositorio remoto.

![Imagen punto 6](Images/6.png)

### 7. Sube los cambios, teniendo en cuenta lo que averiguaste en el punto 3 Utiliza los siguientes comando en el directorio donde tienes tu proyecto, en este orden:

![Imagen punto 7](Images/7.png)

### 8. Configura el correo en git local de manera correcta 

![Imagen punto 8](Images/8.png)

### 9. Vuelve a subir los cambios y observa que todo esté bien en el repositorio remoto (en GitHub)

![Imagen punto 9](Images/9.png)


## PARTE II (Trabajo en parejas)


### 1. Se escogen los roles para trabajar en equipo, una persona debe escoger ser "Owner" o Propietario del repositorio y la otra "Collaborator" o Colaborador en el repositorio.

	- Owner: Sebastián Villarraga
	- Colaborador: Andres Sepúlveda

### 2. El owner agrega al colaborador con permisos de escritura en el repositorio que creó en la parte 1
   
![image](https://github.com/user-attachments/assets/a8107871-6035-4709-b13e-962c14975a7c)


### 3. El owner le comparte la url via Teams al colaborador

   ![image](https://github.com/user-attachments/assets/96bb9c76-5956-4b76-824e-dfe326dd281b)

### 4. El colaborador acepta la invitación al repositorio

### 5. Owner y Colaborador editan el archivo README.md al mismo tiempo e intentan subir los cambios al mismo tiempo.
   
   ![image](https://github.com/user-attachments/assets/2a0fc603-79a8-4b2c-b466-3532ddc72f82)
   ![image](https://github.com/user-attachments/assets/f3b55405-240d-4eee-8cb0-5c07582e054b)
   ![image](https://github.com/user-attachments/assets/8ba8b396-1401-4be0-a2d4-74f093927ea9)



### 6. ¿Qué sucedió?

    - cuando subimos los cambios desde GitHub al mismo tiempo ambos marcamos el commit con el nombre de cada uno a ver cual si se 
      guardaba, el de Sebastian Villarraga fue el que si se subio y el de Andres Sepulveda le arrojo los errores anteriores.
    - cuando subimos los cambios desde consola al mismo tiempo ambos marcamos el 'Git add .', el 'git commit' y el 'git push' al tiempo 
      con el nombre de cada uno a ver cual si se guardaba, el de Andres Sepulveda fue el que si se subio y el de Sebastian Villarraga le 
      arrojo el error anterior.
      
### 7. La persona que perdió la competencia de subir los cambios, tiene que resolver los conflictos, cúando haces pull de los cambios, los archivos tienen los símbolos <<< === y >>> (son normales en la resolución de conflictos), estos conflictos debes resolverlos manualmente.

![image](https://github.com/user-attachments/assets/59f2dfc0-e82b-4fa9-80a1-85165ee641eb)
![image](https://github.com/user-attachments/assets/f94059ad-f579-4f4f-af35-8a0dac332c1d)
![image](https://github.com/user-attachments/assets/fd6ddec6-5356-49e0-a032-718a65d7393c)

Eliminamos los simbolos <, =, >, la palabra 'HEAD' y solo conservamos los cambios remotos, luego de esto hicimos el git add, git commit y git push


### 8. Volver a repetir un cambio sobre el README.md ambas personas al tiempo para volver a tener conflictos.
![image](https://github.com/user-attachments/assets/2ae7c22b-4eb2-40ae-9432-e9ee0ec9c3ff)
![image](https://github.com/user-attachments/assets/4f63007b-d9a6-4ba9-bd91-77ac1b42f89b)


### 9. Resuelvan el conflicto con IntelliJ si es posible, Resolver conflictos en IntelliJ
    
![image](https://github.com/user-attachments/assets/4f9ba436-97e5-4fc3-8014-a52292d8373e)
![image](https://github.com/user-attachments/assets/690282dc-fe4a-47a7-b92b-f1f2c46e6162)
![image](https://github.com/user-attachments/assets/52852e94-d2eb-4791-935f-8b66828fc61e)

## Parte III (Trabajo de a parejas)
### 1. ¿Hay una mejor forma de trabajar con git para no tener conflictos?

Sí, lo primero es verificar siempre que mi repositorio local esté actualizado con el remoto, también que cuando se quiera trabajar en una nueva
funcionalidad se usen ramas separadas de la principal de esta forma se facilita la corrección de posibles errores y reduce la posibilidad de conflictos.
Además, es buena práctica realizar commits pequeños y descriptivos y hacer push regularmente para evitar que los compañeros realicen cambios en el mismo codigo antes que uno. 

### 2. ¿Qué es y como funciona el Pull Request?

Un Pull Request es una herramienta que nos permite proponer cambios a un repositorio si subirlos de una vez, de esta forma se puede colaborar y
revisar el código antes de integrarlo a la rama principal. 

### 3. Creen una rama cada uno y suban sus cambios
![image](https://github.com/user-attachments/assets/3b336a8c-d10e-472d-a237-59e1eb3224e3)

los cambios de las ramas son los siguientes:
- Andres
Prueba pull request en rama master
- Sebastian
aaaaaaaa

4. Tanto owner como colaborador hacen un cambio en el README.md y hacen un Pull Request (PR) a la rama main/master

   ![image](https://github.com/user-attachments/assets/2b4d453a-616b-43be-a096-419edf2e65a3)
   ![image](https://github.com/user-attachments/assets/027d3d23-81fc-45e1-863b-8664e10d2815)

5. Teniendo en cuenta la recomendación, mezclen los cambios a la rama main a través de PR con el check/review/approval del otro compañero (Cuando se hace merge se deberían borrar las ramas en github)

   ![image](https://github.com/user-attachments/assets/38e71ee0-6890-4ed6-a322-9b45d72b4967)
   ![image](https://github.com/user-attachments/assets/9054210c-e476-40ba-9e80-8f4e78b26da2)
   ![image](https://github.com/user-attachments/assets/1c5211fc-c305-4ddb-baab-f264b1d9cdd5)
   ![image](https://github.com/user-attachments/assets/16d39966-52da-4c23-b19e-5e8ac3f79fa1)
   ![image](https://github.com/user-attachments/assets/b574386b-d438-4048-970d-05d40fe4f386)
   ![image](https://github.com/user-attachments/assets/5a4ba758-dc79-4cf6-9069-47f2722e11c6)
   ![image](https://github.com/user-attachments/assets/e41130cc-1b2b-4c92-ae2f-045a4cfff3c1)

















