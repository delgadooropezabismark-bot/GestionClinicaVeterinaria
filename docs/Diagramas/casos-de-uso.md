# Diagrama de Casos de Uso

```mermaid
flowchart LR
    Recepcionista --> RegistrarPropietario
    Recepcionista --> RegistrarMascota
    Recepcionista --> AgendarCita
    Recepcionista --> ModificarMascota
    Recepcionista --> CancelarCita

    Administrador --> VerCitas
    Administrador --> EliminarRegistros

    RegistrarMascota --> Propietario
    AgendarCita --> Mascota

Este diagrama representa:

**Actores**
- Recepcionista
- Administrador

**Casos de uso**
- Registrar propietario
- Registrar mascota
- Agendar cita
- Modificar mascota
- Cancelar cita
- Ver citas
- Eliminar registros

---

# 2️⃣ Diagrama de Clases

Ahora crea:
