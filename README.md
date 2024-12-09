# MEDTIME: Sistema de Gestión de Citas Médicas

## Descripción
**MEDTIME** es un sistema desarrollado en ASP.NET Core que permite la gestión eficiente de citas médicas en línea. Los usuarios pueden programar citas, gestionar horarios de médicos y especialidades, y mantener un historial de citas completadas o canceladas.

## Tecnologías Utilizadas
- **Framework Backend:** ASP.NET Core (API y Web MVC)
- **Base de Datos:** SQL Server (con Entity Framework Core)
- **Frontend:** Razor Pages (ASP.NET MVC)

## Características
- CRUD completo para Pacientes, Médicos, Especialidades, Disponibilidad y Citas.
- Gestión de horarios y disponibilidad de médicos.
- Sistema de historial de citas completadas o canceladas.
- Interfaz amigable para usuarios.

## Estructura del Proyecto
El proyecto está dividido en tres capas principales:
1. **MEDTIME.Api**: API para lógica de negocio y conexión a base de datos.
2. **MEDTIME.Web**: Interfaz Web (ASP.NET Core MVC).
3. **DataLayer**: Contiene las entidades y el DbContext.
