# El Administrador De Memoria
Es la parte del SO que se encarga de administrar la memoria y su labor consiste
en:
+ Llevar un registro de las partes de memoria que se están utilizando y aquellas
  que no.
+ Asignar espacio de memoria a los procesos cuando estos la necesiten.
+ Liberarla cuando los procesos terminen.
+ Administrar intercambio entre memoria principal y secundaria.

Un ejemplo de jerarquía de memoria:  
1. Cache nivel 1 (KiB): Empaquetados dentro del chip, por lo tanto su velocidad
   de acceso es de nanosegundos.
2. Cache nivel 2 (KiB): 12ns - 20ns
3. Memoria principal (RAM) (GiB): 70ns
4. Memoria secundaria (TiB): Almacenamiento permanente y para extender la
   memoria principal.

## Administración En Monoprogramación
Es la forma más simple de administrar memoria, consiste en ejecutar solo un
programa, compartiendo la memoria con el SO. Cuando el usuario digita un comando
el usuario carga el programa respectivo en la memoria y lo ejecuta. Luego,
cuando el programa termina, el SO solicita un nuevo comando y carga el nuevo
programa a la memoria, sobrescribiendo el anterior.

## Administración En Multiprogramación
### Particiones Fijas

# FALTA ALGO
