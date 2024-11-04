# Dispositivos de Entrada/Salida

## Conceptos Generales
- **Características**:
  - No volatilidad
  - Bajo costo por bit comparado con las memorias de semiconductores
- **Conexión con la CPU**:
  - Bus de E/S (Input/Output Bus)
  - Permite intercambio de instrucciones y datos con periféricos

## Almacenamiento Secundario
- **Tipos de almacenamiento masivo**:
  - Usados para diferentes aplicaciones según características específicas

### Discos Magnéticos
- **Tipos**:
  - Discos rígidos con cabezas fijas o móviles
- **Estructura**:
  - Base magnetizable giratoria
  - Pistas (círculos concéntricos) y cilindros
  - Cabezas lectograbadoras para lectura/escritura
- **Controladora de disco**:
  - Controladora del motor y brazo actuador
  - Controladora de interfaz para la comunicación con la CPU
  - Procesador de disco para ejecutar comandos específicos
- **Especificaciones técnicas**:
  - **Tiempo de búsqueda**: Tiempo para mover el brazo entre pistas
  - **Tiempo de cambio de cabezas**: Cambio entre cabezas durante lectura/escritura
  - **Tiempo de acceso a datos**: Combinación de tiempos de búsqueda, cambio de cabezas y latencia
  - **Velocidad de transferencia**: Medida en Mb/s o Gb/s

### Discos Ópticos
- **Funcionamiento**:
  - Almacenan grandes cantidades de datos
  - Uso de **rayos láser** para lectura/escritura
  - Creación de **pits** (agujeros) y **lands** (áreas no quemadas)
- **Tipos comunes**:
  - CD, DVD, Blu-ray
- **Desventajas**:
  - Menor velocidad en comparación con discos rígidos

### Discos Magneto-Ópticos (MO)
- **Tecnología híbrida**:
  - Combina medios magnéticos con tecnología óptica
  - También conocidos como floptical
- **Ventajas**:
  - Alta densidad de datos
  - Resistencia a campos magnéticos
- **Desventajas**:
  - Requiere dos pasadas de escritura
  - Mayor tiempo de escritura

### Tarjetas de Memoria
- **Tipos de tarjetas**:
  - **ROM**: Memoria de solo lectura
  - **OTP**: Programables una sola vez
  - **SRAM**: Volátiles, requieren energía continua
  - **Flash**: No volátil, permite lectura/escritura
- **Características**:
  - Compactas y portátiles
  - Ideales para dispositivos móviles y portátiles
- **Desventajas**:
  - Costo alto en comparación con almacenamiento magnético

## Caché de Disco
- **Caché de lectura**:
  - Lee sectores adicionales de datos en caso de ser solicitados después
  - Mejora el tiempo de acceso y transferencia
- **Caché de escritura**:
  - Permite transferencias paralelas entre sistema y disco
  - Elimina tiempos de búsqueda en acceso aleatorio
