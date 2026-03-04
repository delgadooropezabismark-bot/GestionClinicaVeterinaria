#  Sistema de Gestión de Clínica Veterinaria

##  Descripción del Proyecto

Este proyecto consiste en el desarrollo de una aplicación web CRUD para la gestión de una clínica veterinaria.  
El sistema permite administrar propietarios, mascotas y citas médicas, asegurando la persistencia de datos mediante SQL Server y aplicando el patrón de arquitectura MVC.

El desarrollo se realiza bajo un enfoque socioformativo orientado a competencias, utilizando aprendizaje ágil (trabajo por sprints) y evaluación auténtica.

---

##  Objetivo General

Aplicar el enfoque socioformativo orientado a competencias mediante el aprendizaje ágil, desarrollando una aplicación CRUD básica con persistencia de datos utilizando:

- C# 7.3+
- .NET / ASP.NET Core MVC
- SQL Server
- Entity Framework Core
- Visual Studio Code
- Git y GitHub

---

##  Texto Base para Formulación de Requerimientos

"La clínica veterinaria necesita un sistema simple para gestionar las mascotas y sus citas médicas. El personal administrativo debe poder registrar nuevos propietarios y mascotas, actualizar información existente, eliminar registros obsoletos y consultar listados de mascotas registradas. Además, se requiere agendar citas médicas, asegurando que cada cita esté asociada a una mascota registrada y evitando conflictos de fechas. El sistema debe ser accesible desde una interfaz web básica y permitir el seguimiento del estado de cada cita."

---

#  Metodología de Trabajo

El proyecto se desarrolló en tres etapas:

##  Sprint 0 – Análisis y Requerimientos
- Identificación de historias de usuario.
- Priorización del backlog.
- Publicación de historias en GitHub (Issues).
- Organización del trabajo colaborativo.

##  Sprint 1 – Diseño y Modelado
- Elaboración de diagrama de clases.
- Elaboración de diagrama de casos de uso.
- Definición de relaciones entre entidades.
- Refinamiento de historias de usuario.

##  Sprint 2 – Implementación
- Desarrollo del proyecto en ASP.NET Core MVC.
- Implementación de operaciones CRUD.
- Integración con SQL Server.
- Aplicación de validaciones.
- Pruebas funcionales del sistema.

---

#  Entidades del Sistema

###  Propietario
- ID
- Nombre
- DNI
- Teléfono
- Dirección

###  Mascota
- ID
- Nombre
- Especie
- Raza
- Fecha de Nacimiento
- PropietarioID

###  Cita
- ID
- Fecha de Cita
- Motivo
- Estado (Pendiente, Atendida, Cancelada)
- MascotaID

---

#  Relaciones

- Un Propietario puede tener muchas Mascotas (1:N).
- Una Mascota puede tener muchas Citas (1:N).

---

#  Funcionalidades Implementadas

- Registro, edición y eliminación de propietarios.
- Registro, edición y eliminación de mascotas.
- Agendamiento, modificación y cancelación de citas.
- Validaciones de datos.
- Persistencia en base de datos SQL Server.

---

#  Tecnologías Utilizadas

- C#
- .NET
- ASP.NET Core MVC
- SQL Server
- Entity Framework Core
- Git & GitHub
- PlantUML

---

#  Estructura del Proyecto

/docs  
&nbsp;&nbsp;&nbsp;&nbsp;Diagramas  
&nbsp;&nbsp;&nbsp;&nbsp;HistoriasDeUsuario.md  
&nbsp;&nbsp;&nbsp;&nbsp;Backlog.md  
&nbsp;&nbsp;&nbsp;&nbsp;COLABORACION.md  

/src  
&nbsp;&nbsp;&nbsp;&nbsp;ProyectoMVC  

script_database.sql  
README.md  

---

#  Trabajo Colaborativo

El equipo trabajó utilizando control de versiones con Git y GitHub, empleando:

- Creación de Issues para historias de usuario.
- Uso de ramas (branches).
- Pull Requests para integración de cambios.
- Commits frecuentes por integrante.
- Registro de reuniones en archivo COLABORACION.md.

---

#  Reflexión Socioformativa

El desarrollo del proyecto permitió fortalecer competencias en análisis de requerimientos, modelado UML, desarrollo con patrón MVC, trabajo colaborativo y gestión ágil del tiempo. La organización por sprints facilitó la división de tareas y el cumplimiento progresivo de objetivos.

---

#  Integrantes

- Nombre del Integrante 1
- Nombre del Integrante 2
- Nombre del Integrante 3

---

#  Fecha de Entrega

[Colocar fecha aquí]
