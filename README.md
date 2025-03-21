# Análisis Numérico y Cálculo Avanzado 
## TRABAJO PRÁCTICO Nº2: RAÍCES DE FUNCIONES
OBJETIVO:  El objetivo final de este Trabajo Práctico es determinar cuál es la altura libre HL que define el volumen límite a almacenar
para un tambor cilíndrico, utilizando el método de bisección para encontrar raíces de funciones utilizando lenguaje de programación Python
o implementando en SOFTWARE del tipo Matlab – Scilab – Octave y corroborados mediante planillas de cálculo en SOFTWARE del tipo Excel.

DESCRIPCIÓN DEL PROBLEMA A TRATAR: 
Se continúa el análisis del problema planteado en el Trabajo Práctico Nº1, basado en el hallazgo de un tanque cilíndrico de almacenaje horizontal:

![image](https://github.com/user-attachments/assets/69e34194-f76e-4ac8-9fb0-dcbaeec9c01e)

Trabajando con la geometría, se llega a que, para el tambor cilíndrico con llenado parcial, el volumen se calcula con la siguiente fórmula:

![image](https://github.com/user-attachments/assets/d63238a2-71ec-4daf-9bf7-2be6ebe16d7c)

En el primer Trabajo Práctico se llegó a implementar la fórmula geométrica del volumen, ya sea utilizando Software Matlab, Octave o Scilab, como también programando en Python. Sin embargo, quedaba contestar con precisión el siguiente interrogante:

¿Cuáles serían los cálculos para saber cuántos centímetros debe medir HL para que el volumen sea de 300litros?

Aplicación de métodos numéricos: “Raíces de funciones”
Como puede verse en la fórmula desarrollada para calcular el volumen, despejar la variable HL representa una gran complejidad. Por lo tanto, se opta por utilizar métodos numéricos para llegar a una aproximación. Se re-escribe la fórmula para que tenga la forma de una función de HL que se pueda igualar a cero.

![image](https://github.com/user-attachments/assets/9160663a-c5df-4015-b82d-6d487c87d325)

Entonces, si fijamos el valor de V en 300litros, al hallar el valor de HL que hace cero la función, habremos encontrado la solución a los interrogantes planteados.

CONSIGNAS:
Implementar métodos numéricos en software [Matlab – Scilab – Octave] o utilizar lenguaje Python para resolver los siguientes puntos:

-  Usar el método de la bisección para hallar la altura HL, considerando un error δ de 0,0005 para el intervalo inicial de búsqueda comprendido entre cero y tres medios del diámetro.
-  Mostrar todos los resultados de las iteraciones desarrolladas para cada método en una tabla como la siguiente:

![image](https://github.com/user-attachments/assets/44e155fc-1128-4e25-8dd6-df0d5933b173)

