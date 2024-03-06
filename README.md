#### proceso de ensanblaye del robot

1. como primer paso de emsamblaye del robot que realize fue el esamblaye de las piezas que sostenian las ruedas traseras y el motor, despues coloque las columnas que sostendran las ruedas delanteras y donde se coloca la placa de arduino 

     ![](https://github.com/asrc-0105/practicas.1/blob/main/20240305_153904.jpg)

2. como segundo paso seria colocar las llantas traseras y el motor en su respectivo lugar
 

     ![](https://github.com/asrc-0105/practicas.1/blob/main/20240305_153633.jpg)

4. ya despues de haber colocado las llantas traseras y el motor el siguiente paso es colocar la base donde se coloca las placas de arduino


    ![](https://github.com/asrc-0105/practicas.1/blob/main/20240305_153254.jpg)

5. ya despues es el siguiente paso es poner las llantas delanteras (esta parte me costo un monton porque las llantas no querian entrar )

   ![](https://github.com/asrc-0105/practicas.1/blob/main/20240305_152326.jpg)


y estos fueron los pasos que realice para poner realizar el ensamblaye del auto 


#### explicacion de la tarjeta arduino romeo 

la placa arduino RoMeo BLE contine todas las caracteristicas del arduino RoMeo pero este tiene una caracteristica adiccional que es que contiene bluetooth 4.0, esto le deja recibir comandos mediante bluetooth 

El RoMeo BLE es un tablero de control especialmente diseñado para aplicaciones robóticas. Gracias a la plataforma de código abierto de Arduino y a los códigos de código abierto disponibles públicamente, el BLE se integra fácilmente con los módulos de Arduino.


#### Características técnicas

´´´´
Básico	Funciones
Microcontrolador: ATmega328P	
Gestor de arranque: Arduino UNO	
Chip BLE integrado: TI CC2540	
14 puertos de E/S digitales	
6 salidas PWM (pin 11, pin 10, pin 9, pin 6, pin 5, pin 3)	
8 puertos de entrada analógica de 10 bits	
3 I2Cs	
5 Botones	
Puerto de fuente de alimentación: USB o DC2.1	
Rango de fuente de alimentación externa: 5-23V	
Salida de CC: 5 V/3,3 V	
Tamaño: 94 mm x 80 mm	
Entrada/conmutación automática de alimentación externa	
Alcance de transmisión: 70 m en espacio libre	
Admite la actualización remota de bluetooth del programa Arduino	
Soporta Bluetooth HID	
Soporta iBeacons	
Admite el comando AT para configurar el BLE	
Soporte de comunicación transparente a través de Serial	
Apoye el interruptor de la máquina de ungüento maestro	
Soporta programa de chip BLE de actualización USB	
Admite cabezal de pin macho y hembra	
Controlador de motor de puente H de dos vías con corriente máxima de 2 A	



#### Aplicación de la potencia
Este es uno de los pasos más importantes para poner en marcha el RoMeo y comunicarse con su controlador host. DEBE asegurarse de aplicar energía al terminal de alimentación utilizando la polaridad correcta. La polaridad inversa dañará el RoMeo.

### Alimentación desde USB:
Conecte el cable USB al controlador RoMeo desde una fuente de alimentación (es decir, un conector de pared o una computadora). Su RoMeo debería encenderse, si lo hace, debería notar que el LED se enciende. Tenga en cuenta que el USB solo puede suministrar una corriente de 500 mA, que es suficiente para encender el LED pero insuficiente para alimentar motores o servos de CC.

### Alimentación de entrada de alimentación externa:
Conecte el cable de tierra (generalmente el cable negro) de su fuente al terminal de tornillo etiquetado como "GND" y luego conecte el cable positivo de su fuente de alimentación al terminal de tornillo etiquetado como "VIN".

### Software
RoMeo puede ser programado por Arduino IDE 0022 y versiones superiores.


![]![image](https://github.com/asrc-0105/practicas.1/assets/145295196/ef43e1b4-8bb0-4f04-b892-9832ce153047)

)


links de busquedas: 
https://youtu.be/lWeEF5fmdko?si=-rP11946fr3UGOyu

https://wiki.dfrobot.com/RoMeo_BLE__SKU_DFR0305_
https://wiki.dfrobot.com/RoMeo_BLE__SKU_DFR0305_




  
