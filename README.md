# Demo de FastAPI y Groq

## 0. Actualizar la lista de versiones de las librerias del sistema operativo

Actualiza la lista de versiones de libreias del sistema operativo.

````bash
sudo apt update
````

## 1. Instalar neofetch 

Instalar neofetch para conocer las caracteristicas del sistema operativo que se esta utilizando.

````bash
sudo apt install neofetch -y
````

## 2. Ejecutar neofetch

Ejecutar neofetch

````bash
neofetch
````

Nota: Crear el archivo os.txt con la versión del sistema operativo utilizado

## 3. Crear un ambiente virtual

Crear un virtual enviroment para el proyecto

````bash
virtualenv venv
````

## 4. Entrar al ambiente virtual

Inicializar el ambiente virtual

````bash
source venv/bin/activate
````

## 5. Salir del ambiente virtual

Desactivar el ambiente virtual

````bash
deactivate
````

## 6. Crear el archivo .gitignore

Crear el arhvivo .gitignore y agregar las siguientes lineas

````bash
*.pyc
__pycache__/
venv/
````

## 7. Instalar las librerias necesarias 

Para este proyecto se usaran las librerias de [FastAPI](https://fastapi.tiangolo.com/#installation)

````bash
pip install "fastapi[standard]"
````

## 8. Crear el archivo requirements.txt

Se genera el archivo requirements.txt para listar las librerias necesarias para el proyecto y sus versiones.

````bash
pip freeze > requirements.txt
````

## 9. Crear el archivo runtime

Se genera el archivo runtime con la versión de Python que se esta utilizando

````bash
python3 -V > runtime
````

## 10. Indexar los archivos creados con git

Se actualiza la lista de archivos creados y actualizados con el control de versiones

````bash
git add .
````

## 11. Crear un commit con la configuración inicial

Se crea un commit indicando que ya se termino la configuración incial

````bash
git commit -m "CREATED configuracion inicial"
````

## 12. Actualizar el repositorio de github

Se actualiza el repositorio con los cambios realizados

````bash
git push -u origin main
````

