Conceptos
🔵 Fundamentos


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



🔵 Lógica de programación

Comparar datos: (==, !=, <, >, <=, >=).
    Los operadores de comparación se usan para evaluar condiciones y devuelven True o      False. Son esenciales en estructuras como if o while.

    ==: Igualdad (¿son iguales?).

    !=: Desigualdad (¿son diferentes?).

    <, >: Menor que / Mayor que.

    <=, >=: Menor o igual / Mayor o igual.
    
    
Tomar decisiones: if, else, elif.
    Estructuras condicionales para ejecutar código bajo ciertas condiciones.

    if: Evalúa una condición. Si es True, ejecuta su bloque.

    elif: Si el if anterior fue False, prueba otra condición.

    else: Se ejecuta si ninguna condición anterior fue True.
    
    
Combinar condiciones: and, or, not.
    Permiten unir múltiples condiciones en una sola expresión.

    and: Todas las condiciones deben ser True.

    or: Al menos una condición debe ser True.

    not: Invierte el resultado (True → False, False → True).
    
Cómo escribir comentarios en el código (# comentario).
Son notas para explicar el código. No afectan la ejecución.

Qué es la indentación y por qué es tan importante en Python.
La indentación (sangría) define bloques de código. Es obligatoria en estructuras como if, for, funciones, etc.
Correcto:
if True:
    print("Esto está indentado")  # Bloque del if
    

    Ejem
edad = 30
nombre_completo = "Ana Pérez"
    
Buenas prácticas al nombrar variables (nombres claros, sin espacios).
    Descriptivas: precio_total en lugar de pt.

    Minúsculas y guiones bajos: mi_variable, no MiVariable.

    Evitar espacios o símbolos: nombre_usuario, no nombre usuario.
    
    

¿Qué hacer cuando algo no funciona? (buscar, leer errores, no frustrarse).
    Lee el error: Python indica el tipo y línea del error.

    Verifica la sintaxis: ¿Faltan :, (), o indentación?

    Usa print(): Depura valores intermedios.

    Busca en internet: Copia el mensaje de error en Google.

    Divide el problema: Resuelve por partes pequeñas.
    
    
    

🔵 Estructuras de control

    Repetir acciones con bucles: for y while.
    
    Los bucles permiten ejecutar un bloque de código múltiples veces:

Bucle for:

    Ideal cuando sabes cuántas veces necesitas repetir

    Recorre secuencias (listas, cadenas, rangos)
    
 Bucle while:

    Útil cuando la repetición depende de una condición

    Cuidado con bucles infinitos (asegúrate que la condición cambie)
    
    
    Salir de un bucle antes de tiempo: break y continue.
    break:

    Termina completamente la ejecución del bucle

    Útil cuando encuentras lo que buscabas
     
    continue:

    Salta a la siguiente iteración del bucle

    Ignora el resto del código en la iteración actual
    
    
    
Manejo básico de errores: try-except.
try-except

El bloque try-except en Python te permite controlar errores que podrían detener tu programa. Es como un "seguro" para tu código.
try:
    # Código que podría fallar
    resultado = 10 / int(input("Divisor: "))
    print("Resultado:", resultado)
except:
    # Qué hacer si hay un error
    print("¡Algo salió mal!")
