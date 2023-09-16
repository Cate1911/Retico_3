# Retico_3
## Algoritmo para plantear números primos hasta n

Para plantear este algoritmo, me basé en los números primos base múltiplos de cualquier otro número; es decir, tomé como base al 2, 3, 5, 11, 13 debido a que estos números son de los cuales se derivan los otros números, debido a que son la base para la formación de números más grandes como el 24, 32, 111, 315, 33999999, etc.->esto se relaciona con el mínimo común múltiplo. 
* **_Con Github_**  
```pseudocode
Algoritmo números primos hasta n
n : entero
i : entero
a : entero
b : entero
c : entero
inicio
i := 2
a := 3
b := 5
c := 11
Paso 1. Ingrese un número entero (n)
Paso 2. Cree una lista de números desde i hasta n
Paso 3. Eliminar de la lista todos los números (≠i) que terminen en 0, 2, 4, 6 y 8
Paso 4. Sumar todas las cifras del número siguiente a b hasta que su resultado quede expresado en 1 cifra
 Si ese resultado es igual a 3, 6 o 9 entonces
  eliminar ese número de la lista
 sino
  repetir el Paso 4 con el siguiente número en la lista
Paso 5. Eliminar de la lista todos los números (≠b) que terminen en 5
Paso 6. Eliminar de la lista todos los números (≠11) que tengan el mismo dígito en todas sus cifras
Paso 7. Elevar al cuadrado el primer número de la lista
 Si el cuadrado de este número se encuentra en la lista entonces
  eliminar el cuadrado de ese número y repetir el Paso 7 con el siguiente número de la lista 
 sino
  escribir ("los números primos que hay desde i hasta n son: (mencionar los números que quedaron en la lista)")
fin
```
* **_Con Diagrama de Flujo_**

<span>![image](https://github.com/Cate1911/Retico_3/assets/141857246/88989812-4e9e-4994-a54d-b0a597433a44)
</span>

## Algoritmo para hallar la raíz cuadrada de cualquier número real

Para plantear este algoritmo, me basé en el método del mínimo común múltiplo. Sin embargo, como este método no expresa las raíces de números primos, este algoritmo no puede calcular las raíces de números primos y sólo las deja expresadas.
```pseudocode
Algoritmo raíz cuadrada de cualquier número real
n : real (R)
inicio
n >= 0
Paso 1. Ingrese un número (n)
 Si n es 0
  escribir ("La raíz cuadrada de 0 es 0")
 sino
  realizar el Paso 2
Paso 2.
 Mientras n termine en los dígitos 0, 2, 4, 6 u 8 hacer
  Si n es un número que termina en los dígitos 0, 2,4, 6 u 8 entonces
   dividir ese resultado entre 2, escribir el 2 a un lado y repetir el Paso 2 con el resultado que le dió.
  sino
   continuar con el Paso 3
Paso 3. Sume los dígitos del número resultante del Paso 2 hasta tener una suma de un dígito
  Si el resultado de la suma es 3, 6 o 9 entonces
   dividir ese resultado entre 3, escribir el 3 a un lado y repetir el Paso 3 con el resultado que le dió.
  sino
   continuar con el Paso 4
Paso 4.
  Si el número resultante del Paso 3 termina en 0 o en 5 entonces
   dividir ese resultado entre 5, escribir el 5 a un lado y repetir el Paso 4 con el resultado que le dió.
  sino
   continuar con el Paso 5
Paso 5. dividir ese resultado entre 7
 Mientras ese resultado dé como residuo de su división 0 hacer
  Si ese resultado tiene como residuo de su división 0 entonces
   dividir ese resultado entre 7, escribir el 7 a un lado y repetir el Paso 5 con el resultado que le dió.
  sino
   continuar con el Paso 6
Paso 6. dividir ese resultado entre 11
 Mientras ese resultado dé como residuo de su división 0 hacer
  Si ese resultado tiene como residuo de su división 0 entonces
   dividir ese resultado entre 11, escribir el 11 a un lado y repetir el Paso 6 con el resultado que le dió.
  sino
   continuar con el Paso 7
Paso 7. dividir ese resultado entre 13
 Mientras ese resultado dé como residuo de su división 0 hacer
  Si ese resultado tiene como residuo de su división 0 entonces
   dividir ese resultado entre 13, escribir el 13 a un lado y repetir el Paso 7 con el resultado que le dió.
  sino
   continuar con el Paso 8
Paso 8. 
 Si tiene algún  número escrito a un lado entonces
  Cuente cuántos números de los que escribió a un lado son iguales (cuántos 2, cuántos 3, cuántos 5, cuántos 7, cuántos 11 y cuántos 13 hay)
sino
  escribir ("La raíz cuadrada de n no es exacta, entonces, se podría expresar como √n")
Paso 9. Agrupe los números en parejas del mismo número (por ejemplo, si hay 4 números "3", entonces, agrupe los números "3" en 2 parejas conformadas por dos "3" en cada caso)
 Si hay números que se quedan sin pareja o sin agrupar entonces
  Dejarlos expresados como la raíz cuadrada de estos
 sino
  Reescribir cada pareja como el cuadrado de ese número (Ej: 2 y 2=2^2)
Paso 10. Sacarle raíz cuadrada a cada pareja reescrita, cancelando la raíz cuadrada con el cuadrado de la pareja
Paso 11. Multiplicar todos los resultados, incluyendo los números que quedaron expresados en forma de raíces en el Paso 9 (en caso de que haya)
 Si hay números expresados en raíces entonces
  dejar expresada la raíz en la multiplicación de estos con los otros números
 sino
  multiplicar todos los números
Paso 11. Escribir ("La raíz cuadrada de n es igual a: (inserte el resultado del procedimiento anteriormente realizado)")
fin
```

* **_Con Diagrama de Flujo_**

![image](https://github.com/Cate1911/Retico_3/assets/141857246/4e28ca56-3a73-41cd-be64-3ca41a979986)
### ¡Graciaaasss!

![image](https://github.com/Cate1911/Retico_3/assets/141857246/146297c4-2aec-4f7e-b56c-f2da1d503522)
