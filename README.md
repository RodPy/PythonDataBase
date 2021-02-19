
# Proceso de instalación 
En este repositorio encontraras los materiales necesarios para usar bases de datos y python. 
Cualquier consulta, pueden crear algún issue o contactar a rodpy1@gmail.com

## Instalar Python 

 1. Descargamos e instalamos al versión de Python para Windows, de la [pagina de python](https://www.python.org/downloads/) 

Fijarse que estén marcados 

 - [x] Install launcher for all users
 - [x]  Add Python 3.XX to PATH

![Ejemplo](https://github.com/RodPy/PythonDataBase/blob/master/Capturas/Captura%20de%20pantalla%20(70).png)

3. Verificamos la instalación correcta por terminal cmd o PowerShell de Windows

> Para acceder al cmd o PowerShell en el buscador de Windows se puede buscar con esas palabras. 

```bash
    python --version 
```
> Mensaje esperado  ->Python 3.X.X
![Ejemplo](https://github.com/RodPy/PythonDataBase/blob/master/Capturas/Python%20Ej.png)

5. Ejecutamos Pip para verificar que esté instalado correctamente y también la versión
```python
pip --version
```
> Mensaje esperado  ->pip 3.X.X
![Ejemplo](https://github.com/RodPy/PythonDataBase/blob/master/Capturas/pip%20Ej.png)

> si salta alguna error de que no se encuentra el archivo, **el PATH no fue bien configurado**, para ello deberá agregar manualmente o volver a instalar y fijarse que este marcado la opción Add Python to PATH

6. Ir a la ubicación de este archivo y ejecutar 

> La opción mas rápida es copiar la dirección desde el explorador y pegar en el terminal ej . 
> cd  .\Downloads\PythonDataBase

```python 
pip install -r requerements.txt
``` 


 - Paquetes disponibles
	- mySQL


## Creacion de entorno virtual 

1. Instalamos Virtualenv:
```python
pip install virtualenv
```
2. Verificamos la versión de Virtualenv
```python 
virtualenv --version
```
> Mensaje esperado  ->virtualenv 3.X.X
![Ejemplo](https://github.com/RodPy/PythonDataBase/blob/master/Capturas/Python%20Ej.png)
3. Crear una capeta de trabajo 
```bash 
mkdir CarpertaPrueba
```
5. Acceder a la carpeta y crearemos un entorno virtual con Python
```bash 
cd .../CarpertaPrueba/
```

```python 
virtualenv pyDatos
```

6. Iniciamos el entorno virtual
```bash
.\pyDatos\Scripts\activate
```

5. Para cerrar el entorno  virtual
```bash
.\pyDatos\Scripts\deactivate
```
