---
bibliography: Bibliography.bib
csl: apa.csl
---

## SISTEMA DE GUIADO DE LASER USANDO VISION POR COMPUTADORA

EXPERIENCIA DEL INVESTIGADOR
-----
-Pasante de Investigación en la Universidad de Alberta, Canada. "Análisis numérico de modelos de circulación general oceánica de alta a muy alta resolución"

-Pasante como Analista de Datos en Ernst & Young.

SITUACION PROBLEMATICA
-----
Implementación de un sistema mecánico en el cañón de un tanque de guerra guiado por un marcador láser.

Reducir los costos en compra o fabricacion de cañones guiados, para los entrenamientos realizados por Ejercto del Peru. 

FORMULACION DEL PROBLEMA
-----
Al maniobrar un tanque de guerra se depende mucho del soldado a cargo del cañón, es decir que si el soldado despega los ojos del objetivo del blanco por cualquier causa ya sea un bache en la trayectoria o un mal movimiento dentro del vehículo, se podría perder al objetivo. Por ello la necesidad de diseñar e implementar un sistema de guiado.

Además de Proponer un modelo de entrenamiento simulado de bajo costo. 

JUSTIFICACION
-----
El desarrollo del problema se realizo en el caso más sencillo haciendo escalable el análisis. Se comenzó planteando una solución en el rango del espectro visible para el marcador láser. Posteriormente para el sistema mecánico sobre el tanque es representado por un brazo de impresión 3D y dos servos motores, la cámara web nos ayuda a resolver la posición del láser sobre nuestro objetivo dando nos nuestro blanco de tiro.

El algoritmo seguido muestra resultados sencillos de replicar. Un resultado de bajo costo gracias a que todo el trabajo es realizado por computadora permita reducir los gastos de fabricacion en prototipos.

OBJETIVOS GENERALES
-----
-Analizar las diferentes librerias y paqueterias de python en relacion a Vision Artificial.
    
-Formular una idea inicial escalable no solo de sistemas mecánicos guiados por marcador láser en los tanques de guerra. Implementar el sistema en aviones y barcos de guerra.

OBJETIVOS ESPECIFICOS
-----
-Diseño  de  una  arquitectura  de  procesamiento de imagenes para el reconocimiento de objetivos marcados por laser.
    
-Proponer un sistema mecánico guiado por marcador láser de bajo costo como en la modernización de tanques de guerra.

-El  algoritmo  implementado  será  multiplataforma,  por  lo  que  el  ejecutable podrá  ser  ejecutado  en  cualquier  sistema  operativo.

ALCANCE
-----
El presente trabajo como se expone es aplicable y viable.  

INTRODUCCION
-----

A finales del siglo XVI, los científicos europeos comenzaron a comprender la verdadera esencia del magnetismo.
William Gilbert demostró que la Tierra misma se comportaba como un imán, con propiedades similares a las de un
imán esférico que él mismo había fabricado. También se descubrió que el magnetismo se manifestaba en dos variantes,
conocidas como polos norte y sur, en referencia al magnetismo terrestre. De manera similar a la electricidad, los polos
idénticos se repelen entre sí, mientras que los diferentes se atraen. Sin embargo, a diferencia de la electricidad, los
polos magnéticos siempre parecen existir en pares, uno norte y otro sur. En una barra magnética, un extremo funciona
como polo norte y el otro como polo sur.

