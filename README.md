# Turnos al Calendario

Tu roster de turnos, directo en tu calendario. Pegás el horario como te lo
pasen — foto del papel pegado en la pared, planilla compartida, códigos tipo
`M / T / N` — y salen los eventos listos para tu calendario.

## Qué hace

- **Definís tus turnos una sola vez:** cada código del roster con su horario
  (Mañana, Tarde, Noche, Libre...). Si la salida es menor que la entrada, el
  turno cruza la medianoche. Podés agregar, editar y quitar turnos.
- **Pegás el roster como venga:** líneas con día y código (`3 M`, `12/12 N`),
  horarios sueltos (`5: 07-15`) o la fila corrida de códigos (`M T N L L M…`)
  que se reparte desde el día 1.
- **O leés la foto del roster:** el texto se lee con OCR en tu propio
  teléfono y cae en la caja para que lo revises antes de generar nada.
  (Necesita internet la primera vez para cargar el lector de fotos.)
- **Revisás y corregís en un calendario mensual:** tocás un día para
  cambiarle el turno, y ves cuántos turnos, cuántas horas, cuántas noches y
  cuántos días libres tiene el mes.
- **Descargás el `.ics`** para importar en Google Calendar, Apple Calendar y
  Outlook, o agregás cada turno a Google Calendar con un clic.

Todo se procesa en tu propio navegador. Nada sale de tu teléfono, no hay
cuentas, no hay servidores, no se guarda nada.

## Cómo usarla

1. Abrí la página (o descargá este repo y abrí `index.html`).
2. En el Paso 1, dejá tus códigos con sus horarios.
3. En el Paso 2, elegí el mes y pegá el roster, o subí la foto.
4. Tocá **Pasar al calendario**, revisá el mes y corregí tocando los días.
5. Descargá el `.ics` o agregá los turnos uno por uno a Google Calendar.

## Publicarla en GitHub Pages

1. Creá un repositorio público en GitHub (por ejemplo `turnos-al-calendario`)
   y subí estos archivos a la raíz.
2. En el repo, andá a **Settings → Pages**.
3. En **Build and deployment → Source**, elegí **Deploy from a branch**,
   rama `main`, carpeta `/ (root)`.
4. Guardá y esperá un minuto: la página queda en
   `https://TU-USUARIO.github.io/turnos-al-calendario/`.

No hay nada que compilar: es una sola página estática (`index.html`).

## El plan freemium (idea, no promesa)

Uso gratis para todos. Pro a **$3–5 USD/mes por persona (precio supuesto)**:
sincronización directa con Google Calendar (sin descargar archivos, con
actualización automática si el roster cambia), rosters ilimitados y avisos
cuando cambia un turno ya cargado. Nadie fue citado diciendo «pagaría X» por
esta herramienta; el precio es una inferencia a partir del precio real de
Cellendar ($7,99/mes), la herramienta más parecida, que solo sincroniza
planillas limpias y no lee fotos ni rosters desordenados.

## Licencia

MIT — ver `LICENSE`.
