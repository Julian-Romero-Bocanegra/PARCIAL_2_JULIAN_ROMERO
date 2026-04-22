# PARCIAL_2_JULIAN_ROMERO
Integrantes: Edwin Stiven Pasto / Julián Romero Bocanegra \
Docente: Diego Alejandro Barragán Vargas. \
Institución: Fundación Universitaria Compensar.

### Parte Conceptual
#### Responda las siguientes preguntas

#### LACHT:
Es un aparato asincronico, quiere decir que va en contra de las manecillas de reloj, y tiene dos niveles (alto y bajo), si la entrada esta en el nivel alto su salida cambiara de la misma manera en que cambia su entrada.

##### TIPOS DE LACHT 
###### LACHT SR (SET - RESET):
Se pone 1 para SET y 0 para RESET, si sus entradas estan en el mismo estado, quiere decir 1 - 1 o 0 - 0 su salida no cambia.

###### LACHT D 
Tiene una sola entrada, si esta enable su salida es lamisma.
 
#### FLIP FLOPS
Es un aparato de bloque fundamentales, tiene una subidad (1 y 0) y bajada (0 y 1).ayudan a la construccion de circuitos secuenciales y ademas tiene la capacidad de almacenar información.

##### TIPOS DE FLIP FLOPS
###### FLIP FLOP SR
Tiene un funcinamiento parecido al LACHT SR, para SET se estable salida en alto 1 y para RESET se establece en bajo 0,  tambien si sus estradas estan iguales 1 - 1 es invalido.
<img width="390" height="186" alt="image" src="https://github.com/user-attachments/assets/2cd921e3-6ba8-455f-a2bf-c93ad65cef4f" />
(imagen tomada: de la clase del 15 de abril del 2026, sistemas digitales)

###### FLIP FLOP D 
Es un dispositivo sincronico con el reloj, captira su entrada y la mantiene en la salida
<img width="677" height="244" alt="image" src="https://github.com/user-attachments/assets/245fa695-6d26-4b5f-9782-c2bd459365f7" />
(imagen tomada: de la clase del 15 de abril del 2026, sistemas digitales)

###### FLIP FLOP TOGGLE
Hace algo parecido a lo del FLIP FLOP JK cambia la estrada 1 a 0 y puede mantener el estado anterior.
<img width="731" height="374" alt="image" src="https://github.com/user-attachments/assets/6e5edd83-bef0-4128-853e-33fa7f4a5985" />
(imagen tomada: de la clase del 15 de abril del 2026, sistemas digitales)

###### FLIP FLOP JK  
Es el dispositivo mas usado y puedes solucionar el problema del FLIP FLOP SR cuando sus entradas estan iguales puedes cambiar alguna de las entradas para evitar que sigan igual.
<img width="692" height="378" alt="image" src="https://github.com/user-attachments/assets/090cfada-f826-44cb-8593-6824ae9a2676" />
(imagen tomada: de la clase del 15 de abril del 2026, sistemas digitales


#### MULTIPLEXOR
Es un circuito secuencial que actua como filtro de datos digitales, selecciona entre varias lineas de entrada de datos y la dirige a una sola linea de salida.

##### EJEMPLO
<img width="302" height="393" alt="image" src="https://github.com/user-attachments/assets/9ef38243-159a-42c3-8b42-04529e0fc41a" />

#### DEMULTIPLEXOR
Hace la operacion inversa al multiplexor recibe informacion atravez de una sola linea de entrada y la distribuye entre multiples lineas de salidas disponibles.

##### EJEMPLO
<img width="501" height="420" alt="image" src="https://github.com/user-attachments/assets/0516194e-91b7-49cd-900e-f675b6a5d0bc" />

#### SUMADOR COMPLETO
Incorpora una entrada denominada acarreo, le permite procesar el acarreo generado por la columna de bits menos significativa.

#### SUMADOR MEDIO
Es un circuito medio aritmetico cpaz de realizar una suma binaria de 2 bits individuales y genera 2 salida (la suma y el acarreo)

#### CIRCUITO SECUENCIALES
Es un sistema cuya salida no solo dependen de sus entradas, si no tambien del historial, almacenada en los elementos de memoria.

###### SINCRONOS
El cambio de estado ocurre en momento especificos por la señal del reloj.

###### ASINCRONOS
El cambio del estado ocurre en cualquier momento a cambios de las entradas comunes.

#### MAPA KARNAUGHT 
Es una herramienta grafica que se usa para la simplificación de funciones booleanas, por medio del mapa de karnaught se puede reducir expressiones logicas a su forma minima.

Su estructura consiste en celdas donde cada celda representacion una combinación unica de diferentes variables de entrada.

### Parte de Diseño
### Primer (1er.) punto
<img width="566" height="80" alt="image" src="https://github.com/user-attachments/assets/a0a67e99-8ee2-4cbd-b65e-a4d4610aa8ee" />

### Segundo (2do.) punto
<img width="594" height="80" alt="image" src="https://github.com/user-attachments/assets/0cd34ef0-d7d6-40fb-b702-f7e127831861" />

dibujar circuito y tabla de verdad

### Parte Empirica
#### CHATBOT
El bot está programado para discutir la evolución de la industria, centrándose en hitos como la litografía de menos de 2nm y la integración de hardware especializado para Inteligencia Artificial.

Estructura inicial donde nos sujetamos a gemini como IA de soporte por medio de API.
<img width="1168" height="193" alt="image" src="https://github.com/user-attachments/assets/ed942e5e-fa4e-4343-ab96-10bc33d156fe" />

El PROMT necesario para que nuestro chatbot sea un experto y darle la personalidad.
<img width="1680" height="418" alt="image" src="https://github.com/user-attachments/assets/c67d2a79-7191-4f6d-8a58-e7ec555d7177" />

Diseño del interfaz del CHATBOT.
<img width="1209" height="327" alt="image" src="https://github.com/user-attachments/assets/c9fcf43b-eb4c-4c17-a98d-6a51cba41f00" />

Prueba del chatbot
<img width="1733" height="385" alt="image" src="https://github.com/user-attachments/assets/d9655e55-3292-42b7-bb94-64c37df1c3d4" />
