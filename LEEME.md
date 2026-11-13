# Mapa y agenda · Caminos y Ecos de La Rioja

Sirve para cualquier año: arriba eliges la **edición** o creas una nueva, empezando todo en pendiente o copiando los estados de la edición actual. Cada edición tiene sus propios estados, fechas, notas y fases de agenda, que se generan según el año y se pueden editar; incluye un aviso opcional de elecciones municipales. Los contactos y el patrimonio son comunes a todas las ediciones, y cada ficha muestra el historial por año. Los borradores usan el año de la edición activa. El CSV lleva la columna `edicion`.

Dos formatos con el mismo contenido: 98 puntos (ayuntamientos, aldeas, asociaciones y Anguiano 2026), ficha editable, borradores de email y Facebook con botón de copiar, agenda de fases, alta de pueblos con un clic en el mapa, y exportación/importación en CSV.

## 1. Archivo único: `CaminosYEcos_Mapa.html`
- Doble clic y se abre en el navegador. Funciona sin internet porque todo va dentro del archivo.
- Los cambios se guardan en **ese navegador y en ese ordenador** (localStorage). Si abres el archivo en otro navegador o equipo, empezará vacío.
- **Copia de seguridad:** botón *Exportar CSV*. Para recuperarla, pega el CSV en el cuadro y pulsa *Importar CSV del cuadro*.
- El CSV se abre en Excel o LibreOffice (UTF-8, separado por comas).

## 2. App instalable (PWA): `CaminosYEcos_App.zip`
Una PWA solo se instala si se sirve por **https**. Primero hay que alojarla (es gratis):

### Alojarla gratis
**Opción A · Netlify Drop (la más fácil, sin cuenta técnica):**
1. Descomprime el zip.
2. Entra en https://app.netlify.com/drop.
3. Arrastra la carpeta `CaminosYEcos_App` a la página.
4. Te da una dirección `https://….netlify.app`. Crea una cuenta gratuita para que no caduque.

**Opción B · GitHub Pages:**
1. Crea un repositorio en GitHub (por ejemplo `caminos-y-ecos-mapa`).
2. Sube el contenido de la carpeta (`index.html`, `manifest.webmanifest`, `sw.js`, `icons/`).
3. Ve a *Settings → Pages → Branch: main / (root) → Save*.
4. La app quedará en `https://TU_USUARIO.github.io/caminos-y-ecos-mapa/`.

⚠️ **Privacidad:** la app contiene los contactos y los borradores, y quien tenga el enlace podrá verlos. Las anotaciones (estados y notas) no se suben a ningún sitio: se quedan en cada dispositivo. En GitHub Pages gratuito el repositorio es público; para que no aparezca en buscadores, usa Netlify o no compartas el enlace.

### Instalarla
- **Ordenador (Chrome o Edge):** abre la dirección https y pulsa el icono de instalar en la barra de direcciones (⊕ o pantalla con flecha), o *Menú ⋮ → Instalar Caminos y Ecos*.
- **Android (Chrome):** abre la dirección, *Menú ⋮ → Instalar aplicación* (o *Añadir a pantalla de inicio*).
- **iPhone/iPad (Safari):** abre la dirección en Safari, pulsa *Compartir* (cuadrado con flecha) y luego *Añadir a pantalla de inicio*.

Una vez abierta la primera vez, la app funciona sin conexión.

### Importante
- Cada dispositivo guarda sus propios datos. Para pasar el seguimiento del ordenador al móvil, usa *Exportar CSV* y luego *Importar*.
- Si actualizas la app (subes una versión nueva), los datos guardados se mantienen mientras la dirección no cambie.
- *Copiar texto* usa el portapapeles. En el HTML abierto con doble clic, si el navegador no lo permite, el texto se selecciona para copiarlo con Ctrl+C.

Nada se envía automáticamente: los emails se copian y se envían a mano.