![William_Gilbert](https://github.com/M-O-R-P-H-E-U-S/Design-of-an-electromagnetic-accelerator/blob/main/William_Gilbert.jpg) ![Faraday](https://github.com/M-O-R-P-H-E-U-S/Design-of-an-electromagnetic-accelerator/blob/main/Faraday.jpg)

A principios del siglo XIX, se hizo un descubrimiento significativo que estableció una conexión profunda entre la
electricidad y el magnetismo. En Dinamarca, Hans Christian Oersted descubrió que una corriente eléctrica genera un
campo magnético a su alrededor, mientras que Faraday demostró que un campo magnético en constante cambio produce
flujo de corriente eléctrica. Estos hallazgos sentaron las bases para el desarrollo de la dinamo eléctrica y el generador,
dispositivos de gran importancia en la ingeniería moderna.

![Hans_Christian](https://github.com/M-O-R-P-H-E-U-S/Design-of-an-electromagnetic-accelerator/blob/main/Hans_Christian.jpg) ![Maxwell](https://github.com/M-O-R-P-H-E-U-S/Design-of-an-electromagnetic-accelerator/blob/main/Maxwell.jpg)

El paso crucial se dio en la década de 1850, cuando Maxwell unificó la electricidad y el magnetismo en su teoría del
electromagnetismo, que fue la primera teoría de un campo unificado. Esta teoría siguió siendo válida con éxito después
de incorporar las sutilezas necesarias para tener en cuenta los efectos cuánticos.

METODOLOGIA
-----

Sistema Mecanico
-----

Para el diseño del sistema mecánico se uso una placa de arduino UNO, dos servo motores y para armar el pan tilt que conformaron los servo motores.





Vision por Computadora
-----

Para marcar el objetivo se utilizo un láser de color verde. La solución planteada para nuestra problemática es resuelta
en rango del espectro visible. Los materiales usados se listan a continuación: una cámara asus, un
tanque realizado en el software Fusion 360 y una mira láser que sera usado como marcador.




Para el desarrollo del algoritmo realizado en python debe entenderse que ante los ojos humanos el sistema de medición
es el metro, pero ante los ojos de la computadora que este caso seria la cámara el sistema de medición es el píxel. Es
decir mediante una traslación y rotación de ejes logramos transformar el sistema coordenado de la posición del marcador
láser al sistema coordenado de la cámara. Una vez realizado esta transformación se logra identificar la posición del
objetivo según las coordenadas desde la cámara.


![mov](https://github.com/M-O-R-P-H-E-U-S/Design-of-an-electromagnetic-accelerator/blob/main/mov.jpeg)




![web](https://github.com/M-O-R-P-H-E-U-S/Design-of-an-electromagnetic-accelerator/blob/main/web.jpeg)




![varilla_acero](https://github.com/M-O-R-P-H-E-U-S/Design-of-an-electromagnetic-accelerator/blob/main/varilla_acero.jpeg)






PRESUPUESTO
-----

| CONCEPTO DE PPTO                                         |     FASE      |   TOTAL      |
| -------------                                            | ------------- |------------- |
|SISTEMA DE GUIADO DE LASER USANDO VISION POR COMPUTADORA  |    1RA FASE   |   S/.310     |

FUENTES DE FINANCIAMIENTO
-----

|             |                     CANTIDAD TOTAL                       | UNIDAD DE MEDIDA | PRECIO UNITARIO | PRECIO TOTAL |
| ----------  | -------------------------------------------------------- |----------------- |-----------------|--------------|
|LASER DIODO  |                           01                             |        UND       |     S/.40       |    S/.40     |
|CAMARA WEB   |                           01                             |        UND       |     S/.120      |    S/.120    |
|IMPRESION 3D |                           01                             |        UND       |     S/.70       |    S/.70     |
|SERVO MOTOR  |                           02                             |        UND       |     S/.15       |    S/.30     |
| ARDUINO UNO |                           01                             |        UND       |     S/.50       |    S/.50     |
| ----------  | -------------------------------------------------------- |----------------- |-----------------|--------------|
|    TOTAL    |                           06                             |                  |                 |    S/.310    |


![CRONOGRAMA](https://github.com/M-O-R-P-H-E-U-S/Design-of-an-electromagnetic-accelerator/blob/main/CRONOGRAMA.jpg)

RESULTADOS
-----

Se logro seguir el objetivo usando el marcador láser usando visión por computadora. Ademas se simulo el comportamiento
de las varaibles entorno al recorrido que sigue el misil disparado desde el cañon, con una velocidad de salida de 350m/s
y con un total de 350 iteraciones

![grafica](https://github.com/M-O-R-P-H-E-U-S/Design-of-an-electromagnetic-accelerator/blob/main/grafica.jpeg)

![velocidad](https://github.com/M-O-R-P-H-E-U-S/Design-of-an-electromagnetic-accelerator/blob/main/velocidad.jpeg)

![fuerza](https://github.com/M-O-R-P-H-E-U-S/Design-of-an-electromagnetic-accelerator/blob/main/fuerza.jpeg)

![turbulencia](https://github.com/M-O-R-P-H-E-U-S/Design-of-an-electromagnetic-accelerator/blob/main/turbulencia.jpeg)


CONCLUSIONES
-----

* Es posible contar con un software de bajo costo para el registro de disparos simulados en un bullet de tiro.

* Es posible encontrar aplicaciones de Vision Artificial en el campo militar.

* Es posible modernizar los tanques de guerra del Perú. El trabajo presente propone la idea base para tener un sistema
de guiado láser. Obteniendo una superioridad armamentaria en el campo de guerra.







