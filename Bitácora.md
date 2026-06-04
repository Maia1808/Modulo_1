08/04/2026: 
En esta clase vimos distintos tipos de antenas, principalmente el dipolo y la antena radial. Trabajamos con un dipolo al que le medimos una longitud total de 92 cm, lo que corresponde a media longitud de onda, y a partir de eso determinamos que operaba aproximadamente en 163 MHz. También medimos la separación entre el dipolo y el plano de tierra, que era de 13 cm.
Además, el profesor explicó la importancia de la adaptación de impedancia en la antena, remarcando que el conector debe estar en torno a los 50 ohms para evitar problemas en el funcionamiento del equipo.
Por otro lado, se mencionó la frecuencia de 1090 MHz, utilizada a nivel mundial, lo que nos dio un ejemplo concreto de aplicación real.
Hacia el final de la clase vimos un video introductorio sobre el uso del simulador MMANA-GAL, y también una demostración del NanoVNA, donde el profesor explicó cómo utilizarlo correctamente, haciendo énfasis en la calibración previa y en los cuidados necesarios para no dañarlo.

15/04/2026:
Comenzamos trabajando con el simulador MMANA-GAL, donde modelamos una antena triangular. Esto nos permitió practicar la carga de la geometría, analizar los parámetros principales y empezar a interpretar los diagramas de radiación (far field).
Luego realizamos una experiencia práctica utilizando el mástil donde se encuentra la bandera de la facultad para elevar el sistema y mejorar la recepción de señales. Al aumentar la altura, logramos captar señales de mayor alcance.
También utilizamos un batidor (detector de frecuencia) para identificar con mayor precisión la frecuencia de las señales que queríamos escuchar. Combinando la mayor altura con este instrumento, conseguimos sintonizar señales provenientes de lugares muy lejanos, como Chile y China.

29/04/2026:
En la clase de hoy estuvimos evaluando el modelo físico de la antena Moxon y terminamos de definir que este será el diseño definitivo para nuestro prototipo final. Aunque la antena Yagi ofrecía una ganancia teórica un poco mayor en las simulaciones, elegimos la Moxon porque es más compacta y resistente, lo que va a facilitar muchísimo su montaje sobre el soporte motorizado y el mástil giratorio sin sobrecargarlo.Además, dejamos calculadas las medidas preliminares para la estructura sintonizada en la banda de 2 metros ($145\text{ MHz}$). El próximo paso antes de armar los elementos definitivos de aluminio o alambre será validar completamente estos valores utilizando el NanoVNA.

20/04/2026:
Dividimos las tareas de la antena, nosotros hicimos un grupo para resolver el movimiento de los rotores que van a mover la antena, estos reciben los comandos de G-predict y se mueven segun esas instrucciones para orientar la antena. Primero tuvimos que hacer el circuito para hacer funcionar ambos motores paso a paso con sus respectivos drivers (pololus) , ademas tuvimos que abrir y resoldarle los pines a uno de los motores.

27/04/2026
Seguimos trabjando con los rotores, estuvimos trabjando en la comunicación de los motores para recibir las intrucciones y moverse correctamente. 
