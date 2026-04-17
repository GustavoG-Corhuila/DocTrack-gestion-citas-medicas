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
- [Progreso del Proyecto](#progreso-del-proyecto)
- [Alcance funcional objetivo](#alcance-funcional-objetivo)
- [Stack tecnológico propuesto](#stack-tecnológico-propuesto)
- [Roadmap](#roadmap)
- [Estructura actual del proyecto](#estructura-actual-del-proyecto)
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

- Evidencias gráficas: [docs/img](./docs/img)

El detalle del avance del sprint se encuentra en la sección [Progreso del Proyecto](#progreso-del-proyecto).
La implementación de código (frontend/backend) está planificada en las siguientes iteraciones.

## Progreso del Proyecto

| Sprint | Estado |
|---|---|
| Sprint 1 | En curso |

- Informe de progreso: [INFORME-SPRINT1.md](./INFORME-SPRINT1.md)

Estado actual del tablero: 2 issues cerrados, 1 en revisión y 2 en progreso.

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


## Recursos

- Tablero del proyecto: https://github.com/users/GustavoG-Corhuila/projects/1/
- Video de presentación: https://drive.google.com/file/d/16tVT-tBkAlzWWv0wvhDftFVKup_6UKCL/view?usp=sharing

## Contribuciones

Si deseas contribuir:

1. Crea una rama desde main.
2. Realiza cambios pequeños y enfocados.
3. Abre un Pull Request con descripción y evidencias.