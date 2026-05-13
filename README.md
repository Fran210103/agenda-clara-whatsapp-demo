# Agenda Clara WhatsApp Demo

Demo interactiva para mostrar a peluquerias como funcionaria una recepcion por WhatsApp que responde consultas frecuentes y deja solicitudes de reserva listas para confirmar.

## Demo para cliente

Cuando GitHub Pages este activo, la demo publica deberia quedar en:

```text
https://fran210103.github.io/agenda-clara-whatsapp-demo/
```

La version publicada funciona en modo demo, sin backend local. El cliente puede probar el chat, pedir una hora y ver como se registra una solicitud en el panel interno.

## Que muestra

- Chat simulado con tono de recepcion.
- Respuestas sobre precios, horario y ubicacion.
- Flujo de reserva con nombre, servicio, dia, horario y telefono.
- Panel interno con reservas pendientes, confirmadas o cerradas.
- Copia de resumen y descarga CSV.
- Ficha editable del salon para personalizar la conversacion durante la demo.

## Alcance del MVP

Esta version no envia mensajes reales por WhatsApp. Sirve para mostrar el flujo, validar interes comercial y explicar el producto antes de conectar WhatsApp Business API, calendario o CRM.

## Desarrollo local

Para usar solo la demo visual, abre `index.html` en el navegador.

Para probar con el backend local del asistente:

```bash
cd ../whatsapp-reservas-api
npm start
```

Luego abre `index.html` desde el proyecto `whatsapp-reservas-demo` o sirve estos archivos desde un entorno local.

## Siguiente paso tecnico

- Conectar WhatsApp Business API o Meta Cloud API.
- Registrar reservas en Google Sheets, Notion o CRM.
- Revisar disponibilidad contra Google Calendar.
- Agregar mensajes de recordatorio y seguimiento.