## Enviar con un clic (Proton Mail)
Cada ficha con borrador tiene el botón **«✉️ Abrir en correo para enviar»**. Abre tu app de correo predeterminada con el destinatario, el CC si lo hay (carta de Soto), el asunto y el texto de la edición activa. **No envía nada**: revisas el email y pulsas Enviar tú. Los emails largos se copian además al portapapeles por si el cuerpo llega cortado. Después la app pregunta si quieres marcar la ficha como «email enviado» con la fecha de hoy. Si no hay email de destinatario, el botón aparece desactivado.

**Proton Mail como app de correo predeterminada**
- **iPad/iPhone:** instala la app *Proton Mail* desde el App Store e inicia sesión. Ve a *Ajustes › Apps › Proton Mail › App de correo predeterminada* (en versiones anteriores de iPadOS: *Ajustes › Proton Mail*) y elige Proton Mail. Si no aparece la opción, usa «Copiar texto» y pégalo en la app.
- **Windows:** instala la app de escritorio *Proton Mail* y ve a *Configuración › Aplicaciones › Aplicaciones predeterminadas*; busca «MAILTO» y elige Proton Mail.
- **macOS:** instala la app de escritorio *Proton Mail*; en la app *Mail › Ajustes › General › Lector de correo predeterminado* elige Proton Mail.
- Si usas Proton Mail solo en el navegador, puede que el enlace no lo abra: usa «Copiar texto».

## Pestaña «Envíos» y modo oscuro (v5)
- **Envíos** (por edición): lotes por día (Lote 1 lun 2 nov: 10 + 2 extra; reparto 3–13 nov) y lista «Esperan a resolver» con su motivo. Por cada correo: Para/CC, asunto, avisos, «Ver/editar borrador» (se guarda solo en la edición activa; «Restaurar original» recupera el texto), «✉️ Abrir en correo para enviar» (usa el texto editado y lo copia al portapapeles), casilla «enviado» con fecha (pone la ficha en «email enviado»), mover a otro día, quitar, y crear días nuevos. Desde cada ficha: «Añadir a lote» y enlaces a sus lotes.
- **Modo claro/oscuro**: botón 🌙/☀️ en la cabecera. Por defecto sigue el sistema; tu elección se recuerda en este navegador.

## Calendario reprogramado · versión celr-v9
Envíos del 11 al 22 de enero de 2027; llamadas de seguimiento desde el 25 de enero. Al actualizar se trasladan también los lotes guardados de la edición 2027, sin cambiar enviados, borradores editados ni notas. Abre con conexión para recibir la actualización; no borres la app ni sus datos.

## Correo contacto@caminosyecosdelarioja.com · versión celr-v10
- **Sección «📬 Correo»** (accesible desde la barra superior, con el número de no leídos): inicia sesión con la contraseña del webmail del proyecto. Si aún no existe, primero hay que crearla en https://celr-mail.caminosyecosdelarioja.workers.dev/setup. Dentro: uso de hoy y del mes (límites 100/3000), carpetas (Recibidos, Enviados, Destacados, Archivados, Papelera, Todos), búsqueda y filtro por municipio, lectura de hilos con adjuntos, destacar, archivar, papelera, marcar no leído, vincular un hilo a un municipio y verlo en el mapa, respuesta rápida, «Redactar nuevo» y «Ajustes» (nombre del remitente, reenvío, firma y cambio de contraseña).
- **«📤 Enviar desde contacto@…»** en cada ficha y en cada fila de «Envíos»: muestra antes una confirmación con remitente, destinatarios (si hay varios emails puedes elegir), asunto, avisos y texto. Al confirmarse el envío, el correo queda marcado como enviado en el lote y la ficha pasa a «email enviado» con la fecha de hoy. Si no has iniciado sesión, te lleva a la sección Correo y, al entrar, vuelve a abrir la confirmación: el borrador no se pierde.
- **«✉️ Abrir en Proton / app de correo»** sigue disponible como alternativa (no envía nada por sí solo).
- La sesión del correo se guarda solo en ese dispositivo, aparte de los datos del mapa: no se incluye al exportar el CSV ni se borra con «Restablecer todo». «Cerrar sesión» la elimina.
