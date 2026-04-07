## Laboratorio DEBUG 

En este laboratorio se emplearon los comandos del programa DEBUG para crear, ejecutar y analizar programas en lenguaje ensamblador, observando detalladamente el comportamiento de los registros durante la ejecución instrucción por instrucción.

## Parte A – Programa de suma

Se desarrolló un programa encargado de realizar la suma de tres valores almacenados en registros:

AX = 000A  
BX = 0005  
CX = 0003  

**Resultado final:**

AX = 0012 (18 en decimal)

## Parte B – Programa con LOOP

Se implementó una estructura iterativa utilizando la instrucción `LOOP`, en la cual se suma el valor 2 en cada iteración, empleando el registro CX como contador.

**Evolución:**

AX: 0000 → 0002 → 0004 → 0006 → 0008  
CX: 0004 → 0003 → 0002 → 0001 → 0000  

**Resultado final:**

AX = 0008  

## Parte C – Código máquina

Se examinó la representación en código máquina del programa mediante el comando `D`, permitiendo visualizar directamente los bytes almacenados en memoria.

**Ejemplo de bytes:**

B8 00 00 B9 04 00 05 02 00 E2 FB CD 20  

## Conclusión

El laboratorio permitió profundizar en la correspondencia directa entre las instrucciones en ensamblador y su representación en código máquina, evidenciando cómo el procesador interpreta y ejecuta cada instrucción a nivel binario. Además, se reforzó la comprensión del manejo de registros, el control de flujo mediante estructuras iterativas y la importancia de la memoria en la ejecución de programas, consolidando una visión más precisa del funcionamiento interno de la arquitectura 8086.
