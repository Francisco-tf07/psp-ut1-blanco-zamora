# Informe · Práctica ProcLab (UT1)

**Alumno/a:** [Nombre y apellidos] · **Sistema operativo usado:** [p. ej. Ubuntu 24.04 en VirtualBox]

> Incluye en cada apartado los comandos, la salida relevante (o una captura de `capturas/`) y tus respuestas razonadas.
> Para insertar una captura: `![descripción](capturas/nombre.png)`

## B0 · Preparación del entorno

- `gcc --version`:
- `java -version`:
- `git log --oneline` tras el primer commit:

## B1 · Procesos en Linux y en C

### B1.1 · Exploración desde la terminal
1. Rama del árbol hasta el PID 1:
2. Dos `sleep` en segundo plano (padre y estado):
3. STOP/CONT y SIGTERM frente a SIGKILL:
4. `nice` y `renice`:
5. Cinco campos de `/proc/<PID>/status` relacionados con el BCP:
6. Concurrencia/paralelismo y proceso/hilo; núcleos e hilos observados:

### B1.2 · Árbol genealógico
### B1.3 · ¿Cuántos procesos?
| Fragmento | Predicción | Resultado real | Explicación |
|-----------|-----------|----------------|-------------|
| A | | | |
| B | | | |

### B1.4 · Lanzador
### B1.5 · Zombis y huérfanos
### B1.6 · ★ Tubería (opcional)

## B2 · Crear y controlar procesos en Kotlin
### B2.1 · Ejecutor
### B2.2 · Mini-ps
### B2.3 · Vigilante
| Caso | Código de salida | Explicación |
|------|:----------------:|-------------|
| Cierre normal | | |
| `destroy()` | | |
| `destroyForcibly()` | | |

## B3 · Comunicación entre procesos
### B3.1 · Cifrado César
### B3.2 · Almacén clave-valor
### B3.3 · Tuberías nativas y redirecciones

## B4 · Sincronización y varias tareas en paralelo
### B4.1 · Primos en paralelo
Núcleos del equipo: [ ]

| K (procesos) | Tiempo (s) | Aceleración (T₁ / Tₖ) |
|:------------:|:----------:|:---------------------:|
| 1 | | 1,00 |
| 2 | | |
| 4 | | |
| nº de núcleos | | |
| 2 × nº de núcleos | | |

Análisis:

### B4.2 · Pool de procesos
### B4.3 · Tareas con dependencias

## B5 · Proyecto integrador
| # | Caso | Resultado obtenido | ¿Correcto? |
|:-:|------|--------------------|:----------:|
| 1 | Varios ficheros, uno grande | | |
| 2 | Fichero vacío | | |
| 3 | Fichero sin permiso de lectura | | |
| 4 | Fichero lento (timeout) | | |
| 5 | Directorio inexistente o sin `.txt` | | |
| 6 | Rendimiento: `--secuencial` vs `--max` 1, 2, 4 | | |
| 7 | Nunca más de `--max` trabajadores vivos | | |

Conclusiones de rendimiento:
