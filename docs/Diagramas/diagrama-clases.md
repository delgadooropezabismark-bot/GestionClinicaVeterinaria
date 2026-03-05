
# Diagrama de Clases

```mermaid
classDiagram

class Propietario{
    id
    nombre
    telefono
    direccion
}

class Mascota{
    id
    nombre
    especie
    raza
    edad
}

class Cita{
    id
    fecha
    hora
    estado
}

Propietario "1" --> "0..*" Mascota : posee
Mascota "1" --> "0..*" Cita : tiene
