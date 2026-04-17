# DocTrack

### Sistema de gestión de citas médicas para consultorios independientes

<p align="left">
	<img src="https://img.shields.io/badge/Estado-En%20desarrollo-0a7ea4" alt="Estado" />
	<img src="https://img.shields.io/badge/Frontend-React-61dafb" alt="React" />
	<img src="https://img.shields.io/badge/Backend-Node.js-3c873a" alt="Node" />
	<img src="https://img.shields.io/badge/Base%20de%20datos-PostgreSQL-336791" alt="PostgreSQL" />
	<img src="https://img.shields.io/badge/Arquitectura-API%20REST-5c6ac4" alt="REST" />
</p>

---

## Resumen

DocTrack es una aplicación web pensada para consultorios médicos que aún gestionan citas por teléfono o en agenda física. Permite que el paciente reserve su turno en línea y que el medico visualice y administre su agenda diaria desde un panel centralizado.

## Problema que resuelve

En consultorios pequeños, la gestión manual de 20 o 30 citas al día suele generar:

- Doble asignación de horarios.
- Ausentismo por falta de recordatorios.
- Poca visibilidad de la carga diaria del médico.
- Huecos muertos en agenda que se traducen en pérdida de ingresos.

DocTrack reduce estos problemas automatizando el ciclo completo de agendamiento.

---

## Tabla de contenidos

- [Características principales](#características-principales)
- [Stack tecnológico](#stack-tecnológico)
- [Arquitectura funcional](#arquitectura-funcional)
- [Flujo de usuario](#flujo-de-usuario)
- [Roadmap por fases](#roadmap-por-fases)
- [Instalación local](#instalación-local)
- [Estructura recomendada del proyecto](#estructura-recomendada-del-proyecto)
- [Métricas objetivo](#métricas-objetivo)
- [Seguimiento del proyecto](#seguimiento-del-proyecto)
- [Video de presentación](#video-de-presentación)
- [Contribuciones](#contribuciones)
- [Sprint 1 - Plan](#sprint-1--plan)

---

## Características principales

- Registro e inicio de sesión para pacientes y médicos.
- Búsqueda de médicos por especialidad y disponibilidad.
- Reserva, reprogramación y cancelación de citas.
- Panel del médico con vista diaria/semanal de agenda.
- Gestión de estados de cita (pendiente, confirmada, completada, cancelada).
- Recordatorios automáticos por correo o WhatsApp (según integración).

## Stack tecnológico

| Capa | Tecnología | Justificación |
|---|---|---|
| Frontend | React | Interfaz dinámica con componentes reutilizables |
| Backend | Node.js + Express | API liviana y escalable para un MVP funcional |
| Base de datos | PostgreSQL | Integridad y consistencia para datos clínicos y agendas |
| Autenticación | Firebase Auth o JWT | Seguridad y control de sesiones |
| Despliegue | Vercel/Netlify + Railway/Render | Configuración simple para publicar rápido |

## Arquitectura funcional

```text
Paciente Web/Mobile
				|
				v
	 Frontend (React)
				|
				v
API REST (Node + Express)
				|
				v
	PostgreSQL (citas, usuarios, disponibilidad)
```

## Flujo de usuario

1. El paciente se registra o inicia sesión.
2. Busca medico por especialidad y horario.
3. Selecciona fecha y franja disponible.
4. Confirma la cita y recibe notificación.
5. El medico visualiza cambios en su panel en tiempo real (o casi real).

---

## Roadmap por fases

| Fase | Alcance | Estado |
|---|---|---|
| Fase 1 | Identidad y perfiles (registro, login, roles) | En planificación |
| Fase 2 | Core de agendamiento (búsqueda, disponibilidad, reserva) | Pendiente |
| Fase 3 | Panel médico y notificaciones | Pendiente |
| Fase 4 | Frontend avanzado e integración | Pendiente |
| Fase 5 | Cierre, pruebas y despliegue | Pendiente |

## Instalación local

```bash
# 1) Clonar repositorio
git clone https://github.com/GustavoG-Corhuila/DocTrack-gestion-citas-medicas

# 2) Entrar al proyecto
cd DocTrack-gestion-citas-medicas
```

## Estructura del proyecto

```text
DocTrack-gestion-citas-medicas/
|-- frontend/
|   |-- src/
|   |-- public/
|-- backend/
|   |-- src/
|   |   |-- controllers/
|   |   |-- routes/
|   |   |-- services/
|   |   |-- models/
|   |-- config/
|-- docs/
|-- README.md
```

---

## Métricas objetivo

- Reducir no-shows al menos un 20% en 3 meses.
- Reducir conflictos de agenda (dobles citas) a casi 0.
- Ahorrar al menos 1 a 2 horas administrativas por semana en consultorios pequeños.

## Seguimiento del proyecto

- Ver Tablero Kanban del Proyecto: https://github.com/users/GustavoG-Corhuila/projects/1/

## Video de Presentación

https://drive.google.com/file/d/16tVT-tBkAlzWWv0wvhDftFVKup_6UKCL/view?usp=sharing

## Contribuciones

Las contribuciones son bienvenidas. Flujo recomendado:

1. Crea una rama desde main.
2. Implementa cambios pequeños y enfocados.
3. Abre un Pull Request con descripción clara y evidencia (capturas o pruebas).

## Sprint 1 — Plan
**Periodo:** 14 de abril de 2026 – 28 de abril de 2026 (2 semanas)

### Historias de Usuario seleccionadas:
1. **HU-01:** Registro de nuevos pacientes (Issue #1)
2. **HU-02:** Inicio de sesión seguro (Issue #2)
3. **HU-03:** Gestión de perfil del médico (Issue #3)
4. **HU-04:** Recuperación de contraseña (Issue #4)
5. **HU-05:** Validación de tarjeta profesional (Issue #5)

**Criterio de selección:** Se eligieron estas 5 historias porque corresponden a la **Épica 1: Gestión de Identidad**. Son la base fundamental del proyecto; sin un sistema de usuarios y perfiles válidos, no podemos avanzar con el agendamiento de citas.