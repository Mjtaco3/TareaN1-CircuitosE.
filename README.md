# TareaN1-CircuitosE.
                                
![](https://www.espe.edu.ec/wp-content/uploads/2022/01/ESPEtransparente.png)

Nombre: 	Mauricio Taco

NRC:		10069

Carrera: 	Mecatrónica

Fecha: 	31-10-2022

1.- OBJETIVOS

Objetivo general

Objetivos especificos
    
2.-MARCO TEORICO

Capitulo 1

Para poder iniciar en la concepción de electrónica es necesario que los usuarios posean un conocimiento concreto acerca de las unidades de medición tanto fundamentales como sus derivadas (composición de dos o más unidades fundamentales), para este caso aquellas unidades básicas definidas por el sistema SI son:      

![](https://matemovil.com/wp-content/uploads/2019/01/unidades-b%C3%A1sicas-o-fundamentales-del-sistema-internacional3.jpg)

Según El Sistema Internacional de Unidades, (2020):

SI es el sistema adoptado internacionalmente, utilizado en la práctica científica y el único legal en España, en la Unión Europea y en numerosos otros países. El SI parte de un pequeño número de magnitudes/unidades denominadas básicas definiendo, a partir de ellas, las denominadas derivadas, como producto de potencias de las básicas. Cuando este producto de potencias no incluye ningún factor numérico distinto de la unidad, estas unidades derivadas se denominan coherentes. Así pues, el SI es un sistema coherente de unidades, que permite cuantificar cualquier magnitud medible de interés en la investigación, la industria, el comercio o la sociedad, en campos tan variados como la salud, la seguridad, la protección del medio ambiente, la adquisición de bienes o la facturación de consumos.

![image](https://user-images.githubusercontent.com/116677544/201148531-c71448d5-de6c-4d9a-a8fb-78286b9dc465.png)

Con la finalidad de simplificar la expresión de las unidades más complejas se optó por usar símbolos literales para representar tanto las unidades como cantidades de medición.

![image](https://user-images.githubusercontent.com/116677544/201148649-53d259f9-aba3-4d5e-89e4-7af9b19be3a9.png)

-Notación científica y Notación de ingeniería-Prefijos métricos 

![image](https://user-images.githubusercontent.com/116677544/201148772-f598e24e-9dad-4127-b003-05aacc67c171.png)

![image](https://user-images.githubusercontent.com/116677544/201148832-d67f325a-a8bd-4621-b1a2-fbd49ecab146.png)

Capítulo 2

![image](https://user-images.githubusercontent.com/116677544/201148944-bde7d469-97a6-4c0c-a71b-685333d21b9c.png)

![image](https://user-images.githubusercontent.com/116677544/201148985-08fa3a9f-a495-40de-b033-090b5aca21d4.png)

![image](https://user-images.githubusercontent.com/116677544/201149023-89fe103a-67e8-4c5c-8c98-3117aae8fb56.png)

![image](https://user-images.githubusercontent.com/116677544/201149052-ea3e74b0-40cf-486b-9db2-7488b9f5be3e.png)

->Resistores variables:

Los resistores variables como su nombre lo indica son aquellos que pueden cambiar su resistividad de acuerdo a un ajuste manual o automático. 

-Resistor variable manual -Función

1.	Potenciómetro: dividir el voltaje

Compuesto de 3 terminales, donde 1 y 2 son resistencias fijas mientras que 3 esta conectado a un contacto móvil (rozador), puede ser usado como reóstato conectando los terminales 2 y 3

2.	Reóstato: controlar corriente- formado por 2 terminales
 
 ![image](https://user-images.githubusercontent.com/116677544/201149553-36c2a10e-dbe9-4a53-9ef5-914b2a8ffb45.png)

ambos resistores se pueden clasificar como lineales y no lineales (ajustables), refiriéndonos a de lineales la resistencia entre los terminales y contacto móvil varia linealmente con la posición del contacto móvil (la mitad del movimiento equivale a la mitad del valor de la resistencia total) 

 ![image](https://user-images.githubusercontent.com/116677544/201149611-222ceb4f-f56c-42a8-a89f-db3ef9593190.png)
 
El potenciómetro ajustable la desasistencia no varia linealmente con la posición del contacto móvil, de tal manera que la mitad de una vuelta del potenciómetro no necesariamente es igual a la mita de la resistencia total que posee, siendo este valor arbitrario.

-Resistor automatico variable

![image](https://user-images.githubusercontent.com/116677544/201149994-51232880-352c-49a1-8643-6ea313265ee7.png)

Termistor: resistor variable sensible a la temperatura

1. Relación inversa entre temperatura negativa y resistencia
     
2.Relación directa entre temperatura positiva y resistencia
     
Otro ejemplo resistor automático variable es la celda fotoconductora donde su resistencia cambia en función de la luminosidad a la que esta expuesta. 
 
 ![image](https://user-images.githubusercontent.com/116677544/201150053-272f4c8a-5cce-499f-8a43-995c4ff7fe04.png)

-El circuito eléctrico 

Agrupación ordenada de componentes físicos/eléctricos que utilizan voltaje, corriente y resistencia para realizar una función o trabajo predeterminado por el operador

-Dirección de corriente eléctrica:

![image](https://user-images.githubusercontent.com/116677544/201150453-975a88d0-67e4-4ba7-83d5-e516af9a46aa.png)

-Convenciones aceptadas de dirección eléctrica:

1. Dirección de flujos de electrones: propósitos de análisis donde la corriente sale de la terminal negativa pasa a través del circuito hasta llegar al terminal opuesto de la fuente de voltaje.
     
2. Dirección convencional de la corriente: la corriente se trasporta desde el terminal positivo hasta llegar a terminal opuesto, analizando el voltaje en esta convención se aprecia una disminución del mismo tomando como referencia la fuente de voltaje y un resistor. “Como en realidad no se puede ver la corriente, sólo sus efectos, no importa qué dirección se suponga en tanto sea utilizada consistentemente” (Floyd, 2007), sabiendo esto podemos decir que el uso de la convención en la dirección de la corriente no afecta el análisis efectuado.
     
-Circuito básico 

Con respecto al circuito básico Villegas (2018) menciona:

Se denomina así a la trayectoria cerrada que recorre una corriente eléctrica. Este recorrido se inicia en una de las terminales de una pila, pasa a través de un conducto eléctrico (cable de cobre), llega a una resistencia (foco), que consume parte de la energía eléctrica; continúa después por el conducto, llega a un interruptor y regresa a la otra terminal de la pila.

![image](https://user-images.githubusercontent.com/116677544/201150238-808acb3d-f621-43bd-97be-681590e18a75.png)
 
-Diagrama esquemático de un circuito eléctrico 

Un circuito eléctrico puede representarse de forma esquemática o abstracción de la realidad, básicamente cada elemento físico puede representarse mediante un símbolo que facilite la organización y análisis teórico de un circuito
  ![image](https://user-images.githubusercontent.com/116677544/201153756-f848a21b-cae0-4916-b1c3-d81a1216883e.png)

-Protección y control de la corriente en un circuito

1. Circuito cerrado: la corriente recorre una trayectoria completa de un termina a otro
2.Circuito abierto: cuando la trayectoria de la corriente se interrumpe

![image](https://user-images.githubusercontent.com/116677544/201153882-16368d21-f555-46b7-b9b7-d067bd656d19.png)

-Interruptor mecánico 

Controlar apertura o cierre de un circuito eléctrico denominados como interruptores prácticamente conectando 2 extremos de un conductor.
  
Tipos de interruptores: 
  
1. SPST y SPDT: interruptor de una y doble vía
 
2.Vía única-doble polo (DPST): Apertura y cierre de dos juegos de contactos

3. Doble vía-doble polo (DPDT): Conexión de un juego de contactos

4. Botón pulsador (PB): Conexión cuando existe presión en caso de ser abierto

5. Rotatorio: Conexión entre un contacto y otros terminales

![image](https://user-images.githubusercontent.com/116677544/201154118-bc37b2d9-3e47-4c33-a80d-a0c02717141c.png)

-Interruptor semiconductor

Un transistor es un elemento semiconductor que se puede usar como conductor, “Cuando se utiliza el transistor como interruptor o switch, la corriente de base debe tener un valor para lograr que el transistor entre en corte y otro para que entre en saturación.” (Unicrom, 2020)
 
 ![image](https://user-images.githubusercontent.com/116677544/201151817-af092ba3-9435-433a-88a1-f6fa5f7dac9a.png)

-Dispositivos de protección 
1.	Fusible 
![image](https://user-images.githubusercontent.com/116677544/201154357-afccf23e-4ef2-42ef-834e-0b5ad2befd5f.png)

2.	Cortacircuitos
![image](https://user-images.githubusercontent.com/116677544/201154673-8cd652fa-42d2-4d87-be36-8f2203c9062e.png)

Se utilizan con la finalidad de proteger a los elementos eléctricos dentro del circuito cuando la corriente excede una cantidad especifica de amperes a causa de una condición anormal. La diferencia entre un fusible y cortacircuitos es la reutilización y remplazo del elemento de protector. cuando se excede el amperaje estimado en un fusible su filamento interno se rompe causando que el fusible tenga que ser remplazado por uno nuevo, mientras que el cortacircuitos al presenciar un amperaje mayor al soportable únicamente se “abre” impidiendo el paso de corriente atreves del circuito.
  
-Alambre o conductor

“Los materiales conductores son aquellos que, en mayor o menor medida, son capaces de conducir electricidad. Este tipo de materiales permiten el desplazamiento libre y fluido de electrones de un punto a otro” (características, 2022).
Los cables conductores varían de diámetros y son arreglados en un arreglo de número, donde el diámetro del alambre es inversamente proporcional al numero de cable, sistema AWG(American Wire Gauge).
  
  ![image](https://user-images.githubusercontent.com/116677544/201154885-dd39dba9-f3f4-4f1d-b444-26c234f523f4.png)

-Tierra

Punto de referencia en común (COM o COMM) con carga negativa que comparte un cuerpo al que se le puede añadir varios componentes para cerrar el circuito. Puede representarse de tres maneras distintas tanto una tierra en tierra (instalaciones domesticas), tierra de chasis (campo eléctrico/automotriz) y Tierra de referencias o común.

![image](https://user-images.githubusercontent.com/116677544/201154956-98dc82d0-d13a-4827-9c3b-52d53d65761b.png)

-Mediciones de circuitos básicos 
	
Dentro del análisis de unidades eléctricas aplicada en un circuito se debe tener en consideración obligatoria la presencia de voltaje, corriente y resistencia mismo que poseen sus propias unidades de medida siendo estas los voltios, amperios y ohmios respectivamente. Estas unidades se pueden medir por separado sea con un voltímetro, amperímetro y óhmetro o simplemente con un único elemento de medición electrónica conocido como multímetro en sus dos variantes tanto digital como analógica
  
-Toma de mediciones

1.	Voltaje: conexión en paralelo al elemento a medir terminal positivo a la parte positiva del elemento según el circuito y negativa respecto al terminal opuesto del elemento- Nota: Colocar multímetro en (V) 
2.	Amperios: conexión en serie, se utiliza a la herramienta de medición como un conductor para el flujo de carga- Nota: Colocar el multímetro en (A)
3.	Resistencia: se mide con el elemento separado del circuito eléctrico o independiente – Nota: Colocar el multímetro en ohm

-Multímetros digitales

DMM por sus siglas en ingles es un instrumento eléctrico que combinas los medidores anteriormente mencionados para efectuar lecturas o mediciones de voltaje, corriente y resistencia. Por lo general un multímetro digital incluye varias funciones adicionales (prueba de transistores, diodos, continuidad, medición de potencia y decibeles) de medición con respecto a su contraparte el multímetro analógico, además de presentar mayor precisión y confiabilidad a la hora de realizar cualquier tipo de medición. Sin embargo, no pueden rastrear, en una cantidad variaciones y tendencias a corto plazo.

![image](https://user-images.githubusercontent.com/116677544/201155414-2c44c9bc-0673-4e5f-bb6a-ae82dceb2f44.png)

Según Floyd(2007) afirma:

La resolución de un multímetro digital es el incremento más pequeño de una cantidad 
	que el medidor puede medir. Mientras más pequeño es el incremento, mejor es la resolución. 	Un factor que determina la resolución de un medidor es el número de dígitos que aparecen en 	pantalla.
  
Ya que muchos multímetros digitales tienen 31⁄2 dígitos en su pantalla, se utilizará este caso 	como ilustración. Un multímetro de 31⁄2 dígitos tiene tres posiciones por dígito que pueden 	indicar desde 0 hasta 9, y una posición por dígito que puede indicar sólo un valor de 0 o 1. Este 	último dígito, conocido como medio dígito, es siempre el más importante en la pantalla. (pg.53)
  
-Presición  
La presición es el grado al cual un valor medido representa el valor  verdadero o aceptado de una cantidad, para ello influyen factores fisicos como la circuiteria interna del multimetro y la calibracion del mismo, por lo general la presicion oscila en un intervalo de 0.01% y 0.5%.
  
-Lectura de un multimetro analògico

![image](https://user-images.githubusercontent.com/116677544/201155111-3d628833-5b65-48fa-b247-7e43f095a0d7.png)

 
Por lo general este tipo de multimetro  se usan para medur tanto corriente directa como corriente alterna, asi como resistencia. Consta de 4 funciones:
1-	Volts de cd (DC VOLTS)
2-	Miliamperes de cd (DC mA)
3-	Volts de ca (AC VOLTS)
4-	OHM
Cada funcion del multimetro se encuentra desglozada por distintos intervalos con la finalidad de medir esclas de unidades completas referente a un trabajo.

-Escala de ohms
Los ohms se encuentran en la parte suoerior del medidos, escala no lineal(los valores valores de cada division varian conforme recorre la escala),esta escala se comprime de derecha a izquierda.Para interpretar los valores de resistencia del multimetro se debe considerar los multiplicadores de unidades [x1,x10,x100,x100,x100 000]
  
-Escalas AC-DC y DC mA

Segunda, tercera y cuarta escala respectivamente considerando la parte superior de la pantalla como referencia hacia abajo.
La escala superior ac-dc termina en la marca de 300 y se usa con ajustes de intervalo, tales como 0.3, 3 y 300. Por ejemplo, cuando el interruptor está en 3 en la función DC VOLTS, la escala de 300 tiene un valor de es-cala completa de 3 V; en el ajuste de intervalo de 300, el valor de escala completa es de 300 V. La escala ac-dc intermedia termina en 60. Esta escala se utiliza junto con ajustes de intervalo, tales como 0.06, 60 y 600. Por ejemplo, cuando el interruptor está en 60 en la función DC VOLTS, el valor de escala completa es de 60 V. La escala ac-dc inferior termina en 12 y se utiliza junto con ajustes del interruptor, tales como 1.2, 12 y 120. Las tres escalas Dc mA se utilizan en la misma forma. (Floyd, 2007, pág. 54).

-Choque electrico

Cuando la corriente pasa atrabez de nuestro cuerpo es la causa del choque electrico, se necesita que el voltaje pase por una resistencia para generar corriente, cuando un punto del cuerpo se expone a un voltaje y otro a un voltaje distinto o con tierra, la trayectoria de la corriente dependera de dichos puntos recorriendo asi nuestro cuerpo.

![image](https://user-images.githubusercontent.com/116677544/201155201-20786960-3bfd-4f89-a910-1b69076e4228.png)
 
-Resistencia corporal

La resistencia del cuerpo humano oscila entre 10 a 50 kiloohmios y depende de los puntos donde se mida, como de factores externos(humedad de la piel), esta resistencia determinara la cantidad de voltaje que se requiere para producir una afeccion al cuerpo.
  
-	Precausiones de seguridad
1.	Evite el contacto con cualquier fuente de voltaje
2.	Corte el suminunistro de energia antes de trabajar en un circuito, decargue capacitores
3.	No trabaje solo
4.	No trabaje cuando se encuentre con fatiga o cansancio 
5.	Equipo con cordones de corriente de tres hilos
6.	Herramientas en condicion adecuada
7.	Manejo apropiado de herramientas 
8.	Uso de EPPs
9.	Cuide su entorno de trabajo
10.	“Si otra persona no puede zafarse de un conductor energizado, corte la corriente de inmediato. Si esto no es posible, use cualquier material no conductor para tratar de apartar su cuerpo del contacto” (Floyd, 2007)

3.- EJERCICIOS CAPITULO 1 y 2

![image](https://user-images.githubusercontent.com/116677544/201155833-d771699a-3d98-4f95-8185-8bc67f41dc6a.png)

![image](https://user-images.githubusercontent.com/116677544/201155942-68c9d3bb-c3e0-45bd-b43f-b1f083dae290.png)

![image](https://user-images.githubusercontent.com/116677544/201156023-2640d684-8dd2-4b2a-8b1b-d8a0d1eabbe6.png)

![image](https://user-images.githubusercontent.com/116677544/201156240-55622f69-c21d-4b74-9a6f-54874658fa11.png)

![image](https://user-images.githubusercontent.com/116677544/201156313-05e66fa5-f0b6-4c46-8972-a282ee902afd.png)

![image](https://user-images.githubusercontent.com/116677544/201156501-f06aa9ad-51d4-4fcb-a58f-e2d586bebddf.png)

![image](https://user-images.githubusercontent.com/116677544/201156645-c7af536f-08f2-40ff-8325-272ddff2ee39.png)

![image](https://user-images.githubusercontent.com/116677544/201156753-2188a651-b045-4be3-9913-bd46d02a6d58.png)

![image](https://user-images.githubusercontent.com/116677544/201156823-e7058390-87a1-4603-9472-5a3796153bc3.png)

4.-VIDEOS

5.-CONCLUSIONES

6.-BIBLIOGRAFIA

características, Q. s. (09 de noviembre de 2022). Qué son los materiales conductores y sus características. Obtenido de Ferrovial: https://www.ferrovial.com/es/recursos/materiales-conductores/

El Sistema Internacional de Unidades, S. (12 de enero de 2020). Obtenido de Centro Español de Metrología: https://www.cem.es/es/cem/metrologia/sistema-internacional-unidades-si

Floyd, T. (2007). Principios de circuito electricos (Vol. Octava edición ). PEARSON EDUCACIÓN.

Unicrom, E. (9 de marzo de 2020). Transistor como interruptor o switch – Diseño. Obtenido de Electrónica Unicrom: https://unicrom.com/transistor-como-interruptor-switch/

