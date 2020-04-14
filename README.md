
|Español  | English |
|-------------------|----------------------|
|- [Bienvenido!](#Bienvenido!) 			|- [Welcome!](#Welcome!)|
|- [Proyecto](#Proyecto)  			| - [Project](#Project)|
| - [Funciones](#Funciones)| - [Functions](#Functions)|
| -[Manejo de excepciones](#Manejo-de-excepciones)| - [Exception handling](#Exception-handling)|
|- [Orden jerárquico](#Orden-jerárquico)|- [Hierarchy order](#Hierarchy-order)|
|- [Motor de procesamiento](#Motor-de-procesamiento)|- [Processing engine](#Processing-engine)|
|- [Imagenes](#Imagenes)| - [Images](#Imagenes)|
|- [APK](#Aplicación)| - [APK](#APK)|


# Bienvenido!

En este repositorio encontraras un proyecto para la materia **Programación de Aplicaciones Moviles** del ciclo 7 de 10, de la carrera de ingeniería de sistemas informáticos. 

# Proyecto

Encontraras una aplicación que desarrolla las funciones de una **calculadora**, la cual fue hecha en android studio y es compatible con las versiones de android kit kat 4.4 en adelante.

## Funciones

Aparte de las 4 funciones básicas (suma, resta, multiplicación y división) se incorporan las operaciones de raíz cuadrada y potencias, tiene un botón que simula un estado inactivo de la calculadora (como un botón de encendido y apagado), un botón para borrar y uno para limpiar la pantalla.

El procesamiento de las operaciones se hace a medida que el usuario presiona las teclas, la calculadora realiza las operaciones que se le indican.

Puede manejar decimales, hasta 16.

Al iniciar la aplicación aparecerá una pantalla que se superpone sobre la aplicación, la cual simula el hecho de estar apagada, y se enciende al dar tap sobre ella, si se desea "apagar" de nuevo, solamente se debe presionar sobre el gradiente de color (pantalla donde aparecen las operaciones y resultados).

## Manejo de excepciones

Al presentarse una operación no valida, la aplicación deja de mostrar el resultado hasta que se corrija, a pesar de presentar operaciones no validas no crashea. Las operaciones que tienen como denominador 0 arrojan infinity, o 0/0 arroja NaN (Not a Number) por su indeterminación o falta de acuerdo entre el gremio matemático.

## Orden jerárquico

La aplicación maneja el orden jerárquico de las aplicaciones, realiza primero los exponentes, luego las multiplicaciones y divisiones antes que la suma y resta. En caso de presentarse operaciones del mismo nivel jerárquico se realiza primero la operación más a la izquierda por conveniencia.

## Motor de procesamiento

Se ha ocupado una libreria de terceros:  **Rhino**  que fue desarrollada por mozilla, el cual es un motor de **JavaScript** que evalúa el string que recibe como parámetro y evalúa la cadena de texto, cabe destacar que no sólo procesa operaciones matemáticas sino que también podría evaluar cualquier expresión que se ocupa habitualmente en JS.

> **Nota:** Se consideró que el criterio a evaluar sería los conocimientos sobre **Android Studio**  por lo que se decidió usar la útil libreria de Rhino, todo para no volver a inventar la rueda. (un dicho).


## Aplicación
Puede encontrar la apk para instalar dentro del folder apk.

------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------
-------------------
---
----





# Welcome!

In this repository you will find a project for the subject **Programming of Mobile Applications** (4th. year of college), of the career of computer systems engineering.

# Project

You will find an application that develops the functions of a **calculator**, which was made in android studio and is compatible with versions of android kit kat 4.4 onwards.

## Functions

Apart from the 4 basic functions (addition, subtraction, multiplication and division), is added the functions of square root, and operations such as powers are incorporated, it has a button that simulates an inactive state of the calculator (like an on / off button), a button to clear and one to clean the screens.

Processing of operations is done as the user presses the keys, the calculator performs the operations indicated.

It can handle decimals, up to 16.

When starting the application, a screen will appear that is superimposed on the application, which simulates a turned off state, and turns on when you tap on it, if you want to "turn off" again, you only have to press on the color gradient (screen where operations and results appear).

## Exception handling

When an invalid operation occurs, the application stops showing the result until it is corrected, despite presenting invalid operations, it does not crash. Operations with a denominator of 0 give an infinity answer, or 0/0 give NaN (Not a Number) due to their indeterminacy or lack of agreement between the mathematical union.

## Hierarchy order

The application handles the hierarchical order of the applications, it performs the exponents first, then the multiplications and divisions before the addition and subtraction. In the case of operations of the same hierarchical level, the leftmost operation is performed first for convenience.

### Processing engine

A third-party library has been used: **Rhino** which was developed by mozilla, which is a **JavaScript** engine that evaluates the string it receives as a parameter and evaluates the text string, it should be noted that not only It processes mathematical operations but it could also evaluate any expression that is commonly used in JS.

> **Note:** It was considered that the criterion to evaluate would be knowledge about **Android Studio**, We don't need to reinvent the **wheel**, we just need to **hire** someone who already **knows** how to make the **system work**.



## Imagenes

<img src=/mock-ups/1.png/>
<img src=/mock-ups/2.png/>
<img src=/mock-ups/3.png/>

## APK
You can find the apk under the folder apk.
