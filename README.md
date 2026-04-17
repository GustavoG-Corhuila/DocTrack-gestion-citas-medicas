# DocTrack

Sistema de gestión de citas médicas para consultorios independientes.

<p align="left">
  <img src="https://img.shields.io/badge/Estado-En%20desarrollo-0a7ea4" alt="Estado" />
  <img src="https://img.shields.io/badge/Frontend-React-61dafb" alt="React" />
  <img src="https://img.shields.io/badge/Backend-Node.js-3c873a" alt="Node" />
  <img src="https://img.shields.io/badge/Base%20de%20datos-PostgreSQL-336791" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Arquitectura-API%20REST-5c6ac4" alt="REST" />
</p>

## Tabla de contenido

- [Descripción](#descripción)
- [Problema que resuelve](#problema-que-resuelve)
- [Estado actual del repositorio](#estado-actual-del-repositorio)
- [Alcance funcional objetivo](#alcance-funcional-objetivo)
- [Stack tecnológico propuesto](#stack-tecnológico-propuesto)
- [Roadmap](#roadmap)
- [Sprint 1 (14/04/2026 - 28/04/2026)](#sprint-1-14042026---28042026)
- [Estructura actual del proyecto](#estructura-actual-del-proyecto)
- [Evidencias](#evidencias)
- [Recursos](#recursos)
- [Contribuciones](#contribuciones)

## Descripción

DocTrack es una solución web para digitalizar la gestión de agendas médicas. Está orientada a consultorios que hoy trabajan con llamadas telefónicas o agendas físicas y necesitan reducir errores operativos, optimizar tiempos y mejorar la experiencia del paciente.

## Problema que resuelve

La gestión manual de citas suele causar:

- Doble asignación de horarios.
- Ausentismo por falta de recordatorios.
- Baja visibilidad de la carga diaria del médico.
- Huecos de agenda que afectan ingresos y productividad.

DocTrack automatiza el ciclo de agendamiento para reducir estos problemas.

## Estado actual del repositorio

Este repositorio contiene principalmente documentación académica y evidencias del Sprint 1:

- Informe de avance: [INFORME-SPRINT1.md](./INFORME-SPRINT1.md)
- Evidencias gráficas: [docs/img](./docs/img)

La implementación de código (frontend/backend) está planificada en las siguientes iteraciones.

## Alcance funcional objetivo

- Registro e inicio de sesión para pacientes y médicos.
- Búsqueda de médicos por especialidad y disponibilidad.
- Reserva, reprogramación y cancelación de citas.
- Panel de agenda para médicos.
- Gestión de estado de citas (pendiente, confirmada, completada, cancelada).
- Recordatorios automáticos (correo y/o WhatsApp).

## Stack tecnológico propuesto

| Capa | Tecnología propuesta |
|---|---|
| Frontend | React |
| Backend | Node.js + Express |
| Base de datos | PostgreSQL |
| Autenticación | JWT o Firebase Auth |
| Despliegue | Vercel/Netlify + Railway/Render |

## Roadmap

| Fase | Alcance | Estado |
|---|---|---|
| Fase 1 | Identidad y perfiles | En curso |
| Fase 2 | Core de agendamiento | Pendiente |
| Fase 3 | Panel médico y notificaciones | Pendiente |
| Fase 4 | Integración y UX | Pendiente |
| Fase 5 | Pruebas y despliegue | Pendiente |

## Sprint 1 (14/04/2026 - 28/04/2026)

Historias priorizadas:

1. HU-01 Registro de nuevos pacientes.
2. HU-02 Inicio de sesión seguro.
3. HU-03 Gestión de perfil del médico.
4. HU-04 Recuperación de contraseña.
5. HU-05 Validación de tarjeta profesional.

Motivación: estas historias corresponden a la épica de identidad, base necesaria para habilitar el flujo de citas.

## Estructura actual del proyecto

```text
DocTrack-gestion-citas-medicas/
|-- docs/
|   |-- img/
|   |   |-- tableroKanban.png
|   |   |-- pulse.png
|   |   |-- contributors.png
|   |   |-- commits.png
|   |   |-- codeFrecuency.png
|-- INFORME-SPRINT1.md
|-- README.md
```

## Evidencias

- Tablero Kanban: [docs/img/tableroKanban.png](./docs/img/tableroKanban.png)
- Pulse: [docs/img/pulse.png](./docs/img/pulse.png)
- Contributors: [docs/img/contributors.png](./docs/img/contributors.png)
- Commits: [docs/img/commits.png](./docs/img/commits.png)
- Code frequency: [docs/img/codeFrecuency.png](./docs/img/codeFrecuency.png)

## Recursos

- Tablero del proyecto: https://github.com/users/GustavoG-Corhuila/projects/1/
- Video de presentación: https://drive.google.com/file/d/16tVT-tBkAlzWWv0wvhDftFVKup_6UKCL/view?usp=sharing

## Contribuciones

Si deseas contribuir:

1. Crea una rama desde main.
2. Realiza cambios pequeños y enfocados.
3. Abre un Pull Request con descripción y evidencias.