---------------------------------------------
# ESPECIFICACIONES PARA ENTREGA DE MATERIAL #
---------------------------------------------

¡Hola! Una buena organización nos ayuda a tod@s para que 
el flujo de trabajo sea más ágil, asegurarnos que 
estamos hablando el mismo idioma y, por supuesto, 
lograr que material llegue con su máxima calidad al studio :stuck_out_tongue:

Por si no lo sabías, la primera etapa para hacer el color de 
tu pieza es el conformado: ese momento en que la creación 
audiovisual cambia su cascarón de edición para 
insertarse en uno nuevo llamado DaVinci Resolve.  

Para esto es fundamental la correcta recepción de 
archivos para evitar problemitas de comunicación 
entre las máquinas implicadas. 

A continuación te detallo los requerimientos & algunas recomendaciones: 


## ¿QUÉ? ##
Para ponernos manos a la obra con la pieza, 
necesito que recolectes los siguientes archivos :

+ Archivo .XML del timeline en cuestión. [^1]
+ Archivo .EDL del timeline en cuestión. [^1]
+ Render de un clip de referencia del timeline en media-alta calidad. [^1][^2]
+ Copia de TODO el material de rodaje utlizado dentro del timeline en cuestión. [^3][^4]
+ Copia de otros materiales utilizados en el montaje como grafismos, imágenes de archivo u otros. [^4]
+ Un archivo de texto .TXT ó .DOC o un screenshot donde se especifique los siguientes settings del proyecto: [^1]
	+ Resolución final de la pieza audiovisual.
	+ FPS del proyecto.
	+ La duración desde el punto de inicio de la secuencia hasta el ultimo clip utilizado.

[^1]: *Sugerencia: Especificar en el nombre del archivo la fecha en que se renderizo ó número de versión por si ocurren modificaciones en el montaje*
[^2]: *Sugerencia: Codec: ProRes 422 LT; Formato: .MOV ; Resolución: HD (1920x1080) ó la homologa del aspect ratio que utilices.*
[^3]: a.k.a. Brutos de cámara
[^4]: *Sugerencia: Todo el material de rodaje y archivo con sus respectivos nombres de archivo coherentes durante todo el proyecto*


## ¿CÓMO? ##
La mayoría de estos archivos los puedes exportar desde
tu software de edición y la forma de hacerlo puede variar
dependiendo del fabricante.

***Si el timeline viene de un programa DISTINTO a DaVinci Resolve, POR FAVOR CONSIDERA QUE:*** \
Muchos fx's de edición como podrían ser máscaras, rampas de velocidad, las mismas Nested Sequences de Premiere, o incluso algunas transiciones no comunes podrían ser codificados de manera errónea en Resolve. [^5]

***Si el timeline viene de DaVinci Resolve y tiene algún fx de lo mencionado anteriormente:*** \
Debes enviarme el proyecto de DaVinci. Exportarlo es muy sencillo: le das a File < Export Project y guardas el archivo DRP donde más te convenga. Luego, además de enviarme el .XML y .EDL correspondiente, me haces llegar ese archivo .DRP que contendrá el proyecto.
	
	
[^5]: Si insertaste algo de lo que descrito anteriormente entonces, cuando recolectes esos brutos, no los entregues directamente sino que haz un render de ese tramo del fx en la máxima calidad posible respecto al material de rodaje. Este render es el nuevo material para esa parte de la línea de tiempo: traspasalo al timeline en el sitio correspondiente y este último timeline con sus materiales contenidos son lo que debes hacer llegar. ¿Tienes dudas sobre si este es tu caso o no sabes en qué codec renderizar para asegurar la mayor calidad? No dudes en escribirme :-)

****************************

<ins>Recomendaciones para preparar el timeline para exportación:</ins>
* Si la forma en que está montado el proyecto lo permite: intenta colocar 
todos los clips en el track 1 de tu timeline. De esta forma, los archivos
xml/edl quedan más limpios y se evitan confusiones con la longitud de 
cada clip facilitando la corrección de color.

* Si tienes clips con fx como los que mencione antes, es preferible que
los dejes aislados en un track exclusivo para visualizar su sitio rápidamente
y al momento de traspasar los nuevos renders se haga más fácil. 


<ins>Recomendaciones para ordenar el proyecto para exportación:</ins>
* Si estás trabajando en Premiere y tienes mucho caos 
en tu proyecto [a.k.a. material desordenado, demasiados timelines-versiones, 
mucho material que no pinta nada ahi o cualquiera de estas cositas] 
{been there, done that}: 
	* Algo muy útil para organizarte 
es hacer una copia limpia del proyecto solo con los materiales que se 
están utilizando, y borrarte las demás timelines que no son las definitivas.
Esto se logra fácilmente a través de la función Project Manager dentro del programa. \
[En este vídeo](https://www.youtube.com/watch?v=aiD4uqS0cNI) lo explican bien.  

****************************

Ahora que les tienes recolectados, organizalos en carpetas.
**No** es un requerimiento tener los archivos de una forma concreta,
pero te sugiero esta nomenclatura:

<table>
    <tbody>
        <tr>
            <td colspan=9 style="text-align: center; vertical-align: middle;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CARPETA MASTER CON EL NOMBRE DEL PROYECTO</td>
        </tr>
        <tr>
            <td colspan=5>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Material</td>
            <td rowspan=5>Referencia</td>
            <td rowspan=5>.XML</td>
            <td rowspan=5>.EDL</td>
            <td rowspan=5>.TXT / .DOC / Screenshot</td>
        </tr>
	<tr>
            <td>Footage</td>
	    <td>Imgs</td>
	    <td>Graphics</td>
            <td>Audio</td>
            <td>Otros</td>
        </tr>
    </tbody>
</table>

## ¿DÓNDE? ##
Con las carpetas hechas y los archivos correctamente nombrados, es hora
del traspaso oficial. Esto va a depender de lo que hayamos acordado
previamente.

- Si estamos en la misma ciudad o cerca, puedes venir a dejar un disco
duro con los archivos directamente al studio o en quedar en algún lugar 
a convenir. Coordinemos a través del mail en el cual te envíe este enlace. 

- Si estamos trabajando por remoto, en el mail que te envíe este enlace,
te especifique el link de la carpeta de Frame.io o Drive correspondiente
a tu proyecto para que puedas subir los archivos.


## ¿CUÁNDO? ##
Apenas tengas un corte cercano a lo que será la pieza final, es un buen
momento para comenzar a trabajar en ello.

De todas maneras, nuevamente, esto va a depender de los tiempos y
deadlines que hayamos acordado previamente.
