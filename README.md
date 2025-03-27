# STM32 Firmware Course

Welcome to the STM32 Firmware Course repository! This repository is designed to provide a comprehensive learning experience for anyone interested in developing firmware for STM32 microcontrollers. Whether you're a beginner or an experienced developer, this course will guide you through the essentials of embedded systems programming using STM32 devices.

## Course Overview

The STM32 Firmware Course covers a wide range of topics, including:

# Módulo 1: Configuración del Entorno y Fundamentos de Programación

1. **Instalación y configuración de STM32CubeIDE**
   - Descarga e instalación de STM32CubeIDE
   - Configuración inicial y creación de proyectos
   - Navegación por la interfaz de usuario
   - Compilación y depuración en STM32CubeIDE

2. **Introducción a C para sistemas embebidos**
   - Sintaxis básica de C
   - Diferencias entre C y otros lenguajes (Python, Java)
   - Uso de compiladores y entornos de desarrollo

3. **Configuración de proyectos con CMake y Makefiles**
   - Estructura de un proyecto con CMake
   - Creación de Makefiles para proyectos embebidos
   - Configuración de directorios y variables

4. **Uso de toolchains y compiladores cruzados**
   - Configuración de toolchains para arquitectura ARM
   - Uso de compiladores cruzados en STM32
   - Optimización de código para sistemas embebidos

5. **Debugging en sistemas embebidos con OpenOCD y GDB**
   - Instalación y configuración de OpenOCD
   - Uso de GDB para depuración remota
   - Monitoreo de variables y control de ejecución

6. **Tipos de bibliotecas en sistemas embebidos (estáticas vs. dinámicas)**
   - Diferencias entre bibliotecas estáticas y dinámicas
   - Ventajas y desventajas de cada tipo
   - Uso de bibliotecas en proyectos embebidos

7. **Desarrollo modular y reutilización de código**
   - Conceptos de modularidad y separación de responsabilidades
   - Técnicas para reutilizar código en sistemas embebidos
   - Creación de bibliotecas y control de versiones

8. **Uso de HAL (Hardware Abstraction Layer) y CMSIS**
   - Introducción a HAL y su propósito
   - Uso de CMSIS para configuraciones a nivel de microcontrolador
   - Abstracción de hardware para facilitar el desarrollo

9. **Programación defensiva en sistemas críticos**
   - Estrategias para prevenir errores en sistemas embebidos
   - Manejo de condiciones excepcionales
   - Validación de datos y protección contra fallos

# Módulo 2: Fundamentos de Programación

10. **Variables y Tipos de Datos**
    - Tipos de datos básicos en C: enteros, flotantes, caracteres, booleanos
    - Declaración, inicialización y alcance de variables
    - Constantes y literales
    - Uso de punteros y direcciones de memoria

11. **Estructuras y Uniones**
    - Definición y uso de estructuras en C
    - Acceso a miembros de estructuras
    - Uniones: diferencias con las estructuras y casos de uso

12. **Arreglos y Cadenas**
    - Arreglos estáticos y dinámicos
    - Cadenas de caracteres y manipulación
    - Punteros a arreglos y paso por referencia

13. **Control de Flujo y Bucles**
    - Estructuras de control: if, else, switch
    - Bucles: for, while, do-while
    - Uso de break y continue

14. **Funciones y Paso de Parámetros**
    - Declaración y definición de funciones
    - Paso de parámetros por valor y por referencia
    - Funciones recursivas

15. **Manejo de Errores y Excepciones**
    - Técnicas de manejo de errores en C
    - Uso de flags, códigos de error, y excepciones (en entornos que lo soporten)

# Módulo 3: Programación Orientada a Objetos (POO)

16. **Fundamentos de POO en C/C++**
    - Introducción a clases y objetos
    - Definición de clases y objetos en C++
    - Métodos y atributos de clases

17. **Encapsulamiento y Abstracción**
    - Acceso a miembros de una clase: public, private, protected
    - Encapsulamiento y ocultación de datos
    - Abstracción y diseño orientado a objetos

18. **Herencia y Polimorfismo**
    - Concepto de herencia en C++
    - Herencia simple y múltiple
    - Polimorfismo: sobrecarga y sobrescritura de métodos
    - Uso de punteros a clases base y clases derivadas

19. **Constructores y Destructores**
    - Definición y uso de constructores y destructores en C++
    - Constructor por defecto, constructor de copia y constructor de movimiento
    - Destrucción de objetos y liberación de recursos

