```MERMAID
gantt
    title POI-WIFI
    axisFormat  %m-%d
    section Avvio
    A1 :a1, 2000-01-01, 2d
    A2 :a2, after a1  , 3d
    A3 :a3, after p1, 1d 

    section Dati
    P2 :p2, after p1, 4d

    section Budget
    P1 :p1, after a2  , 4d

    section DATABASE
    R2 :r2, after p1, 78h
    R3 :r3, after r2, 2d
    C1 :c1, after r3, 7d

    section SERVER
    R1 :r1, after p2, 14d

    section FrontEnd
    R4 :r4, 2000-01-23, 5d 

    section Attrezzatura
    P3 :p3, after p1, 10d

    section AP
    P4 :p4, after a2, 6d
    P5 :p5, after p4, 3d
    R5 :r5, after p5, 4d
    R6 :r6, after r5, 127h
    C3 :c3, after r6, 3d

    section Stand
    C2 :c2, after r5, 1d

    section Collaudo
    C4 :c4, after r1, 2d
    C5 :c5, after r1, 4d



