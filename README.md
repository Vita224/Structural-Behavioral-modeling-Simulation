# Structural-Behavioral-modeling-Simulation

Full adder de 64 bits.

## Descripción
Se desarrolla un Full Adder x64bits; iniciamos con un "full_add_x1", que se utiliza para crear un "full_add_x2" para luego instanciarlo nuevamente y crear un "full_add_x4", repitiendo este proceso hasta llegar al full_add_x64 deseado.

## Simulación 🚀
Se realiza la simulación desde el programa vivado, utilizamos nuestro testbench donde establecimos 4 operaciones, las cuales se ejecutan paso a paso por los breakpoints agregados.<br><br>
![Captura](https://github.com/Vita224/Structural-Behavioral-modeling-Simulation/assets/53021236/da8e88f1-11cb-42af-9b05-973d02f1590e)<br>
Imagen 1. Código con 4 operaciones y breakpoints.<br><br>

## Primera operación
Ingresamos el primer valor, el cual se nos muestra en base binaria, no se logra apreciar todo el valor por la longitud que tiene.<br><br>
![Captura1](https://github.com/Vita224/Structural-Behavioral-modeling-Simulation/assets/53021236/7ff7fc2f-8943-47c4-aef3-0dd9892ee84a)<br>
Imagen 2. Primer cálculo en base binaria.<br><br>

Cambiamos la base para ver nuestros calculos, definimos base decimal, esto con fines de que sea más visual cada operación realizada<br><br>
![Captura2](https://github.com/Vita224/Structural-Behavioral-modeling-Simulation/assets/53021236/b237d080-da3a-4fbe-9709-529ac6d3c18a)
Imagen 3. Primer cálculo en base decimal.<br><br>

## Segunda operación
Segundo calculo en base binaria, podemos ver que el resultado es correcto, 8 + 1 = 9<br><br>
![Captura3](https://github.com/Vita224/Structural-Behavioral-modeling-Simulation/assets/53021236/41b59444-ae78-4d10-94da-e2ff23b32d21)<br>
Imagen 4. Segundo cálculo en base decimal<br><br>

## Tercera operación
Tercera operación con un valor más grande, siempre en base decimal para visualizar el resultado satisfactorio<br><br>
![Captura4](https://github.com/Vita224/Structural-Behavioral-modeling-Simulation/assets/53021236/baafcdd4-00f5-4958-96bb-8cd18f71327a)<br>
Imagen 5. Tercer cálculo en base decimal<br><br>

## Cuarta operación
Y por último en nuestra operación final, ingresamos el valor máximo posible, visualizando el resultado en base binaria<br><br>
![Captura5](https://github.com/Vita224/Structural-Behavioral-modeling-Simulation/assets/53021236/db123d72-e58c-4435-bc35-19fb97c36d45)<br>
Imagen 6. Cuarto cálculo en base binaria<br><br>

---
Desarrolado por Vitalino Guerra (091-19-1394) 😊