20. **Sobrecarga de Operadores y Funciones Amigas**
    - Sobrecarga de operadores en C++
    - Funciones amigas para acceder a miembros privados

# Módulo 4: Hardware y Arquitectura del Microcontrolador

21. **Arquitectura de microcontroladores STM32 (Cortex-M)**
    - Descripción de la arquitectura ARM Cortex-M
    - Comparativa con otras arquitecturas de microcontroladores
    - Memoria y registros en microcontroladores STM32

22. **Modelo de ejecución Harvard vs. Von Neumann**
    - Diferencias entre los modelos Harvard y Von Neumann
    - Impacto en el diseño de sistemas embebidos
    - Uso en la arquitectura de microcontroladores STM32

23. **Modos de operación y estados de bajo consumo**
    - Modos de operación en STM32: run, sleep, stop, standby
    - Estrategias para optimizar el consumo de energía
    - Gestión dinámica de energía en sistemas embebidos

24. **Relojes y osciladores internos/externos en STM32**
    - Configuración de relojes internos y externos
    - Uso de osciladores y PLLs en STM32
    - Estrategias para optimizar el uso del reloj

25. **Configuración y uso de PLL (Phase-Locked Loop)**
    - Teoría básica sobre PLL
    - Configuración de PLL en STM32
    - Ejemplos de uso de PLL para sincronización y frecuencias

26. **Manejo de energía y optimización de consumo**
    - Técnicas de optimización de consumo en sistemas embebidos
    - Uso de modos de bajo consumo en STM32
    - Estrategias para la reducción de consumo en microcontroladores

27. **Protección contra ruido electromagnético y EMI**
    - Fuentes comunes de EMI en sistemas embebidos
    - Técnicas de blindaje y filtrado de señales
    - Diseño para mitigar el ruido electromagnético

28. **Acceso a registros y manipulación de hardware desde C**
    - Uso de registros de bajo nivel para controlar hardware
    - Acceso directo a puertos y periféricos
    - Uso de la directiva volatile para manipulación segura de registros

# Módulo 5: Memoria y Administración de Recursos

29. **Tipos de memoria en microcontroladores (Flash, SRAM, EEPROM, etc.)**
    - Características de diferentes tipos de memoria
    - Uso de cada tipo de memoria en sistemas embebidos
    - Acceso y optimización de la memoria Flash y SRAM

30. **Administración de memoria en C para sistemas embebidos**
    - Asignación y liberación de memoria dinámica
    - Técnicas de gestión eficiente de memoria
    - Prevención de desbordamientos y fugas de memoria

31. **Memoria stack y heap: diferencias y manejo eficiente**
    - Diferencias entre stack y heap en sistemas embebidos
    - Gestión de memoria en entornos restringidos
    - Técnicas para optimizar el uso de stack y heap

32. **Acceso directo a memoria (DMA) y su uso en STM32**
    - Conceptos básicos de DMA (Direct Memory Access)
    - Configuración de DMA en STM32
    - Casos de uso de DMA para transferencias eficientes

33. **Implementación de archivos en sistemas embebidos (FatFs, LittleFS)**
    - Sistemas de archivos para microcontroladores
    - Uso de FatFs y LittleFS en sistemas embebidos
    - Integración con almacenamiento externo (tarjetas SD)

34. **Protección de memoria y seguridad en firmware**
    - Técnicas de protección de memoria en sistemas embebidos
    - Seguridad en firmware embebido
    - Prevención de vulnerabilidades en código embebido

35. **Uso de memoria externa (SDRAM, FRAM, Flash externa)**
    - Configuración y uso de memoria externa
    - Diferencias entre SRAM, FRAM, y Flash externa
    - Técnicas de acceso y optimización de memoria externa

# Módulo 6: Periféricos y Timers

36. **Configuración y uso de GPIO (Entrada, salida, pull-up/pull-down)**
    - Configuración de pines GPIO en STM32
    - Uso de pines para entradas y salidas digitales
    - Implementación de resistencias pull-up y pull-down
    - Interrupciones externas y manejo de señales digitales

37. **Uso avanzado de ADC y DAC**
    - Configuración y uso de convertidores analógico-digitales (ADC)
    - Características de DAC y su uso para señal analógica
    - Ejemplos de aplicaciones: medición de sensores, generación de señales de salida

38. **Uso de timers básicos y avanzados**
    - Configuración básica de timers en STM32
    - Programación de timers para retrasos, eventos periódicos, y generación de PWM
    - Configuración avanzada de timers para capturar y comparar eventos

