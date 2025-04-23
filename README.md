Qué es programar?
proceso de crear software o programas mediante la escritura de instrucciones (código) que una computadora puede entender y ejecutar.


¿Qué es Python y para qué sirve?
 lenguaje de programación de alto nivel, interpretado y multipropósito, conocido por su sintaxis clara y legible (parecida al inglés). 
 Desarrollo Web (Backend),Ciencia de Datos & IA, Automatización y Scripting, Desarrollo de Software, Ciberseguridad, Internet de las Cosas (IoT), DevOps y Automatización de Servidores, Finanzas y Trading Algorítmico.
 
 
¿Qué es un programa y cómo se ejecuta?
conjunto de instrucciones escritas en un lenguaje de programación que le indica a una computadora cómo realizar una tarea específica. 

El proceso varía según el lenguaje, pero generalmente sigue estos pasos:

Lenguajes interpretados (Python, JavaScript, Ruby):

    Un intérprete lee y ejecuta el código línea por línea sin generar un ejecutable.

   
¿Qué es una variable?
en programación es un contenedor que almacena datos (valores) en la memoria de la computadora. Estos datos pueden cambiar (de ahí el nombre "variable") durante la ejecución de un programa.

Tipos de datos básicos: texto (str), número entero (int), número decimal (float),
 verdadero/falso (bool).
 
 Tipo	Ejemplo	Descripción
Entero (int)	42, -7	Números sin decimales.
Flotante (float)	3.14, -0.5	Números con decimales.
Texto (string)	"Hola", 'a'	Cadena de caracteres (entre comillas).
Booleano (bool)	true, false	Representa verdadero o falso.


Operaciones básicas con números (+, -, *, /).
Las operaciones básicas con números en programación son similares a las matemáticas tradicionales, pero adaptadas a la sintaxis de cada lenguaje. 
Suma	+	5 + 3	8
Resta	-	10 - 2	8
Multiplicación	*	4 * 3	12
División	/	20 / 5	4 (o 4.0 si es decimal)
Módulo (resto)	%	10 % 3	1 (resto de la división)

Mostrar información en pantalla: print().
una de las herramientas más básicas y esenciales en programación, ya que permite mostrar información en pantalla. Su uso varía ligeramente según el lenguaje, pero el concepto es el mismo.
En Python
print("Hola, mundo")  # Muestra: Hola, mundo

Pedir información al usuario: input().
en Python permite pedir información al usuario desde la consola. El programa espera a que el usuario escriba algo y presione Enter, luego almacena ese dato para usarlo en el código.
En Python
dato = input("Mensaje para el usuario: ")

Convertir tipos de datos: int(), float(), str().

Python ofrece funciones integradas como int(), float() y str() para hacer estas conversiones de manera sencilla.
Ejemplo
Función	Descripción	Ejemplo
int()	Convierte a número entero.	int("5") → 5
float()	Convierte a número decimal.	float("3.14") → 3.14
str()	Convierte a texto (cadena de caracteres).	str(100) → "100"

edad = "25"
edad_entero = int(edad)       # Convierte a entero → 25
precio = "19.99"
precio_decimal = float(precio) # Convierte a decimal → 19.99

print(edad_entero + 5)        # 30 (operación matemática)
print(precio_decimal * 2)     # 39.98


¿Qué es un error? Errores comunes para principiantes.
En programación, un error es un problema que impide que un programa se ejecute correctamente. Los errores pueden surgir por múltiples razones, desde fallos en la lógica del código hasta problemas en los datos ingresados.
Errores de Sintaxis (SyntaxError)
Errores en Tiempo de Ejecución (RuntimeError)
NameError: Usar una variable no definida.
TypeError: Operaciones entre tipos incompatibles.
IndexError: Acceder a una posición inexistente en una lista.
