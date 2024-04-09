# Proy02_E3_ProgramacionFuncional

## Equipo 3
- Jose Luis Lara Rubio
- Arturo Cadena Mendez
- Tyrone Julian Johnson Dorantes

# Instalacion

- Primero nececitamos instalar racket en nuestro dispositivo, para ello nos dirigimos a [Download Racket](https://download.racket-lang.org/)

- Para ejecutar Racket dentro de Jupyter notebooks, primero instalamos Jupyter atravez de "pip install notebook" en nuestra consola de comandos.
  
- Posteriormente nos dirigimos a [IRacket: Racket Kernel for Jupyter](https://docs.racket-lang.org/iracket/index.html) para desgargar e instalar el kernel
  de racket para Jupyter.

> Note: `Agregar al path` para instalar el kernel de racket es necesario haber agregado tanto racket y jupyter al path de nuestra computadora.

# Resultados
- Defina una función para la evaluación del número combinatorio C(n,k), que utiliza la 
definición recursiva.

  <img src = https://github.com/TyroneJJD/Proy02_E3_ProgramacionFuncional/assets/149411556/579b195f-a0cb-4ea3-816c-e5bf353e005a width="250" heigth="350">

  Resultado obtenido:
  
    ![image](https://github.com/TyroneJJD/Proy02_E3_ProgramacionFuncional/assets/149411556/89981c20-7c5d-4c62-b2ce-f0a220812d79)

- Defina una función recursiva para calcular el Máximo Común Divisor de dos enteros 
negativos a y b con a < b usando el hecho de que MCD(a, b) = MCD(a, b-a).

  Resultado obtenido:

    ![image](https://github.com/TyroneJJD/Proy02_E3_ProgramacionFuncional/assets/149411556/7931a110-4bff-40fc-ad2f-3161800c3443)

- Definir una función que devuelva, en una lista, todos los números primos desde un número 
inicial hasta un número final, ejemplo: (primos 3 10) este ejemplo devolverá ‘(5 7).

  Resultado obtenido:

    ![image](https://github.com/TyroneJJD/Proy02_E3_ProgramacionFuncional/assets/149411556/6b6253e3-5486-4993-81ee-2cf7507d82af)

- Realizar una función para buscar un elemento en una lista, regresar #t si lo encontró y #f si 
no lo encontró.
    a. Ejemplo de entrada: (busca 4 ‘(2 4 5))
    b. Ejemplo de salida: #t

  Resultado obtenido:

    ![image](https://github.com/TyroneJJD/Proy02_E3_ProgramacionFuncional/assets/149411556/40e1c7fc-e25f-49c0-adc2-3a25462c7f13)

- Realizar una función recursiva que invierta una lista.
    a. Ejemplo de entrada: (invierte ‘(2 4 5))
    b. Ejemplo de salida: (5 4 2)

  Resultado obtenido:

    ![image](https://github.com/TyroneJJD/Proy02_E3_ProgramacionFuncional/assets/149411556/7bfb7940-3fc6-4c35-b0d2-a8715b926fae)

- Realizar una función recursiva que elimine un elemento de una lista
    a. Ejemplo de entrada: (elimina 4 ‘(2 4 5))
    b. Ejemplo de salida: (2 5)

  Resultado obtenido:

    ![image](https://github.com/TyroneJJD/Proy02_E3_ProgramacionFuncional/assets/149411556/50067077-5c83-4933-b19e-d6dc248a33f5)

- Dado un número entero positivo, realizar una función recursiva que devuelva verdadero (#t)
si el número dado es un palíndromo, en caso contrario, retornar falso (#f). Por ejemplo, 
12321 es un palíndromo, pero 1451 no es un palíndromo. No use la función reverse de 
Racket.
    a. Ejemplo de entrada: (palindromo 12321)
    b. Ejemplo de salida: #f

  Resultado obtenido:

    ![image](https://github.com/TyroneJJD/Proy02_E3_ProgramacionFuncional/assets/149411556/63e33319-f0f5-44bc-af01-3c0221c4ee87)

- Realizar una función recursiva que, dado un número entero, encuentra la suma de sus 
dígitos. No use funciones incorporadas de Racket.
    a. Ejemplo de entrada: (SumaDigitos 457)
    b. Ejemplo de salida: 16

  Resultado obtenido:

    ![image](https://github.com/TyroneJJD/Proy02_E3_ProgramacionFuncional/assets/149411556/5a6d92dd-aad8-42fe-9937-715dd843a119)

- Realizar una función recursiva que, dado un número entero, encuentra la suma de sus 
dígitos. No use funciones incorporadas de Racket.
    a. Ejemplo de entrada: (SumaDigitos 457)
    b. Ejemplo de salida: 16

  Resultado obtenido:

    ![image](https://github.com/TyroneJJD/Proy02_E3_ProgramacionFuncional/assets/149411556/b7e464f0-cd1f-45c5-9e8d-0dc92bdcf349)

- Utilizando la serie de Leibnitz y mediante una función recursiva, calcule el valor de PI
  
    <image src=https://github.com/TyroneJJD/Proy02_E3_ProgramacionFuncional/assets/149411556/27d3e105-5172-405a-9507-d7b73c6711f4  width="250" heigth="350">
  
    Resultado obtenido:
  
      ![image](https://github.com/TyroneJJD/Proy02_E3_ProgramacionFuncional/assets/149411556/d28ded4c-9519-4bab-a96d-2e54b47047c2)
