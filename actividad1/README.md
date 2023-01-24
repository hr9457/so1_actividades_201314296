# Actividad 1


## Tipos de Kernel y sus diferencias
Los kernel son un centro para un sistema operativo que ayuda a controlar las funciones importantes del hardware, este lo podemos tener presenta en sistemas operativos Linux, MacOS, windows, un smartphone y un server.

* kernel Monolitico:
Este esta mas enfocado para gestionar la memoria y los procesos, comunicacion que existente entre procesos, Ademas de proporcionar el soporte para los drivesr y el hardware

* Microkernel:
Es el kernel monolitico ya que funciona de la misma manera con la diferencia que este es mas pequeño dado que esta funcionando por modulos para evitar fallos en el sistema a gran escala. 

* Kernel hibrido:
Los kernel hibrido son la comibinacion de un kerel monolitico y un microkernel, esto para que el kernel puede ser mas grande pero de forma modular y dinamico

* Exonucleos:
Son un poco mas simples pero con la potencia de que nos permite el uso de bibliotecas. Lo cual los hace mas pequeños y administrable para los desarrolladores


## User vs Kernel Mode

* User Mode:
Los modos de usuario en el kernel tiene cierta limitaciones para la interaccion o acceso a los recuros de la maquina como poder acceder direactamente al hardware o memoria de referencia lo cual se hace apoyo en la API del sistema

* Kernel Mode:
El modo kernel es un modo en el cual nuestra ejecucciones pueden tener acceso completo y sin restricciones al hardware, logrando ejecutar cualquier instruccion de CPU y teniendo acceso completo a la direcciones de memoria en el sistema, Comumente este modo se reserva para funciones de mas bajo nivel y de mayor confianza en el sistema operativo.
