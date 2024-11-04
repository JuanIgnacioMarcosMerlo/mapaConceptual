# Memorias

## Conceptos Generales
- **Unidad de información**:
  - Conjunto de bytes accesibles conjuntamente (bloques, palabras, posiciones de memoria)
- **Tiempo de acceso**:
  - Tiempo entre la orden de lectura y la disponibilidad de los datos

## Clasificación de Memorias
- **Según el modo de acceso**:
  - **Acceso aleatorio**: Acceso directo e independiente de la posición física
  - **Acceso secuencial**: Acceso en orden, el tiempo depende de la ubicación
- **Según las operaciones**:
  - **Lectura/escritura**: Permite ambas operaciones
  - **Solo lectura**: Solo permite lectura
- **Según duración de la información**:
  - **Volátiles**: Pierden información sin energía
  - **No volátiles**: Retienen información sin energía

## Tipos de Memorias RAM
- **SRAM** (Static RAM):
  - Estática, rápida y volátil
  - Usa biestables para cada bit
- **DRAM** (Dynamic RAM):
  - Dinámica y volátil
  - Necesita refresco de carga periódica (ciclo de refresco)
  - Mayor capacidad y menor costo por bit que SRAM
- **Memoria Caché**:
  - **Ubicada entre CPU y RAM** para aumentar velocidad de acceso
  - **Jerarquías**:
    - **Caché de nivel 1** (L1): Rápida, cercana a la CPU
    - **Caché de nivel 2** (L2): Mayor capacidad, respaldo de L1
  - **Conexiones**:
    - **Serie (look-through)**: Acceso directo
    - **Paralelo (look-aside)**: Procesa solicitudes en paralelo

## Dimensión de Memoria
- **Unidades de medida**:
  - Bits, Bytes, KB, MB, GB, TB, PB, EB
- **Capacidad de memoria**:
  - Aumento en capacidad se expresa en múltiplos de 1024

## Memoria Virtual
- **Modelos de memoria**:
  - **Segmentación pura**: Divide en segmentos contiguos y lógicos
  - **Paginación por demanda**: Uso de páginas virtuales y físicas en memoria y disco
- **Administración de Páginas**:
  - **Page fault**: Error cuando no se encuentra página en memoria
  - **Algoritmos de reemplazo**:
    - FIFO, LRU, y Random
  - **Swipe in/out**: Carga y descarga de páginas en memoria

## Modelos de Memoria RAM
- **Tipos de módulos**:
  - **DIMM**: Placa con chips de memoria para instalación en placas base
- **Tecnologías DDR**:
  - **DDR (Double Data Rate)**:
    - DDR, DDR2, DDR3, DDR4, DDR5
    - Diferencias en velocidad, voltaje y número de pines

## Controlador de Memorias Dinámicas
- **RAS/CAS**:
  - Señales para seleccionar filas y columnas en memoria dinámica
- **Función**:
  - Controlar el acceso y el ciclo de refresco

## Velocidad del Bus de Memoria
- **Ancho de banda**:
  - Determinado por ancho de bus y frecuencia en MHz
- **Tecnología DDR SDRAM**:
  - Enviar datos dos veces por ciclo de reloj (Double Data Rate)
  - **DDR2-800**: Ejemplo de DDR, con ancho de banda de 6.4 GHz

## Detección y Corrección de Errores (ECC)
- **ECC**:
  - Detecta y corrige errores de uno o más bits
  - Utilizado en sistemas de alta gama

## Almacenamiento de Bytes en Memoria
- **Endianness**:
  - Big-Endian vs. Little-Endian

## Modelos de Memoria Virtual
- **Segmentación y Paginación**:
  - Uso de tablas descriptivas para manejar segmentos y páginas
  - **Page fault** y **algoritmos de reemplazo**

## Modos de Operación del Procesador
- **Modo Real**:
  - Acceso sin protección
- **Modo Protegido**:
  - Protección y gestión avanzada de memoria