39. **Generación de PWM y control de servomotores**
    - Concepto de PWM (Pulse Width Modulation)
    - Generación de señales PWM usando timers
    - Control de servomotores y su implementación con PWM

40. **Medición de frecuencia y captura de señales con timers**
    - Uso de timers para medir frecuencia de señales externas
    - Captura de eventos con timers y su procesamiento
    - Implementación de un medidor de frecuencia con microcontroladores STM32

41. **Uso de interrupciones y manejo de eventos en STM32**
    - Configuración y manejo de interrupciones externas
    - Uso de interrupciones para responder a eventos en tiempo real
    - Técnicas de optimización para interrupciones y reducción de latencia

42. **Control de motores: BLDC, Stepper y DC**
    - Control de motores DC utilizando PWM
    - Control de motores paso a paso (Stepper)
    - Control de motores BLDC y su aplicación en sistemas embebidos

# Módulo 7: Protocolos de Comunicación

43. **Comunicación UART (Serial)**
    - Configuración de comunicación UART en STM32
    - Transmisión y recepción de datos serie
    - Uso de interrupciones para manejo de UART

44. **Comunicación SPI y SPI avanzado (modo DMA)**
    - Configuración básica de SPI en STM32
    - Uso avanzado de SPI con DMA (Direct Memory Access) para transferencias más rápidas
    - Casos de uso: sensores, módulos de comunicación

45. **Comunicación I2C y detección de dispositivos**
    - Configuración de la interfaz I2C en STM32
    - Uso de I2C para comunicación con dispositivos como sensores y pantallas
    - Detección de dispositivos I2C en la red

46. **Comunicación CAN Bus y CAN FD**
    - Introducción a CAN Bus y su uso en vehículos y sistemas industriales
    - Configuración de comunicación CAN en STM32
    - Uso de CAN FD para mayor ancho de banda en aplicaciones avanzadas

47. **Comunicación USB (HID, CDC, MSC)**
    - Uso de USB en sistemas embebidos
    - Implementación de dispositivos HID (Human Interface Device)
    - Implementación de dispositivos CDC (Communication Device Class) y MSC (Mass Storage Class)

48. **Comunicación Ethernet con TCP/IP y lwIP**
    - Introducción a Ethernet en microcontroladores STM32
    - Configuración de TCP/IP usando lwIP
    - Implementación de servidores y clientes web en sistemas embebidos

49. **Comunicación Modbus, LIN y RS-485**
    - Implementación de Modbus RTU en sistemas embebidos
    - Configuración de la comunicación LIN (Local Interconnect Network)
    - Uso de RS-485 para comunicación en entornos industriales

50. **Comunicación Bluetooth (BLE y Clásico)**
    - Configuración de comunicación Bluetooth en sistemas embebidos
    - Diferencias entre Bluetooth Clásico y Bluetooth Low Energy (BLE)
    - Desarrollo de aplicaciones de comunicación Bluetooth con STM32

51. **Comunicación Wi-Fi con ESP8266/ESP32**
    - Uso de módulos ESP8266 y ESP32 para comunicación Wi-Fi
    - Configuración básica de redes Wi-Fi y TCP/IP
    - Desarrollo de aplicaciones IoT con Wi-Fi

52. **Comunicación LoRa, Zigbee y NFC**
    - Introducción a LoRa (Long Range) y su aplicación en redes de sensores
    - Uso de Zigbee para redes inalámbricas de bajo consumo
    - Implementación de NFC (Near Field Communication) en sistemas embebidos

53. **Comunicación MQTT, CoAP y OPC UA**
    - Introducción a protocolos IoT: MQTT (Message Queuing Telemetry Transport)
    - Uso de CoAP (Constrained Application Protocol) para dispositivos IoT
    - Integración de OPC UA (Open Platform Communications Unified Architecture) en sistemas industriales

# Módulo 8: Sistema Operativo en Tiempo Real (RTOS)

54. **Introducción a FreeRTOS y su estructura**
    - Conceptos básicos de un sistema operativo en tiempo real (RTOS)
    - Arquitectura de FreeRTOS y sus componentes principales
    - Creación de tareas y gestión de recursos en FreeRTOS

55. **Creación y administración de tareas en FreeRTOS**
    - Creación de tareas en FreeRTOS
    - Planificación de tareas y prioridades
    - Técnicas para optimizar el rendimiento de tareas

56. **Prioridades de tareas y planificación en RTOS**
    - Asignación de prioridades a tareas en FreeRTOS
    - Algoritmos de planificación en RTOS
    - Técnicas para evitar bloqueos y optimizar tiempos de respuesta

