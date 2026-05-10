Panel Web de Asignación Operativa — Tránsito Armenia

Aplicación web desarrollada para la Secretaría de Tránsito de Armenia, Quindío, utilizada en producción por agentes operativos para la asignación diaria de zonas de control vial.

Descripción

Herramienta interna que permite a los coordinadores de tránsito asignar agentes ATT-CPS a zonas específicas de la ciudad, registrar novedades de la jornada y generar reportes en PDF — todo desde el navegador, sin instalación ni dependencias externas.

Funcionalidades

- Control de acceso — sistema de autenticación por contraseña para uso interno
- Asignación de zonas — tabla editable con 13 zonas operativas de la ciudad
- Resumen automático — vista consolidada que se actualiza en tiempo real
- Registro de novedades — incapacidades, suspensiones, compensatorios y capacitaciones
- Persistencia local — los datos se guardan en el navegador con `localStorage`
- Exportación a PDF — generación de reporte oficial directamente desde el navegador
- Diseño responsivo — compatible con escritorio y dispositivos móviles

Tecnologías utilizadas

| Tecnología | Uso |

| HTML5 | Estructura de la aplicación |
| CSS3 | Estilos, diseño responsivo, variables CSS |
| JavaScript (Vanilla) | Lógica de negocio, DOM, eventos |
| localStorage API | Persistencia de datos en el navegador |
| Print API | Generación de reportes PDF |

Sin frameworks. Sin dependencias. Sin backend. Corre en cualquier navegador moderno.

Contexto del proyecto

Este proyecto nació de una necesidad real: los coordinadores de tránsito manejaban las asignaciones en papel o en archivos de Excel que no se sincronizaban entre dispositivos. La solución fue una herramienta web ligera, de acceso rápido desde cualquier dispositivo, que centraliza la información de la jornada y genera el reporte oficial en segundos.

Impacto: utilizada diariamente por el equipo operativo de tránsito de Armenia, Quindío, Colombia.

Mejoras futuras

Migrar persistencia a Firebase para sincronización en tiempo real entre dispositivos
Panel de historial de asignaciones por fecha
Autenticación por roles (coordinador / supervisor)
Notificaciones push para cambios de turno

Autor
Jairo Henao Hernandez
Estudiante de Ingeniería Electrónica — Universidad del Quindío
📧 jairohernandez753@gmail.com
📍 Armenia, Quindío, Colombia
