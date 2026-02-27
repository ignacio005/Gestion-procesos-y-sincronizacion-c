# Gestión de Procesos y Sincronización en Linux (C)

Proyecto orientado a la implementación de mecanismos fundamentales de los sistemas operativos en entorno Unix/Linux utilizando el lenguaje C.

Se trabajan conceptos clave como creación de procesos, manejo de señales y sincronización mediante semáforos, incluyendo la resolución de problemas clásicos de concurrencia.

---

## Descripción

El repositorio está dividido en dos bloques principales:

### Gestión de Procesos
Implementación de programas que utilizan:

- `fork()` para creación de procesos
- `exec()` para ejecución de nuevos programas
- Manejo de señales (`SIGINT`, `SIGTERM`)
- Control básico del ciclo de vida de procesos

### Sincronización de Procesos
Implementación de mecanismos de concurrencia:

- Uso de semáforos para exclusión mutua
- Coordinación entre procesos
- Resolución del problema clásico de la barbería
- Control de acceso a recursos compartidos

---

## Conceptos Técnicos Trabajados

- Procesos en sistemas Unix
- Creación y jerarquía de procesos
- Señales y gestión de interrupciones
- Concurrencia
- Exclusión mutua
- Sincronización con semáforos
- Problemas clásicos de sincronización

---

## Tecnologías

- Lenguaje C
- Entorno Linux / Unix
- GCC
- Librerías estándar de sistemas

---

## Compilación y Ejecución

Ejemplo de compilación:

```bash
gcc Gestion_Procesos/fork.c -o fork
./fork

gcc Sincronizacion_Procesos/semaforos.c -o semaforos -pthread
./semaforos