57. **Mecanismos de sincronización: semáforos, mutex y eventos**
    - Uso de semáforos y mutex para sincronizar tareas
    - Manejo de eventos y colas en FreeRTOS
    - Implementación de mecanismos de sincronización eficientes

58. **Comunicación entre tareas: colas y mensajes**
    - Uso de colas para la comunicación entre tareas en FreeRTOS
    - Implementación de mensajes y pasos de información entre tareas
    - Ejemplos de sistemas con múltiples tareas y comunicación inter-tareas

59. **Gestión de memoria en FreeRTOS**
    - Gestión dinámica de memoria en FreeRTOS
    - Técnicas para evitar fragmentación de memoria
    - Uso eficiente del heap y stack en sistemas embebidos

60. **Timers en FreeRTOS y su uso en aplicaciones de tiempo real**
    - Creación y gestión de timers en FreeRTOS
    - Uso de timers para tareas periódicas y temporizadores
    - Implementación de temporizadores para sistemas de control en tiempo real

61. **Protección y aislamiento de tareas en RTOS**
    - Protección de memoria y aislamiento de tareas en FreeRTOS
    - Prevención de interferencias entre tareas y procesos
    - Estrategias para mejorar la seguridad de las aplicaciones en RTOS

62. **Multithreading y multiprocesamiento en RTOS**
    - Introducción al multithreading en FreeRTOS
    - Uso de múltiples núcleos y procesadores en sistemas embebidos
    - Gestión de recursos compartidos entre hilos de ejecución

# Módulo 9: Principios SOLID y Buenas Prácticas en Firmware

63. **Introducción a SOLID en sistemas embebidos**
    - Explicación de los principios SOLID
    - Aplicación de SOLID en el desarrollo de firmware embebido
    - Ejemplos prácticos de cómo SOLID mejora la calidad del código

64. **Principio de Responsabilidad Única (SRP) aplicado a firmware**
    - Aplicación del principio SRP en sistemas embebidos
    - Ejemplos de código modular y bien estructurado
    - Estrategias para dividir responsabilidades de forma efectiva

65. **Principio Abierto/Cerrado (OCP) en sistemas embebidos**
    - Diseño de sistemas embebidos que sean fáciles de extender
    - Evitar modificaciones innecesarias en el código existente
    - Aplicación del principio OCP en protocolos y periféricos

66. **Principio de Sustitución de Liskov (LSP) aplicado a código C/C++**
    - Aplicación del principio LSP en programación embebida
    - Uso de herencia y polimorfismo en C/C++
    - Ejemplos de implementación que siguen el principio LSP

67. **Principio de Segregación de Interfaces (ISP) y diseño modular**
    - Dividir interfaces en partes más pequeñas y manejables
    - Diseño de código más flexible y mantenible
    - Aplicación del principio ISP en controladores de periféricos

68. **Principio de Inversión de Dependencias (DIP) en software embebido**
    - Uso de abstracciones para reducir el acoplamiento de código
    - Implementación de controladores de hardware siguiendo el principio DIP
    - Ejemplos de código que implementan este principio en sistemas embebidos

69. **Patrones de diseño en sistemas embebidos (Singleton, Factory, Observer)**
    - Introducción a patrones de diseño y su aplicabilidad en sistemas embebidos
    - Implementación de patrones Singleton y Factory para manejo de recursos
    - Uso del patrón Observer para comunicación entre módulos

# Módulo 10: Pruebas Unitarias y Depuración

70. **Introducción a las pruebas unitarias en sistemas embebidos**
    - Conceptos básicos de pruebas unitarias en firmware
    - Importancia de las pruebas en sistemas embebidos
    - Herramientas y frameworks comunes para pruebas en C (Unity, CMock)

71. **Uso de Ceedling, Unity y CMock para pruebas en C**
    - Instalación y configuración de Ceedling
    - Implementación de pruebas unitarias utilizando Unity
    - Uso de CMock para la simulación de dependencias externas

72. **Implementación de pruebas unitarias en FreeRTOS**
    - Creación de pruebas unitarias para tareas y sincronización en FreeRTOS
    - Verificación del comportamiento de la comunicación entre tareas
    - Ejemplos de pruebas de temporizadores y colas en FreeRTOS

73. **Técnicas de pruebas de hardware en el circuito**
    - Estrategias para realizar pruebas directamente sobre el hardware
    - Uso de herramientas como osciloscopios y analizadores lógicos
    - Pruebas de señales digitales y analógicas en sistemas embebidos

