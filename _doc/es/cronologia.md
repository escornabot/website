---
layout: doc

title: Cronología
description: In hac habitasse platea dictumst. Curabitur scelerisque justo vitae nunc ultrices.
image: 
---

# Cronología

## El origen

-ToDo-

## Hitos

### Versión 'Placidus'

![Placidus][Placidus]

La primera versión estable, llamada *Placidus*, se lanzó en noviembre de 2014 y fue sometida a duras pruebas durante la *[OSHWDEM A Coruña 2014][OSH01]* por los niños que nos visitaron durante el evento. Todos los Escornabots se mantuvieron de una una pieza tras dos días de jugar intensamente con los niños (y también con algunos mayores :)

Esta versión utilizaba el primer y el segundo modelo de chasis, ambos con las placas de los drivers de los motores en  los laterales y la botonera sobre ellas. La primera interfaz Bluetooth se implementó en esta versión y se controlaba enviando líneas de texto describiendo los comandos de movimiento mediante la app *Android Bluetooth terminal*.

### Versión 'Brivoi'

![Brivoi][Brivoi]

Su lanzamiento tuvo lugar durante el [*Streets Science Day*][SCI01] en mayo de 2015. El diseño del nuevo chasis es más compacto, reduciendo el plástico utilizado y el tiempo de impresión hasta el 50%. En él se incorpora el concepto de hardware modular para unir las partes con soportes (brackets) a la electrónica, baterías y otros módulos opcionales. Otra característica interesante, debido a su pequeño tamaño, es la posibilidad de realizar giros en casillas cuadradas de 10cm x 10cm.

El firmware es capaz de detectar pulsaciones largas, doblando por tanto las funciones de la botonera. Introduce el comando de pausa y se simplifica el código para permitir que se  amplíe el comportamiento del Escornabot más fácilmente.

Se diseñaron placas de hardware específicas para el Escornabot: la _Escornaboard_ que integra el Arduino Nano, un controlador para dos motores paso a paso, el zumbador y otros conectores e interruptores útiles en una placa de 5cm x 5cm board; la _Escornashield Keypad_ facilitando el montaje de la botonera y un  _Arduino Shield_ preparado para conectarse a un Arduino Uno/Mega

---------

[OSH01]: http://oshwdem.org/2014/11/se-acabo-pulpo/
[SCI01]: http://www.amigoscc.es/agend/?calendar_day=2015-05-09

<!-- Images -->
[Placidus]: https://escornabot.com/web/sites/default/files/node_attachs/placidus.jpg
[Brivoi]: https://escornabot.com/web/sites/default/files/node_attachs/brivoi.jpg

