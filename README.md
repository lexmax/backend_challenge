DESAFÍOS A ALCANZAR:
-------------------

Se debe crear una aplicación con el proposito de dar mantenimiento a una sola tabla.
Esa tabla debe contar con las siguientes caracteristicas.

| CAMPOS | ATRIBUTOS |
| --- | --- |
| id | INT() NOT NULL |
| name | VARCHAR(100) NOT NULL |
| lastname | VARCHAR(150) NOT NULL |
| email | VARCHAR(200) NOT NULL |
| address | TEXT |
| reference_address | TEXT |
| phone_number | VARCHAR(20) |


### Nivel 1(creación): 
  Las apis (5) a crear deben cumplir con las opciones para dar mantenimiento a esta entidad(CRUD)
  
  - GET => Para listar todos los registros.
  - GET => Para obtener un item especifico.
  - POST => Para añadir un nuevo item.
  - PUT => Para actualizar un item espefifico.
  - DELETE => Para eliminar un item especifico.

### Nivel 2 (Reglas):

- Para los efectos de actualización y/o creación 3 campos son obligatorios(name, lastname, email).

### Nivel 3 (Documentación):
- Documentar las apis creadas. Sugerimos utilizar swagger.

### Nivel 4 (Portabilidad): 
- Crear un docker file que permita crear la imagen.


REPOSITORIO:
-------------

El repositirio debe contar con:
- Descripción
- Alcances del desarrollo (nivel desarrollado)
- Indicaciones de como ejecutar la solución


REQUISITOS:
-----------

En este desafío debes mostrar tu habilidades en el manejo de tecnologías como:

- Python >= 3.7
- Flask >= 2.0.0
- SqLite


DESAFÍOS A ALCANZAR:
-------------------

Este es un desafío de next y no de diseño. En este desafío debes mostrar tu habilidades en el manejo de tecnologías como:

- Typescript
- Next
- Uso de Ant design 



Evalución: backend-python nivel 1
