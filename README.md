# Clínica Dra. Poveda Odontología — Landing de demostración

Landing de una sola página (`index.html`, HTML/CSS/JS inline) para la **Clínica Dra. Poveda Odontología**, clínica dental en **Zapote, San José, Costa Rica**.

Pieza central: **agenda de turnos en línea** que arma el mensaje de WhatsApp con el día, la hora, el tipo de consulta y los datos del paciente, más una sección de recordatorios (maqueta visual) y los servicios de la clínica.

## Contenido

- `index.html` — página autocontenida (CSS y JS inline, diseño mobile first).
- `img/` — fotografías (Unsplash, uso libre) recomprimidas con PIL: `hero.jpg`, `consultorio.jpg`, `consulta.jpg`.
- `Dockerfile` — `FROM nginx:alpine` + `COPY . /usr/share/nginx/html`.

## Datos de contacto

- WhatsApp: **+506 7193 0777** → `https://wa.me/50671930777`
- Ubicación: Zapote, San José, Costa Rica

## Notas

- El turno agendado **queda sujeto a confirmación de la clínica**.
- La demo **no envía mensajes** a nadie: solo arma el texto y abre WhatsApp.
- Horario de la agenda: lunes a viernes, 8:00 a.m. a 5:00 p.m., con el bloque de almuerzo (12:00–1:00 p.m.) fuera.

## Despliegue

Servido como app estática en EasyPanel (proyecto `clientes`, servicio `demo-clinicapoveda`).

---

Demo de referencia hecho por Nocodeveloper.
