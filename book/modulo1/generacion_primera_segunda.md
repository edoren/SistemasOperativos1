# Primera Y Segunda Generación

## Primeras Maquinas
+ Monoprogramación.
+ Labores especificas.
+ Dueño absoluto.
+ Tiempos Específicos.

## Acceso Al Sistema
+ __Programador:__
    - Escribe programas en papel.
    - Perfora tarjetas.
    - Arma pila.
    - Entrega al operador.
    - Observe (sin contacto con la máquina).
+ __Operador:__
    - Recibe pilas diferentes.
    - Carga programas.
    - Vigila ejecución.
    - Recoge resultados.
    - Entrega al programador.
    - Optimiza su labor.

## Secuencia Automática De Trabajos
+ __Monitor residente:__
    - Transferencia automática de un trabajo a otro.
    - Es considerado el primer S.O porque es residente en memoria y cuando
      enciende la maquina se de control al MR.
+ __Contiene un MR:__
    - Secuenciador automático de trabajos.
    - Interprete de tarjetas de control (J.C.L).
    - Controladores de dispositivos I/O
+ __Primeros S.O:__
    - FMS.
    - IBSYS.

## Mejora De Desempeño
M.R solucionó muchas cosas pero... Existe mucho tiempo ocioso del C.P.U
por los sistemas mecánicos de I/O. Se implementan las siguientes técnicas.

+ __OFF-LINE:__
    - Cintas magnéticas.
    - Sistemas de impresión.
+ __BUFFERING:__
    - Memoria intermedia.
    - Volcado de memoria.
+ __SPOOLING:__
    - Discos _"/usr/spool/mail"_
    - Online _"/usr/spool/lp"_
