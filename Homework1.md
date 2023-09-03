# Study Guide: Chapter 1 - Computer Networks: A Systems Approach

## Introduction
Welcome to the study guide for Chapter 1 of the textbook "Computer Networks: A Systems Approach" by Larry Peterson and Bruce Davie. This guide will help you understand the fundamental concepts of computer networks and provide you with questions and exercises to reinforce your understanding. Let's get started!

### Required reading
Sections: 1.1, 1.2, 1.3 and 1.5 

## 1. Building a Scalable Network
- What are the key considerations when building a scalable network?

    Al construir una red escalable, se deben tener en cuenta varias consideraciones clave. Estas consideraciones incluyen:

    Arquitectura de red: diseñar una red escalable requiere una arquitectura bien pensada que pueda adaptarse al crecimiento y la expansión futuros. Esto implica considerar factores como la topología de la red, los protocolos de enrutamiento y la segmentación de la red.

    Ancho de banda: Un ancho de banda suficiente es crucial para una red escalable. Es importante evaluar los requisitos de ancho de banda actuales y futuros de la red y garantizar que la infraestructura de la red pueda manejar el volumen de tráfico esperado.

    Redundancia: incorporar redundancia en la red es esencial para garantizar una alta disponibilidad y minimizar el tiempo de inactividad. Esto se puede lograr mediante enlaces de red redundantes, componentes de hardware redundantes e implementación de mecanismos de conmutación por error.

    Seguridad: implementar medidas de seguridad sólidas es crucial para proteger la red de posibles amenazas. Esto incluye el uso de firewalls, sistemas de detección de intrusiones y protocolos de cifrado para salvaguardar el tráfico y los datos de la red.

    Monitoreo y administración de redes: contar con herramientas efectivas de monitoreo y administración de redes es esencial para identificar y resolver problemas con prontitud. Esto incluye monitorear el rendimiento de la red, analizar patrones de tráfico y administrar de manera proactiva los recursos de la red.

    Crecimiento futuro: anticipar el crecimiento futuro y planificar la escalabilidad es vital. Esto implica considerar factores como la cantidad de usuarios, dispositivos y aplicaciones que la red deberá admitir en el futuro

- Explain the concept of network scalability and why it is important.

    La escalabilidad de la red se refiere a la capacidad de una red informática para acomodar un número cada vez mayor de usuarios, dispositivos y tráfico de datos sin experimentar una disminución significativa en el rendimiento o la funcionalidad. Es importante al construir una red informática desde cero porque permite que la red crezca y se adapte a las necesidades cambiantes de una organización o empresa.

    Al construir una red informática desde cero, es fundamental considerar la escalabilidad para garantizar que la red pueda soportar el crecimiento y la expansión futuros. Sin escalabilidad, la red puede sobrecargarse y ser incapaz de manejar las crecientes demandas que se le imponen. Esto puede provocar un rendimiento lento, congestión de la red e incluso fallas en la red.

    La escalabilidad también permite flexibilidad para agregar nuevos dispositivos, aplicaciones y servicios a la red. Permite que la red se adapte fácilmente a nuevos usuarios y dispositivos sin requerir cambios significativos o interrupciones en la infraestructura existente. Esto es particularmente importante en el panorama tecnológico actual en rápida evolución, donde constantemente se introducen nuevos dispositivos y tecnologías.

    En resumen, la escalabilidad de la red es importante al construir una red informática desde cero porque garantiza que la red pueda soportar el crecimiento futuro, adaptarse a las necesidades cambiantes y proporcionar un rendimiento y una funcionalidad óptimos.

