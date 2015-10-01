# El Administrador De Procesos
Hasta ahora hemos hablado de programas/procesos un poco vagamente y como si
fueran sinónimos, pero son conceptos distintos. Un procesos es un programa en
ejecución, incluyendo el valor actual del PC (Program Counter), registros y
variables. Un programa es pasivo (Es solo código o texto) y un proceso es
activo y dinámico (varia en el tiempo). Analogía: preparar una receta de una
torta. El programa es la receta, el proceso es la actividad que consiste en
leer la receta, mezclar los ingredientes y hornear la torta. Varios procesos
pueden estar ejecutando el mismo programa, __(FALTA ALGO)__, si dos o mas
usuarios están usando simultáneamente el mismo editor de texto. El programa es
el mismo, pero el usuario tiene un proceso distinto (y con distintos datos).
Conceptualmente el proceso tiene su propia CPU virtual. En la practica hay
una sola CPU real, que cambia periódicamente la ejecución de un proceso a
otro, pero para entender el proceso a otro, pero para entender el sistema es
mas fácil modelarlo como una colección de procesos secuenciales que ejecuten
concurrentemente (pseudoparalelismo).

## Estados de un proceso
Para efectos del S.O, el proceso puede estar en uno de los siguientes estados.

### Ejecutando
El procesos esta siendo ejecutado (atendido) en al CPU. Por los tanto a lo
mas un procesos puede estar en este estado en un procesador uniproceso.

### Listo
El proceso esta en condiciones de ejecutarse pero debe esperar su turno de
CPU.

### Bloqueado
El proceso no esta en condiciones de ejecutar. Esta esperando a que algún
evento ocurra, como la finalización de una operación I/O. También se dice que
está suspendido o en espera.
