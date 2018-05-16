# Calculadora

<p align="center">
<img src="https://k62.kn3.net/05BA07F37.png">
</p>

Calculadora básica que maneja números de 32 bits, hecha en [Netwide Assembler](https://www.nasm.us) (NASM).

Para facilitar la lectura y el mantenimiento del código, el programa esta dividido en diversas Macros. Al iniciar el programa este limpia las variables y los registros del CPU.
Posteriormente los números se almacenan como un arreglo de bytes, estos son convertidos a números para luego ser procesados según sea el caso (suma, resta, multiplicación o división).
Una vez obtenido el resultado, este se convierte a un arreglo de bytes nuevamente (dividiéndolo entre 10 y almacenando el residuo en una posición del arreglo).
Finalmente se guarda el arreglo invertido en uno nuevo (debido a que este dará el numero al revés), y se imprime en pantalla el resultado.


## Características

* Procesa números naturales de 32 bits (0 a 4.294.967.295).

* El resultado se muestra con signo.

* Opción para salir o continuar en el programa