- Provide examples of different applications that require a scalable network.

    Algunos ejemplos de aplicaciones que requieren una red escalable incluyen:

    Computación en la nube: los proveedores de servicios en la nube necesitan una infraestructura de red escalable para manejar la creciente demanda de almacenamiento, potencia de procesamiento y transferencia de datos.

    Plataformas de comercio electrónico: los sitios web de compras en línea experimentan un alto tráfico durante las horas pico, como días festivos o eventos de ventas. Es necesaria una red escalable para manejar el mayor número de usuarios y transacciones.

    Plataformas de redes sociales: los sitios de redes sociales como Facebook, Twitter e Instagram tienen millones de usuarios activos que generan y consumen grandes cantidades de datos. Una red escalable es esencial para manejar el flujo constante de información.

    Servicios de transmisión de video: plataformas como Netflix, YouTube y Hulu requieren una red escalable para entregar contenido de video de alta calidad a una gran cantidad de usuarios simultáneamente.

    Juegos en línea: los juegos en línea multijugador requieren una red escalable para admitir la comunicación y la interacción en tiempo real entre los jugadores.

    Análisis de big data: las aplicaciones que procesan y analizan cantidades masivas de datos, como la minería de datos, el aprendizaje automático y la inteligencia artificial, requieren una red escalable para manejar los requisitos computacionales y de almacenamiento.

    Internet de las cosas (IoT): los dispositivos de IoT, como los dispositivos domésticos inteligentes, los dispositivos portátiles y los sensores industriales, generan una gran cantidad de datos que deben transmitirse y procesarse. Es necesaria una red escalable para manejar el creciente número de dispositivos conectados.

## - Why does a network need to be cost-effective, fair, and have robust connectivity?

    Rentabilidad: una red rentable garantiza que se optimicen los recursos y la infraestructura necesarios para establecer y mantener la red. Esto incluye minimizar los gastos asociados con hardware, software, mantenimiento y costos operativos. Al ser rentable, una red puede proporcionar servicios y conectividad a un precio asequible, haciéndola accesible a una gama más amplia de usuarios.

    Equidad: La equidad en una red se refiere a la distribución equitativa de los recursos de la red entre los usuarios. Garantiza que todos los usuarios tengan igualdad de oportunidades para acceder y utilizar los servicios de red sin discriminación ni prejuicios. La equidad evita que un solo usuario o grupo monopolice los recursos de la red, lo que genera un entorno de red más equilibrado e inclusivo.

    Conectividad sólida: una conectividad sólida es crucial para que una red garantice una comunicación confiable e ininterrumpida. Una red con una conectividad sólida puede manejar grandes volúmenes de tráfico, proporcionar baja latencia y mantener un rendimiento constante incluso durante los períodos de uso pico. Minimiza el tiempo de inactividad, la pérdida de paquetes y otras interrupciones, mejorando así la experiencia del usuario y la productividad.
    
## - Discuss the challenges involved in designing a network that can support various applications.

    Requisitos de ancho de banda: diferentes aplicaciones tienen diferentes requisitos de ancho de banda. Algunas aplicaciones, como la transmisión de vídeo o los juegos en línea, requieren un gran ancho de banda para funcionar correctamente. Diseñar una red que pueda asignar suficiente ancho de banda a cada aplicación puede ser un desafío.

    Calidad de servicio (QoS): ciertas aplicaciones, como las conferencias de voz o video, requieren baja latencia y alta prioridad para garantizar una experiencia de usuario fluida. Diseñar una red que pueda priorizar el tráfico y proporcionar la QoS necesaria para diferentes aplicaciones puede resultar complejo.

    Escalabilidad: a medida que aumenta la cantidad de aplicaciones y usuarios en la red, la red debería poder escalar en consecuencia. Diseñar una red que pueda manejar las crecientes demandas de diversas aplicaciones sin comprometer el rendimiento o la estabilidad puede ser un desafío.

    Seguridad: diferentes aplicaciones pueden tener diferentes requisitos de seguridad. Diseñar una red que pueda proporcionar las medidas de seguridad necesarias, como firewalls, sistemas de detección de intrusos o cifrado, para cada aplicación puede ser una tarea compleja.

    Compatibilidad: varias aplicaciones pueden tener diferentes protocolos o requisitos de comunicación. Diseñar una red que pueda admitir diferentes protocolos y garantizar la compatibilidad entre aplicaciones puede resultar un desafío.


