# Autotipía

En casi todos los sistemas de impresión, las tintas funcionan siempre con la misma intensidad, es decir: no se puede aplicar una misma tinta de forma más clara o más oscura. El proceso es **binario**: se aplica, o no se aplica tinta, sobre cierta superficie.

Es por esto que solemos decir que las **formas impresoras** tienen _zonas impresoras_ y _zonas no impresoras_.

Mientras se realicen trabajos con elementos llamados “pluma”, en la jerga del trabajo gráfico, no hay ningún inconveniente con esto. Texto, imágenes con líneas plenas y definidas, fondos de color pleno, etc. Sin embargo, la incógnita es ¿cómo se logran los medios tonos, entonces?

## La autotipía

Por medio de un grafismo, una **trama**, logramos dar la sensación de cambio en el valor tonal. De ahí que cuando uno elige tinta negra al 50%, o cian al 30% —por ejemplo—, la computadora le indicará al CTP que en la forma impresora debe generar una trama donde cubra el 50% ó el 30% de la superficie.

![](http://tecnologiagrafica1.files.wordpress.com/2012/11/autotipc3ada.jpg)

## CMYK

Cuando se suman más tintas (más colores) el asunto se complica, porque la superposición de tramas por lo general hace aparecer un efecto no deseado, llamado _efecto Moirè_.

[caption id="attachment_285" align="alignnone" width="283"][![Efecto Muaré](http://tecnologiagrafica1.files.wordpress.com/2012/11/trama-chiste-02.jpg)](http://juanjomegias.wordpress.com/2010/09/29/puntos-y-tramas/ "Tramas y comic, por Juanjo Mejías - algunos datos extra en relación a la industria del comic") Tramas y comic, por Juanjo Mejías - algunos datos extra en relación a la industria del comic[/caption]

La solución a este inconveniente es **variar los ángulos de las diferentes tintas**, de forma tal que ninguna tenga el mismo ángulo que la otra.

A continuación se pueden ver unas pruebas con las cuatro tintas al 50%. En la fila superior los colores no se encuentran tramados (como se vería en una computadora), en la segunda fila ya están tramados, como pasarían a una forma impresora de offset, por ejemplo.

![](http://tecnologiagrafica1.files.wordpress.com/2012/11/c3a1ngulos-de-trama.jpg)

Existen diferentes combinaciones, pero por lo general las tintas CMYK van en los siguientes ángulos:

*   <span style="line-height: 15px;">C - Cian: 15°</span>
*   M - Magenta: 75°
*   Y - Amarillo: 0°
*   K - Negro: 45°
![](http://tecnologiagrafica1.files.wordpress.com/2012/11/trama-de-puntos.jpg)



# Variables de la autotipía

En el caso de la autotipía tradicional (AM), hay tres variables que es importante identificar.

## Valor tonal

![](http://tecnologiagrafica1.files.wordpress.com/2012/11/variables-autotipc3ada-valor.jpg)

![](http://tecnologiagrafica1.files.wordpress.com/2012/11/am-screen-halftone.png)

Básicamente, es lo que hace que cierta zona del impreso se vea más oscura o más clara. Se mide en porcentaje (de 0% a 100%) y suele decidirse desde los programas de diseño.

## Ángulo de trama

![](http://tecnologiagrafica1.files.wordpress.com/2012/11/variables-autotipc3ada-c3a1ngulo.jpg)

Por lo general, varía entre las tramas de las diferentes tintas de un impreso, para evitar el famoso _efecto Moirè_.

## Lineatura de trama

![](http://tecnologiagrafica1.files.wordpress.com/2012/11/variables-autotipc3ada-lineatura.jpg)

Aquí arriba ^ tenemos un ejemplo con dos tramas que tienen un mismo valor tonal, mismo ángulo pero **diferente lineatura** de trama. **Cuidado!** Aunque los puntos sean más grandes, se trata del mismo valor tonal porque al estar más alejados entre sí, hay que agrandarlos para que sigan cubriendo el mismo porcentaje de superficie.

La **lineatura de trama** sirve para medir cuántos puntos entrar en cierto recorrido. Se mide en Lpi (_Lines per inch_ / Líneas por pulgada).

La trama tradicional está ordenada a través de una grilla imaginaria en forma de cuadrícula. Esa cuadrícula tiene líneas (horizontales y verticales). Lpi se refiere a la cantidad de dichas líneas, que pueden entrar en una pulgada.

En términos ideales y abstractos podemos decir que a una mayor lineatura de trama, la imagen tiene mayor definición (porque hay más puntos, de menor tamaño, en una pulgada). A lineatura más alta, puntos más pequeños, mayor y mejor definición. A lineatura más baja, puntos más grandes, menor y peor definición.
Esto es así en teoría, pero al tomar en cuenta el tipo de tinta, el tipo de impresión y sobre todo el soporte, no es tan sencillo. Por ejemplo: si se utiliza papel prensa, una lineatura cerrada no funcionará bien porque dicho soporte es altamente absorvente, los puntos de tinta se agrandarán por la capilaridad del papel y el valor tonal se incrementará, empastando la imagen. Para ese tipo de soportes, conviene utilizar una lineatura menor (más abierta).

