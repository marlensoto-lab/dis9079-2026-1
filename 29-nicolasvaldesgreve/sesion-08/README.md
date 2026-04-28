# sesion-08

lunes 27 abril 2026

dato de gente bacán: chico maker

guido van rossum es el creador del idioma python

en python importan los espacios importan, no son al azar. escribes menos, pero de manera más estricta. Python es para los computadores más rápidos

micropython -> circuitpython (fork del original, básicamente un nieto de micropython), auspiciado por Adafruit!!

vamos a usar circuit python 10.2.0 e inyectarla a nuestra raspberry pi pico 2 w.

### momento dramático de la clase

para que aparezca la placa como disco duro, hay que mentener presionado el botón de nuestra raspberry pi pico 2 w, conectarlo al cable que está unico a nuestro computador y soltar el botón. luego de hacer eso, nos va a aparecer el disco duro en nuestro computador, por lo que hay que abrirlo y arrastrar el archivo que descargamos llamado ``adafruit-circuitpython-raspberry_pi_pico2_w-es-10.2.0.uf2`` dentro del disco duro, lo cual hará que éste desaparezca y vuelva a aparecer con un nuevo nombre.

circuit python -> get started -> latest version of PuTTY -> Descargar la última versión de PuTTY -> Abrir PuTTY

dentro de putty, hay que cambiar el tipo de conexión a ``serial``, el port a 115200 y el host name al com en donde se encuentra nuestra raspberry pi pico 2 w
para salir de, hay que hacer ``ctrl + c``, y si no funciona, entonces hacemos ``ctrl + d``.

en el arduino uno r4 wifi tiene 5.0v de voltaje, y utilizaremos este para mover el motor servo ya que éste es un poco mañoso.

el standart de voltaje en microcontroladores ahora es de 3.3!! para que no gasten tanta energía

adc: conversor análogo-digital (es como el pin A0 del arduino)

| python | c++ |
|--- | --- |
| import | include |
| (#) | (//) |

+ cambiar el descanso de 5 seg a 20 en caso de que sea un problema