## 2. Computer Network Architecture
- Define computer network architecture in terms of layers and protocols

    La arquitectura de una red informática se refiere al diseño y la estructura de una red informática. Implica la organización de la red en diferentes capas, cada una de las cuales proporciona un nivel de servicio específico. La estratificación ayuda a gestionar la complejidad de la red y permite el diseño y la implementación modulares, Los estándares para cada capa pueden desarrollarse de manera independiente debido a que cada una de las capas está delimitada con independencia de las otras, los cambios realizados en las normas de una de ellas no influyen en los procesos que se están desarrollando en las otras capas, lo que facilita la introducción de nuevas normas.

    Los protocolos son una parte esencial de la arquitectura de red. Definen las reglas y formatos de comunicación entre los diferentes componentes de la red. Cada capa de la arquitectura de red tiene su propio conjunto de protocolos que proporcionan servicios a capas superiores y utilizan servicios de capas inferiores.

    Las arquitecturas de red más referenciadas son el modelo OSI (Open Systems Interconnection) y la arquitectura de Internet. El modelo OSI consta de siete capas, cada una responsable de un aspecto específico de la comunicación de la red. La arquitectura de Internet, por otro lado, sigue una pila más simple, con capas como protocolos de red, Protocolo de Internet (IP), Protocolo de control de transmisión (TCP), Protocolo de datagramas de usuario (UDP) y protocolos de aplicación como HTTP, FTP, Telnet. y SMTP.

- Why are layers and protocols important?

    Las capas y los protocolos son importantes en la arquitectura de redes informáticas por varias razones:

    Descomposición del problema: la estratificación permite dividir la compleja tarea de construir una red en componentes más pequeños y manejables. Cada capa se centra en resolver una parte específica del problema, lo que hace que el diseño general sea más modular y más fácil de entender.

    Abstracción: las capas proporcionan una forma de abstraer la complejidad del hardware subyacente y la topología de la red. Cada capa se basa en los servicios proporcionados por las capas inferiores, proporcionando un mayor nivel de abstracción a las capas superiores. Esto permite que las aplicaciones y los protocolos interactúen con la red sin necesidad de comprender los detalles de la infraestructura subyacente.

    Modularidad: la estratificación promueve la modularidad en el diseño de redes. Si es necesario agregar un nuevo servicio o funcionalidad, a menudo se puede hacer modificando o agregando funcionalidad en una capa específica, sin afectar las otras capas. Esto facilita la actualización y ampliación de la arquitectura de red a medida que surgen nuevas tecnologías y requisitos.

    Interoperabilidad: los protocolos definen las reglas y formatos de comunicación entre diferentes componentes de la red. Al adherirse a un conjunto común de protocolos, diferentes dispositivos y sistemas pueden comunicarse e interoperar entre sí, independientemente de sus implementaciones específicas. Esto promueve la compatibilidad y permite el desarrollo de una amplia gama de aplicaciones y servicios que pueden funcionar juntos sin problemas.

- What is encapsulation, multiplexing and demultiplexing?

    La encapsulación, multiplexación y demultiplexación son conceptos importantes en la arquitectura de redes informáticas.

    La encapsulación se refiere al proceso de agregar encabezados (header) o avances a un mensaje en cada capa de la pila de protocolos a medida que viaja desde el origen hasta el destino. Cada capa agrega su propio encabezado (header) o avance al mensaje, que contiene información de control específica de esa capa. Esto permite que el mensaje sea manejado e interpretado adecuadamente por la capa correspondiente en el destino. Los encabezados (header) o trailers son como sobres que contienen el mensaje y la información necesaria para su entrega.

    La multiplexación es la técnica de combinar múltiples flujos de datos en un solo flujo para su transmisión a través de un medio o enlace compartido. En el contexto de las redes informáticas, la multiplexación permite que múltiples aplicaciones o protocolos compartan la misma conexión de red. A cada flujo de datos se le asigna un identificador único, conocido como clave de multiplexación o clave demux, que se incluye en el encabezado del mensaje. El extremo receptor utiliza esta clave para demultiplexar los mensajes entrantes y entregarlos a la aplicación o protocolo apropiado.

    La demultiplexación es el proceso inverso a la multiplexación. Implica extraer los flujos de datos individuales de un flujo multiplexado en el extremo receptor. La clave demultiplexación en el encabezado del mensaje se utiliza para determinar la aplicación o protocolo de destino para cada flujo de datos. El proceso de demultiplexación garantiza que cada flujo de datos se entregue correctamente a su destinatario previsto.

