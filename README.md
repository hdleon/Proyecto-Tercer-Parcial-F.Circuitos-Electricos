# Proyecto-Tercer-Parcial-F.Circuitos-Electricos

**Integrantes**

Josue Chavez

Domenica Espin

Henrry Leon

## Objetivo de la practica

Realizar un circuito  

## Objetivos especifico

- Analizar el funcionamiento del circuito 

-	Armar experimentalmente el circuito analizado.

## Marco Teorico

![Mapa mental](https://user-images.githubusercontent.com/116777118/221868641-ef493e15-4d14-4243-969c-6b617a4fb7ec.jpeg)

##  Material o Equipo

![image](https://user-images.githubusercontent.com/116777118/221866528-f70d779f-5055-4a33-8ece-3949494cb30a.png)

![image](https://user-images.githubusercontent.com/116777118/221866574-1195c5c6-a5f7-4567-a7d2-43c1ea7d81c3.png)

##  Procedimiento

1. Se coloca el circuito integrado LM386 de tal forma que sus cuatro terminales izquierdas estén en una pista y los otros cuatro en la pista pasando el canal central. 

![image](https://user-images.githubusercontent.com/116777118/221868890-3ac7ff01-6b91-4d37-9f63-c1fdfc16dce3.png)

2. Con un cable realizamos conexión del terminal 2 al terminal 4 

![image](https://user-images.githubusercontent.com/116777118/221869671-6624f173-388b-48d5-989e-647fd0b2fb93.png)

3. Se conecta la terminal positiva del condensador al terminal 5 del circuito integrado, mientras que la terminal negativa se conectará en un punto fuera de conexión por el momento.  

![image](https://user-images.githubusercontent.com/116777118/221869880-465c5a81-fb27-4fba-9753-08ef21f0c75d.png)

4. Se conecta el potenciómetro 

![image](https://user-images.githubusercontent.com/116777118/221869962-b5e88100-9d36-40a1-a1e3-69f6d3d3f115.png)

5. Se conecta con un cable la terminal 2 del circuito integrado hacia la terminal izquierda del potenciómetro 

![image](https://user-images.githubusercontent.com/116777118/221870043-baed95a3-030b-4591-a638-f1d574a9a486.png)

6. Se conecta con un cable la terminal 3 del circuito integrado hacia la terminal central del potenciómetro

![image](https://user-images.githubusercontent.com/116777118/221870148-2c779b76-2da9-4670-8218-bf4714dd323d.png)

7. Se conecta un cable del plug para sonido hacia la terminal 4 del circuito integrado y el otro cable hacia la terminal derecha del potenciometro. 

![image](https://user-images.githubusercontent.com/116777118/221870252-b542fa26-be7c-4564-9b2d-9dc69e29113a.png)

8. Se realiza un puente desde la terminal 2 del circuito integrado hacia el bus negativo de la protoboard 

![image](https://user-images.githubusercontent.com/116777118/221870302-abca48e1-bdbf-4658-bd71-da567447da5f.png)

9. Se realiza un puente desde la terminal 6 del circuito integrado hacia el bus positivo de la protoboard 

![image](https://user-images.githubusercontent.com/116777118/221870610-6c28cebc-db84-4d23-bb8d-61094a3df51e.png)

10. Se conecta un cable de la bocina hacia el terminal negativo del condensador y el otro cable hacia el terminal 4 del circuito integrado 

![image](https://user-images.githubusercontent.com/116777118/221870550-c146c3bf-082f-44b9-9dd8-3a397b513413.png)

11. Por último, se conecta la batería hacia los buses correspondientes de la proto, y además se conecta el plug de sonido al dispositivo a utilizar. 

![image](https://user-images.githubusercontent.com/116777118/221870488-fab1958e-46a9-4ee0-80e1-bfef2d82be4e.png)

## Diagrama esquemático

![WhatsApp Image 2023-02-27 at 7 12 39 PM](https://user-images.githubusercontent.com/116777118/221871527-52b6c7cf-8f35-4955-8895-aa496a9b38bd.jpeg)

## Explicacion de funcionamiento

En términos generales, un amplificador es un elemento con un circuito electrónico que puede aumentar la intensidad de la tensión, la corriente o la potencia de una señal que se aplica en su entrada; posteriormente, la señal se recibe aumentada en la salida.

Este Amplificador de audio 0,5W con LM386 es un amplificador de potencia que está diseñado especialmente para aplicaciones en computadoras, radios, pero puede ser utilizado en cualquier sistema de amplificación de audio.

Este amplificador está diseñado para ser conectado a parlantes de 8 ohmios, pero sí solo hay disponibles parlantes de 8 ohmios, podemos colocar dos en paralelo.

La señal de entrada se aplica al pin 6 del LM386. La señal de salida se obtiene en el pin 4. El condensador se conecta al pin 5 con el fin de almacenar la carga de salida al parlante que se disparara para amplificarla.  Por otra parte, el potenciómetro atenúa la señal ya que crea las fluctuaciones de voltaje de la señal de audio original. 

Por esta razón, la señal es potenciada por un pre-amplificador, el cual envía una señal de salida más fuerte al dispositivo.

El pre-amplificador funciona de una manera muy parecida al amplificador: el circuito de entrada aplica una resistencia variable a un circuito de salida generado por la fuente de alimentación. Algunos sistemas de amplificadores usan varios pre-amplificadores para gradualmente construir una señal de salida de alto voltaje.

Este circuito integrado puede ser alimentado con voltajes que van de los 5 hasta los 20 V, pero en caso de que la señal amplificada esté distorsionada se recomienda colocar este voltaje de alimentación entre los 6 y 12 voltios. La distorsión también puede ser causada debido a la excesiva amplitud de la señal de entrada, en este caso se recomienda atenuarla con ayuda de un potenciómetro.

## Video

https://youtu.be/Xrey1Yituq4

## Conclusiones
