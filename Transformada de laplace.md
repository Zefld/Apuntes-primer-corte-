# Transformada de LaPlace
## Sistema
Un sistema es una combinacion de componentes que actúan conjuntamente para alcanzar un objetivo especifico. La combinacion de componentes se puede representar por medio de reglas o principios que relacionan entradas con salidas.

## Sistema dinámico
- Un sistema se llama dinámico si su salida en el presente depende de una entrada en el pasado.
- Si su salida está en curso depende solamente de la entrada en curso, el sistema se comoce como estático.

## Planta
- Es todo lo fisico que permite que se lleve a cabo un proceso.
- Puede ser representado matemáticamente.
- Puede ser representado a través de uno o varios sistemas

## Proceso
- Es la secuencia de pasos que permite el desarrollo, o fabricación de un objetivo o producto
- En el area de control se usa coo sinonimo de planta (Aunque en sentido estricto no lo son)

## Modelos dinámicos
- En control interesa obtener un modelo matemático que relacione las variables de interés con el tiempo
  f(t)
- Es necesario cuantificar cuanto cambia las variables de interés con respecto al tiempo
$$\frac{df(t)}{dt}$$

## Recordando calculo diferencial
Definicion de la derivada

lim cuando h tiende a 0 de $$\frac{f(x+h)}{h}$$

## Como lucen los modelos de ecuaciones duferenciales
- Son combinaciones lineales de derivadas de diferente orden:
  
a1 $$\frac{d2F}{dt2}$$ + a2 $$\frac{dF}{dt}$$ + a3F = u(t)

- Donde F es la salida del sistema.
- U es la entrada del sistema.
- La solución no es un número, es una función.

## Caracteriaticas de una ecuacion diferencial
Pueden ser:
- Ecuaciones lineales invariantes en el tiempo
- Ecuaciones lineales variantes en el tiempo
- Ecuaciones no lineales invariantes en el tiempo
- Ecuaciones no lineales variantes en el tiempo

## Sistemas lineales y no lineales
- Un sistema se considera lineal cuando cumple con el principio de superposición
  - La respuesta de un sistema al que se le aplican 2 o más exitaciones simultaneas, es la suma de las respuestas                individuales.
 - Un sistema lineal tambien tiene la característica de proporcionalidad entre la entrada y la salida
 - Los sistemas no lineales no cumplen con el principio de superposicion
 - Los sistens bi lineales se linealizan en un punto de operacion, en el cual se cumple el principio de superposicion

## Modelamiento y validacion
- Al aplicar leyes fisicas a un modelo matemático de un sistema, se debe tener en cuenta que hay un nivel de incertidumbre en el resultado final
- Es necesario validar el modelo con respecto al sistema físico comparando la salida del modelo con la salida del modelo fisico, si no es aceptable la diferencia se debe modificar el modelo hasta conseguir una diferencia aceptable.

## Influencia de parametros
- Comportamiento sinusoidal
- Decaimiento exponencial
- Combinacion de ambos

## Transformada de LaPlace
- Es un cambio de espacio geometrico del dominio del tiempo hacia el dominio de la frecuencia compleja.
- Ecuaciones con derivadas son transformadas en ecuaciones algebraicas
- La transformada de LaPlace muestra las exponenciales y sinusoidales presentes en una señal.

## Calculo de transformada inversa
- Si las funciones son simples, utilizar la tabla de transformadas
- Si las funciones son una combinacion o composicion de varias funciones:
  - Calcular la integral de la definicion de la transformada inversa de LaPlace
  - Realizar una expansión en fracciones parciales para obtener una suma de funciones mucho más simples que se puedan encontrar en las tablas de transformadas. 

## Conclusiones
Por medio de las ecuaciones diferenciales y la transformada de LaPlace podemos realizar modelamientos matemáticos acerca de fenomenos fisicos; además, la transformada de LaPlace nos permite resolver ecuaciones diferenciales de una manera rápida.


