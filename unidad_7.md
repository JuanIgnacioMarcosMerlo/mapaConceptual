# Transferencias de Entrada/Salida  
## Definición  
- Comunicación entre CPU y dispositivos periféricos.  

## Buses  
- Elementos de comunicación que conectan componentes.  
- Tipos de señales:  
  - **Dirección**: Indica la dirección de memoria.  
  - **Control**: Señales de control de transferencia.  
  - **Datos**: Transfiere datos entre componentes.  

## Jerarquía de Buses  
- **Buses internos**: Conectan registros dentro de un chip.  
- **Buses de placa**: Conectan chips en una placa.  
- **Buses de interconexión**: Conectan diferentes placas.  

## Dispositivos de E/S  
- Controladores y adaptadores que gestionan la comunicación.  
- Modalidades de E/S:  
  - **Controlada por programa (PIO)**: La CPU controla la transferencia.  
  - **Iniciada por interrupción**: La interfaz genera una interrupción cuando está lista.  
  - **Acceso directo a memoria (DMA)**: Transferencias sin intervención de la CPU.  

## Interrupciones  
- Eventos que suspenden la actividad actual del microprocesador.  
- Tipos:  
  - **Interrupciones internas**: Generadas por el software.  
  - **Interrupciones externas**: Generadas por dispositivos de hardware.  

## Controladores  
- Dispositivos que gestionan la comunicación entre la CPU y los periféricos.  
- **Controlador DMA**: Permite transferencias sin intervención de la CPU.  
- **Drivers**: Programas que permiten al SO comunicarse con dispositivos específicos.


# Interfaz USB  
## Introducción  
- Desarrollo iniciado en 1994, versión 1.0 en 1996.  
- Regulada por USB Implementers Forum (USB-IF).  
- Unificación de conectores y simplificación de interfaces.  

## Características  
- Velocidades:  
  - USB 1.1: 12 Mbps.  
  - USB 2.0: 480 Mbps (40 veces más rápido que USB 1.1).  
- Plug & Play: Conexión fácil de dispositivos.  
- Longitudes de cable: Hasta 5 metros, 25 metros con hubs.  

## Controladores USB  
- **UHCI**: Interfaz de controlador de terminal, estándar 1.1.  
- **OHCI**: Equivalente a UHCI, desarrollado por Intel.  
- **EHCI**: Estándar para USB 2.0, soporta múltiples velocidades.  

## Tipos de Conectores  
- **Conector Tipo A**: Conexión estándar.  
- **Conector Tipo B**: Usado en impresoras y dispositivos.  
- **Conector Tipo C**: Conector reversible y más moderno.  

## Versiones del Estándar  
- **1.1**: Mejoras sobre la versión inicial.  
- **2.0**: Alta velocidad.  
- **3.0**: Velocidades aún mayores.  
- **3.1 Gen 1 y Gen 2**: Mejoras en la eficiencia y velocidad.  
- **3.2**: Últimas actualizaciones.  

## Compatibilidad  
- Soporte para versiones anteriores.  
- Ejecución de aplicaciones y sistemas operativos de 32 y 16 bits.