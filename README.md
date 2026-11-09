# Ejercicio de gestión de agenda y coordinación de reuniones

> **Ejercicio de práctica con datos ficticios.** Los equipos, fechas y horarios son inventados. No corresponde a experiencia laboral real.

## Descripción

Simulación de la coordinación de **cinco reuniones** entre equipos ubicados en distintos países (Colombia, Estados Unidos, México y España). El objetivo es practicar la organización de agendas, el manejo de zonas horarias y la documentación de confirmaciones y cambios.

## Contenido

| Archivo | Descripción |
|---|---|
| `Ejercicio_Gestion_de_Agenda.xlsx` | Libro de Excel con la agenda, la disponibilidad de cada equipo, las zonas horarias y el registro de movimientos |

### Hojas del libro

- **Resumen:** objetivo, herramientas utilizadas y resultado (indicadores calculados con fórmulas).
- **Agenda:** las cinco reuniones, con la hora convertida a la zona de cada equipo y una verificación automática de su horario disponible.
- **Disponibilidad:** horario laboral local de cada equipo.
- **Zonas:** diferencia horaria (UTC) de cada ciudad.
- **Registro:** solicitudes, confirmaciones, recordatorios y cambios de horario.

## Objetivo

Coordinar reuniones entre equipos de distintos países, detectar conflictos de horario, reprogramar cuando es necesario y dejar todo documentado.

## Herramientas

- Microsoft Excel: fórmulas (`INDEX`, `MATCH`, `MOD`, `IF`), listas desplegables y formato condicional.

## Resultado

- 5 reuniones coordinadas: 3 confirmadas, 1 reprogramada y 1 pendiente de confirmación.
- 1 conflicto de horario detectado (una reunión caía a las 21:00 en Madrid) y resuelto reprogramando.
- 0 conflictos de horario sin resolver.

## Cómo usarlo

1. Descarga `Ejercicio_Gestion_de_Agenda.xlsx` y ábrelo en Excel.
2. Empieza por la hoja **Resumen** y luego revisa **Agenda** y **Registro**.
3. El texto en azul son datos editables; el texto en negro son fórmulas. Si cambias la hora de una reunión, la verificación de horarios se actualiza sola.

## Supuestos

- Diferencias horarias de noviembre de 2026: Bogotá UTC-5, Nueva York UTC-5, Ciudad de México UTC-6, Madrid UTC+1. Antes de usarlo en un caso real, verifica el horario de verano de cada país.

## Autora

Ana Camila Sánchez Góngora · Estudiante de Ingeniería de Sistemas, Universidad de Ibagué
