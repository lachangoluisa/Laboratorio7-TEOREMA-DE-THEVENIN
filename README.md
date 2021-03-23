
# Laboratorio7-TEOREMA-DE-THEVENIN

OBJETIVOS

Demostrar experimentalmente el teorema de Thevenin  para resolver un circuito

OBJETIVOS ESPECIFICOS

Aplicar la teoria de Thevenin  para conseguir un circuito mas sencillo de resolver

Comparar los calculos con los resultados practicos y determinar  cual es el error entre los datos ontenidos en la practica y los valores calculados


MARCO TEÓRICO

El teorema de Thevenin establece que un circuito lineal de dos terminales puede sustituirse por un circuito equivalente
Es decir, el teorema de Thevenin proporciona una técnica para sustituir la parte fija por un circuito equivalente sencillo.

Si el circuito original posee muchas resistencias, y se desea calcular intensidad, tensión o potencia de alguna de estas, o que se ubique entre los puntos A y B de un circuito grande, se puede simplificar el proceso a través del teorema de Thevenin. Se establece que es posible construir un circuito equivalente más pequeño, comprendido por una resistencia y una fuente de tensión dispuestos en serie. Los valores asignados a cada uno de estos se conoce como resistencia de Thevenin y tensión de Thevenin, que serán equivalentes al valor de la resistencia entre A y B, conocida como resistencia de carga.

