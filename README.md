## Trabajo práctico final de la asignatura DCI ##
Este repositorio contiene el trabajo práctico final para la asignatura de Diseño de Circuitos Impresos de la carrera de posgrado de FIUBA.

* Autor: Jordán Joan Emmanuel
* Título corto del trabajo:  Adaptador LCD i2c para Displays Alfanuméricos
* Resumen:  Este trabajo consiste en el diseño de una placa electrónica para control de Displays Alfanuméricos desde microcontrolador.
Mediante interfaz LCD-i2c. La placa utiliza como integrado principal el PCF8574, el cual traduce la comunicación i2c con el microcontrolador
a puerto paralelo para el Display, el cual puede ser 16x02, 20x4, 40x2, etc.

* Descripción: El módulo LCD-i2c es un expansor de puertos I2C, para controlar desde un microcontrolador con sólo dos pines (SCL y SDA), 
un display alfanumérico tipo 16x2, 20x4, 40x2, etc. Cuenta con un potenciómetro para ajustar el contraste de la pantalla y un jumper para 
habilitar su backlight. Cuenta con un selector de tres palancas para modificar la dirección de esclavo (pines A0, A1 y A2) lo que permite 
direccionar hasta 8 módulos iguales en el mismo bus de comunicación. La dirección predeterminada es 0x27, y puede ser detectada por el 
programa. El integrado principal de este módulo es el expansor i2c PCF8574.

## Licencia de este trabajo ##
CERN Open Hardware Licence 

## Estructura del TP FINAL ##

Se propone y se pide utilizar la siguiente estructura.

* doc: Toda la información sobre el circuito, principalmente de autoría o procesamiento propio. Por ejemplo:
  * Notas de ingeniería propias.
  * Notas de aplicación propias.
  * Estudios previos, estado del arte, resumen de las investigaciones.
  * Notas con cálculos.
  * Dibujos adicionales.
  * Fotos de los prototipos.
  * Presupuestos, cotizaciones.
* info: Toda la información recolectada, principalmente de terceros, como por ejemplo:
  * Hojas de datos.
  * Notas de aplicación.
  * Info de productos comerciales.
  * Info en internet.
* pcb: Archivos de diseño esquemático y pcb.

Dependiendo la magnitud del proyecto, tendremos más o menos información en estos directorios. 
Revisar los README.md en cada directorio para conocer las pautas de cada uno para este TP.