- Discuss the role of each layer in the OSI and Internet protocol stack.

    En el modelo OSI, cada capa tiene un rol específico:

    Capa física (Physical Layer): esta capa es responsable de la transmisión de bits sin procesar a través de un enlace de comunicación.

    Capa de enlace de datos (Data Link Layer): la capa de enlace de datos recopila un flujo de bits en agregados más grandes llamados marcos. Maneja el encuadre, la detección de errores y el control de flujo.

    Capa de red (Network Layer): la capa de red maneja el enrutamiento entre nodos dentro de una red de conmutación de paquetes. Se ocupa del direccionamiento lógico y el enrutamiento de paquetes.

    Capa de transporte (Transport Layer): la capa de transporte proporciona comunicación de un extremo a otro entre procesos en diferentes hosts. Garantiza la entrega fiable y ordenada de mensajes.

    Capa de sesión (Session Layer): la capa de sesión gestiona las sesiones de comunicación entre aplicaciones. Establece, mantiene y finaliza conexiones entre aplicaciones.

    Capa de presentación (Presentation Layer): la capa de presentación se ocupa del formato de los datos intercambiados entre pares. Maneja el cifrado, compresión y conversión de datos.

    Capa de aplicación (Application Layer): la capa de aplicación proporciona servicios directamente a las aplicaciones del usuario final. Incluye protocolos como HTTP, FTP, Telnet y SMTP.

- Provide examples of protocols used at each layer of the TCP/IP protocol stack.

    Capa de interfaz de red (también conocida como capa de enlace): - Ethernet - Wi-Fi (802.11) - Protocolo punto a punto (PPP)

    Capa de Internet: - Protocolo de Internet (IP) - Protocolo de mensajes de control de Internet (ICMP) - Protocolo de resolución de direcciones (ARP)

    Capa de transporte: - Protocolo de control de transmisión (TCP) - Protocolo de datagramas de usuario (UDP)

    Capa de aplicación: - Protocolo de transferencia de hipertexto (HTTP) - Protocolo de transferencia de archivos (FTP) - Protocolo simple de transferencia de correo (SMTP) - Sistema de nombres de dominio (DNS)

## 3. Performance
- Why is important to keep track of the performance of a network?
- What are the main metrics we use to measure network performance?
- Give some examples of the challenges of using different metrics in high speed networks


## Exercises
1. Calculate the total time required to transfer a 1000-KB file in the following cases, assuming an RTT of 50 ms, a packet size of 1 KB data, and an initial 2 × RTT of “handshaking” before data is sent:

    a. The bandwidth is 1.5 Mbps, and data packets can be sent continuously.

    b. The bandwidth is 1.5 Mbps, but after we finish sending each data packet we must wait one RTT before sending the next.
    
    c. The bandwidth is “infinite,” meaning that we take transmit time to be zero, and up to 20 packets can be sent per RTT.
    
    d. The bandwidth is infinite, and during the first RTT we cansend one packet ($2^{1−1}$), during the second RTT we can send two packets ($2^{2−1}$), during the third we can send four ($2^{3−1}$), and so on
    
2. For each of the following operations on a remote file server, discuss whether they are more likely to be delay sensitive or bandwidth sensitive:

    a. Open a file.

    b. Read the contents of a file.
    
    c. List the contents of a directory.
    
    d. Display the attributes of a file.
    
3. Suppose a host has a 1-MB file that is to be sent to another host. The file takes 1 second of CPU time to compress 50% or 2 seconds to compress 60%.

    a. Calculate the bandwidth at which each compression option takes the same total compression + transmission time.
    
    b. Explain why latency does not affect your answer

4. . Discuss the relative performance needs of the following applications in terms of average bandwidth, peak bandwidth, latency, jitter, and loss tolerance:
    
    a. File server.
    
    b. Print server.
    
    c. Digital library.
    
    d. Routine monitoring of remote weather instruments.
    
    e. Voice.
    
    f. Video monitoring of a waiting room.
    
    g. Television broadcasting.


```python

```
