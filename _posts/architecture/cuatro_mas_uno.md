Se propone que una arquitectura se puede documentar con 4 vistas, mas una que las une



Vista logica:

Es independiente de las tecnologias que se estan usando, deberia de ser entendida por cualquiera de los stakeholders del sistema
- Modulos funcionales
- Aplicaciones que seran necesarias
- Relacion entre las aplicaciones
- Que bases de datos van a existir
- Entidades principales del sistema o de cada aplicacion 


Vista de Procesos:

Vista dinamica de la arquitectura que idealmente va centrada en los flujos mas criticos
- Interaccion de cada uno de los componentes del sistema

Vista de Desarrollo:
La arquitectura que percibe un desarrollador al trabajar en el sistema. Todo lo relevante para que un desarrollador pueda trabakar.
- Modulos organizados por carpetas
- Uso de Git
- Uso de herramientas
- Integracion continua

Vista Fisica:
Muestra como se ve ya de forma fisica como se encuentra un sistema o infrastructura
- Comunicaciones
- Puertos abiertos

Todo esto debe estar integrado a traves de escenarios.  

Paper:
https://www.cs.ubc.ca/~gregor/teaching/papers/4+1view-architecture.pdf
