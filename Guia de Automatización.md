# CP_Caceres_Pablo
Guia para ejecución de la Automatización.

1) Requisitos.
+ Encontrarse dentro de la red de la empresa o utilizar VPN para la conexión.
+ Modificar las rutas de origenes y destinos en el equipo desde donde se realizará la ejecución de la automatización.

2) La ejecución de la automatización se debe realizar de manera ordenada y de la siguiente forma:

2.1) #Instalar las dependencias necesarias
2.2) #Variables de Entorno
2.3) #Script para encriptar la clave de switch - Seguridad
2.4) #Script para desencriptar la clave de switch
2.5) #Script para cargar el Firmware IOS en Switch Aruba 1930
2.6) #Filtrar los switches que tienen el estado 'OK'
2.7) #Script para reiniciar los switches Aruba 1930

3) Observaciones.
El paso 2.7 se lo puede realizar únicamente fuera de horario de operaciones de ventas de 8:00am a 2:00 am, debido a que los equipos de red, switches Aruba 1930 se encuentran en producción y operación.