74. **Validación de periféricos mediante simulaciones**
    - Uso de simuladores para validar el comportamiento de periféricos
    - Técnicas de pruebas de interfaces de comunicación (I2C, SPI, UART)
    - Validación de controladores de motores y otros dispositivos periféricos

75. **Uso de herramientas de análisis estático (Cppcheck, Coverity)**
    - Introducción a herramientas de análisis estático de código
    - Configuración y ejecución de Cppcheck y Coverity en proyectos embebidos
    - Identificación y corrección de problemas comunes de código con estas herramientas

76. **Pruebas de estrés y rendimiento en microcontroladores**
    - Realización de pruebas de carga y estrés en sistemas embebidos
    - Medición del rendimiento de microcontroladores en condiciones extremas
    - Optimización del código para mejorar la eficiencia y rendimiento

77. **Estrategias de depuración y análisis de fallos**
    - Uso de depuradores (GDB, OpenOCD) para análisis detallado del código
    - Estrategias para localizar y resolver fallos en sistemas embebidos
    - Análisis de dumps de memoria y registros para diagnóstico de fallos

78. **Pruebas de regresión y automatización en sistemas embebidos**
    - Implementación de pruebas de regresión para asegurar estabilidad del sistema
    - Automatización de pruebas para facilitar la validación continua
    - Uso de herramientas de CI/CD para automatizar pruebas de firmware

# Módulo 11: Control de Versiones con Git

79. **Introducción a Git: ¿Qué es y por qué usarlo?**
    - Conceptos básicos de control de versiones y Git
    - Ventajas de usar Git en proyectos embebidos
    - Cómo Git mejora la colaboración y el seguimiento de cambios

80. **Configuración de Git en sistemas embebidos**
    - Instalación y configuración de Git en entornos de desarrollo embebidos
    - Configuración de repositorios para proyectos de firmware
    - Uso de configuraciones específicas para sistemas embebidos en Git

81. **Comandos básicos de Git (init, add, commit, push, pull)**
    - Uso de comandos básicos para gestionar el código fuente
    - Inicialización de repositorios y configuración de archivos de seguimiento
    - Realización de commits, push y pull de cambios de código

82. **Flujo de trabajo con Git: ramas y fusión**
    - Creación y gestión de ramas en proyectos de firmware
    - Cómo hacer merge y resolve conflictos en ramas
    - Flujo de trabajo Git para equipos de desarrollo de firmware

83. **Creación y gestión de ramas en proyectos de firmware**
    - Estrategias para la creación y manejo de ramas de desarrollo
    - Uso de ramas para pruebas, desarrollo y mantenimiento
    - Implementación de ramas para nuevas características o correcciones

84. **Resolución de conflictos en Git**
    - Manejo de conflictos al hacer merge entre ramas
    - Estrategias para evitar y resolver conflictos en proyectos de firmware
    - Uso de herramientas como Git mergetool para resolver conflictos

85. **Uso de etiquetas (tags) en versiones de firmware**
    - Concepto de etiquetas en Git y su uso en el control de versiones
    - Etiquetado de versiones estables o liberaciones de firmware
    - Cómo gestionar versiones de firmware con etiquetas en Git

86. **Trabajar con repositorios remotos: GitHub, GitLab, Bitbucket**
    - Configuración y uso de repositorios remotos para proyectos de firmware
    - Clonación, push y pull de proyectos en plataformas como GitHub, GitLab y Bitbucket
    - Colaboración en equipo usando plataformas de repositorios remotos

87. **Integración de Git con herramientas de CI/CD (GitHub Actions, Jenkins)**
    - Introducción a la integración continua (CI) y despliegue continuo (CD)
    - Configuración de pipelines de CI/CD en GitHub Actions y Jenkins
    - Automatización de pruebas y despliegues de firmware

88. **Estrategias para equipos de desarrollo con Git (ramas de desarrollo, release, hotfix)**
    - Flujo de trabajo Git para equipos grandes de desarrollo de firmware
    - Uso de ramas para desarrollo, releases y correcciones de errores (hotfix)
    - Estrategias para mantener la coherencia del código en equipos distribuidos

89. **Buenas prácticas en el uso de Git: mensajes de commit, convenciones de código, gestión de conflictos**
    - Mejores prácticas para el manejo de commits y ramas
    - Establecimiento de convenciones de código en proyectos de firmware
    - Cómo mejorar la gestión de conflictos y asegurar un flujo de trabajo eficiente
