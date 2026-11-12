# EventosU – Modelo de amenazas
Tarea de modelado de amenazas de un sitio web en fase de diseño (EventosU, un sitio ficticio de la universidad para congresos, talleres y conciertos).

| Integrante               | Carnet   |
|--------------------------|----------|
| Ana Gabriela López Ortiz | 18002988 |

## Alcance
El modelo cubre el diseño de EventosU: el sitio web, la API, la base de datos, el almacenamiento de archivos, el login institucional con Microsoft Entra ID, la pasarela de pagos, el servicio de correo, la app de puerta y el panel de administración. Se analizan los cinco flujos principales: registro y login, inscripción, pago, ingreso y gestión. Quedan fuera la seguridad interna de los proveedores externos, los datos de tarjeta y el código fuente, que todavía no existe.

## Contenido
- `model/eventosu.json`: modelo de OWASP Threat Dragon.
- `docs/informe.pdf`: informe final.
- `docs/amenazas.csv`: tabla de amenazas exportada.

## Cómo abrir el modelo
1. Abrir OWASP Threat Dragon (versión de escritorio).
2. Elegir "Open an existing threat model".
3. Seleccionar el archivo `model/eventosu.json`.
