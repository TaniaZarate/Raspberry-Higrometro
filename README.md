# Raspberry-Higrómetro
Ejercicio utilizando la Raspberry Pi 4 y el Higrómetro, el cual está midiendo y detectando el nivel de la humedad  en el suelo, ocupando en este ejemplo una planta situada en una maceta.


- Se requiere instalar la librería `WiringPi`. Para más información, visita [WiringPi](http://wiringpi.com/).
> Si persiste error al compilar el programa debido a esta librería diciendo ***<wiringPi.h>: No existe el fichero o el directorio***, realiza lo siguiente:
> 
> `sudo apt-get install git-core`
> 
> `git clone https://github.com/WiringPi/WiringPi`
> 
> `cd WiringPi`
> 
> `./build`
> 
> `gpio -v`        -->  Para comprobar que la librería se ha instalado correctamente.
