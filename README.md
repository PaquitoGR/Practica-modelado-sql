# Practica-modelado-sql

Práctica del módulo Modelado de datos e introducción a SQL del Bootcamp Web15 | Keepcoding

## Enunciado

En KeepCoding queremos gestionar la flota de vehículos de empresa, controlando los
modelos de los coches, las marcas y el grupo empresarial de la marca (por ejemplo: VW,
SEAT, Audi etc. pertenecen al grupo VAG).

De los coches, también necesitamos saber el color, la matrícula, el número total
de kilómetros que tiene, la compañía aseguradora (Mapfre, MMT, AXA, etc), el número de
póliza y fecha de compra.

Además, de cada coche, queremos controlar las revisiones que se han pasado,
sabiendo los Kms que tenía en el momento de la revisión, la fecha y el
importe de la misma.
Aparte del script, habrá que entregar una consulta SQL para sacar el siguiente listado de
coches activos que hay en KeepCoding:

- Nombre modelo, marca y grupo de coches (los nombres de todos)
- Fecha de compra
- Matricula
- Nombre del color del coche
- Total de kilómetros
- Nombre empresa que está asegurado el coche
- Numero de póliza
  Nota: Los importes se debe controlar la moneda (EURO, DÓLAR etc.).

[Código SQL](schema%20keepmoving.sql)

## Diagrama ER

[Diagrama ER en formato drawio](KeepMoving%20Autos%20-%20ER.drawio)

![Diagrama Entidad-Relación](./img/Keepmoving%20ER.jpg)
