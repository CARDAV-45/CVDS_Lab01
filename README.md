# LABORATORIO 1- INTRODUCCIÓN GIT
ESCUELA COLOMBIANA DE INGENIERÍA - CICLOS DE VIDA DE DESARROLLO DE SOFTWARE

## PARTE I (Trabajo Individual). 

1.	Crea un repositorio localmente.
2.	Agrega un archivo de ejemplo al repositorio, el **README.md** puede ser una gran opción.
3.	Averigua para qué sirve y como se usan estos comandos **git add** y **git commit -m “mensaje”**
4. Abre una cuenta de github, si ya la tienes, enlazala con el correo institucional.
   
   [Como enlazar correos en GitHub](https://docs.github.com/es/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-email-preferences/adding-an-email-address-to-your-github-account)
   
5.	Crea un repositorio en blanco (vacío) e GitHub.

![image](https://github.com/PDSW-ECI/labs/assets/118181543/0a6db4de-3682-4e43-838c-415373596947)
![image](https://github.com/PDSW-ECI/labs/assets/118181543/7c1cafdf-9a35-4180-99c4-8cabd84d21b8)

   
6.	Configura el repositorio local con el repositorio remoto.

      [Como subir un proyecto local a github.](https://gist.github.com/cgonzalezdai/cc33db72a6fe5178637aabb562eae35c)
  
7.	Sube los cambios, teniendo en cuenta lo que averiguaste en el punto 3
    Utiliza los siguientes comando en el directorio donde tienes tu proyecto, en este orden:
   	```bash
      git add .
    ```

    ```bash
      git commit -m "mensaje, lo que hiciste con el archivo"
    ```

    ```bash
      git push "url repositorio"
    ```
8.	Configura el correo en git local de manera correcta
     [Configurar correo electrónico en GitHub](https://docs.github.com/es/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-email-preferences/setting-your-commit-email-address)
9.	Vuelve a subir los cambios y observa que todo esté bien en el repositorio remoto (en GitHub).

## :white_check_mark: Respuestas: 1, 2, 6, 7 y 8.

![alt text](<assets/Screenshot 1.png>) 
![alt text](<assets/Screenshot 2.png>)
![alt text](<assets/Screenshot 3.png>) 

## :white_check_mark: Respuestas: 3.
3. Comandos básicos de Git: `git add` y `git commit -m “mensaje”`

### **`git add`**
#### ¿Para qué sirve?
- **`git add`** se usa para preparar archivos para ser incluidos en el próximo commit. Esto se llama agregar los archivos al "área de preparación" o "staging area".

#### **Ejemplo de uso:**
1. Modificas o creas un archivo en tu proyecto (por ejemplo, `archivo.txt`).
2. Escribes el comando:
   ```bash
   git add archivo.txt
### **`git commit -m “mensaje”`**
#### ¿Para qué sirve?
- **`git commit`** guarda los cambios que están en el área de preparación (staging area) en el historial de Git.
- Es como tomar una "foto" del estado actual del proyecto.
- El argumento **`-m`** Permite añadir un mensaje breve que describe el cambio realizado.

#### **Ejemplo de uso:**
1. Después de agregar los archivos con git add
2. Escribes el comando:
   ```bash
   git commit -m "Primer commit o escribes lo que has hecho"
3. Esto crea un commit con el mensaje "Primer commit o escribes lo que has hecho"

## :white_check_mark: Respuestas: 4.
4. Ya tenia una cuenta y estaba enlazada al correo institucional.
## :white_check_mark: Respuestas: 5.
9. Despues de subir los cambios podemos observar que todo esta correctamente.


