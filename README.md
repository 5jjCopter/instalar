# instalar
Aqui tenemos 3 archivos para hacer una instalacion automatica de:
Navio +
navio 2
navio 2 estable
Dentro de los archivo hay una parte de codigo para actualizar 
Lo hace automatico
Solo teneis que copiar el conteniso del archivo correspondiente y pegar en la consola de navio.
Realizara la instalacion y actualizacion automatica.
Si solo quereis actualizar elegir el archivo de actualizacion.
Estos archivos cargan.
APM (home/pi/ardupilot) incio automatico en arranque.
Video streamin por wifi
Lectura de temperatura con almacenado en (home/pi/temp.txt).....con reescritura de datos tra reincio.....No inicio automatico.
Para incio de temp.py(sudo python temp.py)Para incio automatico de temp.py:
sudo systemctl daemon-reload
sudo systemctl enable temp.py
Para parar,detener o reinciar cualquiera de los .services:
Start
Inciar
sudo systemctl start ardupilot

Stop
Parar
sudo systemctl stop ardupilot

Restart
restar
sudo systemctl restart ardupilot

Start on boot 
Arranque en inicio
sudo systemctl enable ardupilot

Not run on boot (for troubleshooting or other tasks)
Quitar arranque en incio
sudo systemctl disable ardupilot

Cambiar el nombre del servvicio por el que nesesitemos:ejemplo sudo sydtemctl video
