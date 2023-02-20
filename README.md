# TutorialGIT
1- Para subir nuestro proyectos como repositorios en GitHub, debemos:
2- Dirigirnos a nuestro perfil de GitHub, y hacer clic en repositories
![image](https://user-images.githubusercontent.com/124592235/220131146-10cf87a9-2ebb-4b34-be7c-839d122ad9a8.png)
3- Luego clic en New:
![tempsnip](https://user-images.githubusercontent.com/124592235/220132062-e4a73b8b-b96b-4b39-a831-6a7e63125618.png)
4- Después nombramos nuestro repositorio, chequemos en "Add a README file" y crear repositorio
![nombre](https://user-images.githubusercontent.com/124592235/220134342-54f709f0-6c80-4415-beac-5b3df7a4d717.png)
5- Una vez creamos el nombre de nuestro proyecto: 
*clic en "CODE"
![tempsnip](https://user-images.githubusercontent.com/124592235/220134420-3ae4bf0a-1c78-4170-9110-9969fdcfeccf.png)
*clic en "SSH" y después copiar el link:
![ssh](https://user-images.githubusercontent.com/124592235/220134769-74da89d7-9559-4bdd-a9c5-92cbaba9bb67.png)

6- Después de copiar el link, procedemos a abrir nuestro proyecto con git bash
*Para eso damos clic derecho sobre  nuestra carpeta y luego en la opción 
![git bash](https://user-images.githubusercontent.com/124592235/220127403-59e93272-6ef9-451b-9389-9b168fb07544.png)
7- Cuando estemos en la consola de Git Bash, escribimos los siguentes comandos:
1. git init
*y oprimimos la tecla "enter" del teclado
2. git remote add origin y pegamos nuestro link de "SSH" 
*clic derecho "PEGAR" y "ENTER" del teclado
3. git fetch origin main
"ENTER" del teclado
4. git pull origin main
"ENTER"
5. git add .
"ENTER"
6. git commit -m "Proyecto" <---- *Aquí nombramos nuestro proyecto (con las comillas)
"ENTER"
7. git push -u origin main
"ENTER"
Y verificamos que se nos haya subido nuestro proyecto en GITHUB