![Circuito-de-Thevenin](https://user-images.githubusercontent.com/76057459/112097385-e7b49600-8b6d-11eb-835c-bd0b8f91fc59.jpg)

![Untitled Document](https://user-images.githubusercontent.com/76057459/112117135-02e0cf00-8b89-11eb-80b8-e0cace648ac6.png)


DIAGRAMAS

![diagrama circuito](https://user-images.githubusercontent.com/76057459/112098032-12ebb500-8b6f-11eb-9140-0cbc5065ff2e.jpeg)

![WhatsApp Image 2021-03-23 at 2 18 46 AM](https://user-images.githubusercontent.com/76057459/112108495-41bd5780-8b7e-11eb-8cff-b829ea63e316.jpeg)


LISTA DE COMPONENTES

![elementos circuito](https://user-images.githubusercontent.com/76057459/112097894-d7e98180-8b6e-11eb-82b0-383eff8ab08f.jpeg)



7.- DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN


Para poder aplicar este teorema es necesario tener conocimiento varios métodos estudiados previamente como lo son: resolución de circuitos por medio de mallas y nodos, superposición, resistencia equivalente, etc.

PASOS PARA APLICAR TEOREMA DE THEVENIN

Cuando se construye un circuito equivalente de Thevenin, es posible realizar cálculos más sencillos y en menos tiempo que al trabajar con el circuito completo original. Para lograr aplicar el teorema correctamente, se deben realizar estos pasos:

Al eliminar las fuentes de alimentación del circuito original, será posible encontrar la resistencia de Thevenin. Luego se deberá calcular el valor de la resistencia total que existe entre los punto A y B donde se encuentre conectada la resistencia de carga.
Para el caso de hallar la tensión de Thevenin, se elimina la resistencia de carga, y se calcula el voltaje de los puntos de conexión abiertos donde esta se encontraba.
Construye el circuito equivalente utilizando la tensión de Thevenin y la resistencia de Thevenin en serie. Conecta la resistencia de carga entre los puntos de conexión abiertos de este circuito.
Utilizando las reglas de circuitos en serie, se analiza la tensión y corriente de la resistencia de carga.

PROCEDIMIENTO

1.Arme el circuito que se muestra en la figura 5.1.![WhatsApp Image 2021-03-23 at 2 18 46 AM](https://user-images.githubusercontent.com/76057459/112191247-d1412580-8bd3-11eb-88c5-7fef2890b3bf.jpeg)
    
2.Mida el voltaje y la corriente en el resistor R5, anote los resultados en la tabla 5.2.![WhatsApp Image 2021-03-23 at 1 09 51 AM](https://user-images.githubusercontent.com/76057459/112191437-03eb1e00-8bd4-11eb-85e4-83e587f81a9a.jpeg)
![WhatsApp Image 2021-03-23 at 1 05 22 AM](https://user-images.githubusercontent.com/76057459/112191502-149b9400-8bd4-11eb-8034-a739b2778984.jpeg)

3.Desconecte el resistor R5 y mida el voltaje en el circuito abierto. Anote el valor
medido en la tabla 5.1.![WhatsApp Image 2021-03-23 at 1 12 54 AM](https://user-images.githubusercontent.com/76057459/112191560-23824680-8bd4-11eb-8810-4ac69781438b.jpeg)

4.Anule el efecto de las fuentes de alimentación. Desconecte R5 y desde el circuito
abierto resultante mida la resistencia equivalente. Anote el valor medido en la tabla 5.1.
![WhatsApp Image 2021-03-23 at 2 18 46 AM (3)](https://user-images.githubusercontent.com/76057459/112191727-4ca2d700-8bd4-11eb-842e-664e7b531e35.jpeg)

5.Implemente el circuito equivalente de Thévenin, agregue el resistor R5 y mida la
corriente y el voltaje en el mismo, anote los resultados en la tabla 5.2.![WhatsApp Image 2021-03-23 at 2 18 46 AM (4)](https://user-images.githubusercontent.com/76057459/112191802-5fb5a700-8bd4-11eb-8185-a412a3a9deef.jpeg)
![WhatsApp Image 2021-03-23 at 2 18 46 AM (5)](https://user-images.githubusercontent.com/76057459/112191822-65ab8800-8bd4-11eb-939b-caf2b4525f1d.jpeg)

TABULACION DE DATOS Y CALCULOS 
![WhatsApp Image 2021-03-23 at 1 52 40 PM](https://user-images.githubusercontent.com/76057459/112202218-1f0f5b00-8bdf-11eb-9847-1e60e5cc9a32.jpeg)
![WhatsApp Image 2021-03-23 at 1 52 55 PM](https://user-images.githubusercontent.com/76057459/112202226-20d91e80-8bdf-11eb-8da7-68233d8995db.jpeg)

CALCULO DEL ERROR

![WhatsApp Image 2021-03-23 at 1 55 34 PM](https://user-images.githubusercontent.com/76057459/112202519-77def380-8bdf-11eb-8d7f-4ab1612c7ba4.jpeg)

![WhatsApp Image 2021-03-23 at 1 54 43 PM](https://user-images.githubusercontent.com/76057459/112202420-5f6ed900-8bdf-11eb-8ff3-996d711ad16e.jpeg)

APORTACIONES
En este punto se indicará todo lo adicional fruto de lo investigado que se haya agregado al trabajo.

CONCLUSIONES


El teorem de Thevenin nos permite obtener un circuito equivalente , se puede calcular en menos tiempo el valor de voltajes, la corriente o hasta la potencia de un circuito una vez que se conecta una carga lo cual facilita la resolucion del circuito
Es aplicable a cualquier elemento del circuito, siempre que este cuente con una fuente independiente

BIBLIOGRAFÍA
https://www.teorema.top/teorema-de-thevenin/#Ventajas_de_aplicar_el_teorema_de_Thevenin

X. (2020, 20 julio). de Thevenin explicado para que lo Entiendas. Teorema. https://www.teorema.top/teorema-de-thevenin/

Sadiku. (sf). Teoremas de circuitos. En Sadiku, Fundamentos de Circuitos Eléctricos

Floyd, T. (2007). PRINCIPIOS DE CIRCUITOS ELÉCTRICOS. (8va ed.). México, México: Pearson Education.


ANEXOS
![WhatsApp Image 2021-03-23 at 2 18 46 AM (1)](https://user-images.githubusercontent.com/76057459/112108603-6ca7ab80-8b7e-11eb-89cc-8723d0f7760e.jpeg)![WhatsApp Image 2021-03-23 at 2 18 46 AM (2)](https://user-images.githubusercontent.com/76057459/112108648-7b8e5e00-8b7e-11eb-9bd2-e5b6d79f8162.jpeg)
![WhatsApp Image 2021-03-23 at 2 18 46 AM (3)](https://user-images.githubusercontent.com/76057459/112108679-8648f300-8b7e-11eb-8b16-f365a6cced93.jpeg)
![WhatsApp Image 2021-03-23 at 2 18 46 AM (4)](https://user-images.githubusercontent.com/76057459/112108727-99f45980-8b7e-11eb-9287-4260a04d5d0a.jpeg)
![WhatsApp Image 2021-03-23 at 2 18 46 AM (5)](https://user-images.githubusercontent.com/76057459/112108735-9f51a400-8b7e-11eb-98d6-eceabc5377b1.jpeg)
 calculos
 ![img046](https://user-images.githubusercontent.com/76057459/112203594-b75a0f80-8be0-11eb-9b94-666fb5353f63.jpg)

