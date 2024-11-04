# Procesadores Avanzados  
## Paralelismo  
- Aumenta la velocidad de cómputo.  
- Multiplica unidades de ejecución.  
- Tipos de paralelismo:  
  - **Paralelismo a nivel de instrucción**: Ejecución simultánea de etapas de instrucciones.  
  - **Pipelining**: Segmentación de instrucciones en etapas.  

## Técnicas de Ejecución  
- **Frecuencia de reloj**: Aumentar la frecuencia para mayor velocidad.  
- **Paralelismo a nivel instrucción**:  
  - Ejecución simultánea de instrucciones.  
  - Grado de paralelismo: Cantidad de etapas definidas.  
  
## Unidades de Ejecución  
- **Memory Manager Unit**: Traduce direcciones lógicas.  
- **Bus Interface Unit**: Acceso a memoria y E/S.  
- **Code Prefetch Unit**: Precarga de instrucciones.  
- **Instruction Decode Unit**: Decodificación de instrucciones.  
- **Execution Unit**: Ejecución del microcódigo.  

## Dependencias  
- **Dependencia de datos**: Conflictos por resultados de instrucciones previas.  
- **Ejecución fuera de orden**: Reordenamiento de instrucciones para evitar esperas.  

## Diseño Superescalar  
- Múltiples vías de procesamiento paralelo.  
- Planificador determina ejecución paralela de instrucciones.  

## Multiprocesadores  
- **Thread Level Parallelism (TLP)**: Ejecución simultánea de hilos.  
- **Chip-Level Multiprocessing (CMP)**: Multiprocesadores en un solo chip.  
- **Simultaneous Multithreading (SMT)**: Ejecución de múltiples hilos en un solo núcleo.  

## Arquitectura Itanium  
- **EPIC (Explicitly Parallel Instruction Computing)**: Ejecución paralela de instrucciones.  
- Registros internos: 128 registros de enteros y coma flotante.  
- Soporte para aplicaciones de alto nivel.  

## Tipos de Paralelismo según Flynn  
- **SISD**: Un solo procesador, secuencial.  
- **MISD**: Múltiples instrucciones, un solo flujo de datos.  
- **SIMD**: Una instrucción, múltiples datos.  
- **MIMD**: Múltiples instrucciones, múltiples datos.  

## Mejora de Rendimiento  
- **Especulación**: Ejecución anticipada de instrucciones.  
- **Predicación**: Ejecución de instrucciones basadas en condiciones.  
- **Predicción de saltos**: Técnicas para anticipar el flujo de ejecución.