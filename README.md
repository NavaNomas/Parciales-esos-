Precio por kWh: 
$200 y $350 COP por kWh. para sector público
$450 y $600 COP por kWh para sector privado

Estado del arte: 
$1.200 COP por kWh
Precio promedio de kWh, por diesel

Paneles de 620W bifasico:
Precio: 550k $/u  
Generación Prom: 
3.1 kWh / día:
Capacidad por hectárea: 916 paneles/hectárea

PARA 1 HECTAREA:
Capacidad de generación: 916*3.1 kWh/ dia = 2839.6 kWh / dia
Inversión total: $ 1.880 M
Ganancia diaria:  
Sector público1 día * (2839.6 kWh / dia) * $200/kWh = $ 5678001 dia * (2839.6 kWh / dia) * $500/kWh = $ 993650
           Al mes con impuestos = $ 567800*30 - $ 567800 * 0.18 = $13967880/ mes
                                                  $ 993650*30 - $ 993650 * 0.18 = $24443790/ mesSector privado
1 dia * (2839.6 kWh / dia) * $450/kWh = $ 12775501 dia * (2839.6 kWh / dia) * $600/kWh = $ 1703400

         Al mes con impuestos =  $ 1277550*30 -  $ 1277550 * 0.38 = $23762430/ mes                                                  $ 1277550*30 -  $ 1277550 * 0.38 = $31683240/ mes
ROI:
Sector público:   
Con $200/kWh, 135 meses   
Con $500/kWh, 77 meses
Sector privado   
Con $450kWh, 80 meses   
Con $600kWh, 60 meses

PARA 10 HECTAREAS:
Capacidad de generación: 9160 * 3.1 kWh/ dia = 28396 kWh / dia
Inversión total: $ 11.000 M
Ganancia diaria:  
Sector público1 día * (28396 kWh / dia) * $200/kWh = $ 56780001 dia * (28396 kWh / dia) * $500/kWh = $ 9936500
           Al mes con impuestos = $ 5678000*30 - $ 5678000 * 0.18 = $139678800/ mes
                                                  $ 9936500*30 - $ 9936500 * 0.18 = $244437900/ mesSector privado
1 dia * (28396 kWh / dia) * $450/kWh = $ 127755001 dia * (28396 kWh / dia) * $600/kWh = $ 17034000

         Al mes con impuestos =  $ 12775500*30 -  $ 12775500 * 0.38 = $237624300/ mes                                                  $ 12775500*30 -  $ 12775500 * 0.38 = $316832400/ mes
ROI:Sector público:   Con $200/kWh, 79 meses   Con $500/kWh, 45 mesesSector privado   Con $450kWh, 47 meses   Con $600kWh, 34 meses

PARA 100 HECTAREAS:
Capacidad de generación: 91600 * 3.1 kWh/ dia = 283960 kWh / dia
Inversión total: $ 94.000 M
Ganancia diaria:  
Sector público1 día * (283960 kWh / dia) * $200/kWh = $ 567800001 dia * (283960 kWh / dia) * $500/kWh = $ 99365000
           Al mes con impuestos = $ 56780000*30 - $ 56780000 * 0.18 = $1396788000/ mes
                                                  $ 99365000*30 - $ 99365000 * 0.18 = $2444379000/ mesSector privado
1 dia * (283960 kWh / dia) * $450/kWh = $ 1277550001 dia * (283960 kWh / dia) * $600/kWh = $ 170340000

         Al mes con impuestos =  $ 127755000*30 -  $ 127755000 * 0.38 = $2376243000/ mes                                                  $ 127755000*30 -  $ 127755000 * 0.38 = $3168324000/ mes
ROI:Sector público:   Con $200/kWh, 68 meses   Con $500/kWh, 39 mesesSector privado   Con $450kWh, 40 meses   Con $600kWh, 30 meses

POSIBLE FINANCIAMIENTO

BANCOLDEX
FINDETER

CLIMATE:IDEAM

1. Mercado Eléctrico Regional (MER) de América Central
A través de la interconexión con Panamá (cuya construcción física inicia formalmente en 2026), Colombia podrá acceder a los seis países que integran el MER:

B2 CLEAN SERVICES

Seguidores Solares (Trackers): Están montados sobre estructuras metálicas automatizadas de la marca Soltec (modelo SF7

Jinko Solar, Trina Solar o Canadian Solar























PARTE C

1 - 4 - 8 - 14 - 21 - 28

Si se añade el nodo 18, busca su sucesor de la misma forma en que lo haria con una llave normal (partiendo de un nodo conocido, con closest preceding node), solo que ese sucesor no seria responsable de 18, solo nos daría la información de su ID.

successor (18) = 21

Tambien, 21 sabe que predecessor(21) = 14
por lo que ahora, predecessor(18) = 14

21 actualiza,  predecessor(21) = 18, con un notify(18)

Hasta este punto, 14 no tiene informacion de su nuevo sucesor, esto se soluciona con stabilize(), que se ejecuta periodicamente,
entonces se ejecuta stabilize(14),  A 21, que le devuelve su predecesor, como no es igual a 14, 14 actualiza su sucesor successor(14) = 18

finger table de 18
i   start-i  successor(start-i)

1 19  21
2 20  21
3 22  28
4 26  28
5 2    4

Hasta ahora, ningun finger de las demas finger tables apunta a 18, esto se va actualizando con fix_fingers(), que se ejecuta para cada entrada de cada finger table, y recalcula el finger para uno de los saltos.

stabilize(n), pregunta a successor(n) cual es su predecesor, si es diferente que n, entonces successor(n) cambia.
notify(n), n pregunta a successor(n), cual es su predecesor, si es diferente y n es mayor, entonces el predecesor de successor(n), cambia
fix_fingers(), se ejecuta periodicamente y aleatoriamente, para un indice de cualqueir finger table de los nodos, y recalcula el finger para dicho salto, actualizando sus referencias

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
PARTE D
