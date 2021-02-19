
Proceso de isntalación 

Instalar Python 

1. Descargamos e instalamos al version de Python para Windows

https://www.python.org/downloads/

Fijarse que esten marcados 
[x] Install launcher for all users
[x] Add Python 3.XX to PATH

3. Verficamos la intalacion correcta en cmd 
python -v

4. Ejecutamos Pip para verificar que esté instalado correctamente y también la versión
pip --version
(si salta alguna alerta de que no se encuentra el archivo, el PATH no fue bien configurado, para ello debera agregar manualmente o volver a instalar y fijarse que este marcado la opcion Add Python to PATH

5. Ir a la ubicacion de este archivo y ejecutar 
 pip install -r requerements.txt


 - Paquetes disponibles
	- mySQL


Creacion de entorno virtual 

1. Instalamos Virtualenv con

pip install virtualenv

2. Verificamos la versión de Virtualenv

virtualenv --version

3. Crearemos un entorno virtual con Python

virtualenv test

4. Iniciamos el entorno virtual

.\test\Scripts\activate

5. Finalmente desactivamos el entorno virtual

deactivate
