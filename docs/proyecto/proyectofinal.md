---
hide:
    - toc
---

# Aerogenerador para el Soporte de Dispositivos de Bajo Consumo en Remotas

## ¿Qué hace?

El proyecto busca desarrollar un aerogenerador eficiente para bajas velocidades de viento, capaz de proporcionar energía sostenible y descentralizada para dispositivos de bajo consumo utilizados en zonas rurales y remotas. Esto permitirá prolongar la autonomía de equipos como estaciones meteorológicas, robots autónomos y sensores, disminuyendo la necesidad de conexión a la red.

## ¿Cómo llegaste a la idea?

La idea surgió a partir de experiencias en proyectos y tesis realizados en UTEC, donde se identificó la dificultad de mantener la operación continua de dispositivos en áreas remotas debido a la limitada autonomía de las baterías y las complicaciones asociadas con su recarga o sustitución.

## ¿Quién lo ha hecho de antemano? 

Existen investigaciones y proyectos previos sobre aerogeneradores de pequeño tamaño diseñados para bajas velocidades de viento, como los desarrollados por comunidades de energía renovable y fabricantes especializados en soluciones descentralizadas para entornos rurales. Sin embargo, este proyecto busca adaptar dichos conceptos a las condiciones específicas de Uruguay.

## ¿Qué diseñaste?
Se diseñó un prototipo de aerogenerador capaz de generar energía bajo velocidades de viento moderadas. Se están evaluando varios diseño de aerogeneradores tanto modelos de eje horizontal como vertical para determinar cuál es más eficiente en las condiciones climáticas locales.

## ¿Qué materiales y componentes se utilizaron?

El proyecto utilizó los siguientes materiales y componentes para su construcción:

__Materiales para fabricación__

- PLA (ácido poliláctico): Utilizado para la impresión 3D de las partes estructurales, palas de aerogenerador. engranes.

- TPU (poliuretano termoplástico): Usado para la fabricación de la correa de transmisión mediante impresión 3D.

__Componentes electrónicos__

- Microcontrolador ESP8266: Para el control y monitoreo del sistema.

- Sensor Hall: Para detectar las revoluciones del aerogenerador.

- 2 Imanes de neodimio (5x3 mm): Interactúan con el sensor Hall.

- Sensor de corriente ACS712: Para medir la potencia generada.

- 2 Motores DC de impresoras (12V): Funcionan como generadores de energía.

- 1 rodamiento 607 2RS.

## ¿Qué partes y sistemas se fabricaron?

Las partes y sistemas desarrollados y fabricadas son:

- Estructura: Fabricada en PLA mediante impresión 3D para soporte del aerogenerador.

- Aspas del aerogenerador: Diseñadas y fabricadas para capturar la energía eólica.

- Engranajes personalizados: Impresos en 3D para transmitir el movimiento mecánico.

- Correa de transmisión: Diseñada y fabricada en TPU mediante impresión 3D, para transferir el movimiento generado por las aspas.

- Caja para componentes electrónicos: Diseñada y fabricada en PLA para alojar y proteger los componentes electrónicos.

## ¿Qué procesos se utilizaron?

Procesos aditivos (fdm): Impresión 3D de prototipos Y de componentes.

## ¿Qué preguntas se respondieron?

- ¿Cuál es el diseño de aerogenerador más eficiente para bajas velocidades de viento?
Durante el proyecto, se evaluaron varias configuraciones para optimizar el rendimiento en condiciones de viento bajo. Se diseñaron aspas con perfiles aerodinámicos específicos. Además, se implementó un sistema de transmisión con engranajes impresos en 3D que maximizan la eficiencia energética al transmitir la rotación del rotor al generador. 


- ¿Es viable generar suficiente energía para dispositivos de bajo consumo en entornos rurales?

La viabilidad fue confirmada mediante las pruebas prácticas. Los motores DC utilizados como generadores, junto con la optimización del diseño, demostraron ser capaces de producir energía de 5V y el pico de corriente fué aproximado de 100 mA, dando una Potencia de 0.5W. suficiente para alimentar dispositivos de bajo consumo, como 5 luces LED. Por lo tanto, cargar completamente una bateria de 2000 mAh con esta corrinete 100 mA puede tomar entre 20 y 24 horas, dependiendo de las condiciones y la eficiencia del sistema. 

- ¿Qué materiales y configuraciones son más adecuados para estas condiciones específicas?

El uso de PLA para las partes estructurales y aspas permitió una construcción ligera, fácil de fabricar y adecuada para un prototipo funcional. La fabricación de la correa en TPU garantizó flexibilidad y durabilidad en la transmisión mecánica

## ¿Qué funcionó? ¿Qué no?

Funcionó la generación de energía en condiciones de viento moderado, así como la integración básica de los sistemas electrónicos.
No funcionó algunos diseños iniciales de aspas, no alcanzaron la eficiencia esperada.

## ¿Cuáles son las conclusiones?

El proyecto demuestra que es posible desarrollar una solución de energía renovable para dispositivos en zonas remotas. Sin embargo, se requiere optimizar el diseño de las aspas, investigar en otros generadores electricos y la resistencia de la estructura para mejorar la eficiencia y la durabilidad del sistema.

## ¿Cuáles son los pasos a seguir?

- Refinar el diseño del aerogenerador basado en los resultados iniciales.

- Probar materiales alternativos que aumenten la resistencia y reduzcan el peso.

- Integrar sistemas de almacenamiento de energía.

- Realizar pruebas de campo para evaluar el desempeño en condiciones reales.