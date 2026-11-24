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

## Segundo buzón director@caminosyecosdelarioja.com · versión celr-v11
- **Selector de buzón** en la sección Correo: *Todos / Contacto / Director* (se recuerda en ese dispositivo, aparte de los datos del mapa). La lista, la búsqueda, el filtro por municipio y los contadores de carpetas se filtran por el buzón elegido; en «Todos» cada correo lleva una etiqueta con su buzón. El número de no leídos de la barra superior es siempre la suma de los dos buzones, y el uso diario/mensual (100/3000) es compartido.
- **Hilos**: se indica a qué buzón pertenecen; la respuesta rápida sale por defecto de ese buzón y con su firma (se puede cambiar en «De»).
- **Redactar nuevo**: campo «De» (Contacto / Director). Por defecto el buzón seleccionado, o contacto si estás en «Todos». La firma cambia con el «De».
- **Ajustes**: elige el buzón para editar su nombre de remitente, firma y reenvío. La contraseña es común a los dos.
- **«📤 Enviar desde la app»** (antes «Enviar desde contacto@…») en fichas y en «Envíos»: la confirmación incluye «De»; los borradores de campaña salen por defecto desde contacto@, pero puedes elegir director@. El texto del borrador no cambia (lleva su propia firma).
- Si el servidor de correo aún no tuviera el segundo buzón, la app sigue funcionando como antes, solo con contacto@.

## Firmas de Director y Contacto · versión celr-v12
- **Borradores de campaña** (lotes, fichas, carta conjunta de Soto, reenganche de Ábalos y Agoncillo, mensajes a asociaciones): firmados por Daniel Torres Tear con **director@caminosyecosdelarioja.com** · 621 38 83 46. En los mensajes de Facebook, el contacto de Daniel también es director@. Los enlaces «✉️ Abrir en Proton / app de correo» llevan esa misma firma.
- **Contacto** firma como «Un cordial saludo, / Equipo de comunicación / Caminos y Ecos de La Rioja · Música y Patrimonio / contacto@caminosyecosdelarioja.com · 621 38 83 46».
- **«📤 Enviar desde la app»** en fichas y en «Envíos»: «De» es **Director** por defecto. Si eliges Contacto, el bloque de firma del texto cambia solo a «Equipo de comunicación · contacto@» (y vuelve a Daniel · director@ si eliges Director). Si el texto no lleva firma, no se añade ninguna.
- **Redactar nuevo y respuesta rápida**: si un buzón no tiene firma guardada en «Ajustes», se usa su firma predeterminada (Director: Daniel · director@; Contacto: Equipo de comunicación · contacto@). Si la tiene, se usa la guardada.
- Al abrir esta versión, los borradores que ya habías editado y guardado en el dispositivo cambian la firma antigua (Daniel con contacto@) por la de director@. Tus notas, lo marcado como enviado y el resto del texto no cambian.

## Número en el icono (correos no leídos) · versión celr-v13
- Con la app **instalada** (iPad: Añadir a pantalla de inicio; ordenador: Instalar en Chrome o Edge), el icono muestra el número de correos **no leídos de los dos buzones** (contacto@ y director@), aunque en la sección Correo estés viendo solo uno.
- El número se actualiza al abrir la app (si hay sesión), al refrescar la bandeja, al leer un correo, cada dos minutos mientras la app está abierta, y al volver a ella.
- **iPad (iPadOS 16.4 o posterior):** el número solo aparece si concedes el permiso de notificaciones. En **Ajustes** del correo hay un botón **«Activar número en el icono»** (en v14 pasa a «Activar avisos y número en el icono»). En el ordenador, con la app instalada en Chrome o Edge, suele bastar con eso.
- Con la app cerrada, el número se actualiza al volver a abrirla. Desde v14, si activas los avisos, también puede actualizarse cuando llega un correo nuevo.

## Avisos push y número en el icono · versión celr-v14
- En **Ajustes** del correo, el botón **«Activar avisos y número en el icono»** pide el permiso de notificaciones, registra el dispositivo en el servidor de correo y deja listo el aviso «Nuevo correo» (o el asunto que envíe el servidor) aunque la app esté cerrada. El estado visible puede ser «Avisos activados», «Permiso denegado», «No compatible (instala la app en el iPad)» o «Servidor aún sin avisos» si el servidor aún no responde. **«Desactivar avisos»** cancela el registro en este dispositivo.
- Si el permiso ya estaba concedido, al iniciar sesión la app vuelve a registrar el dispositivo en silencio, sin volver a pedir permiso. Al cerrar sesión se da de baja la suscripción.
- El icono sigue mostrando la suma de no leídos de Director y Contacto. Un aviso de solo número no muestra notificación (en el iPad, Safari exige un aviso visible; el servidor envía «Nuevo correo» a esos dispositivos). Pulsar el aviso abre la sección Correo. También puedes abrir la app con `#correo`.
- Abre la app instalada con conexión para recibir la actualización; no borres la app ni sus datos.

## Ventana de correo en paralelo · versión celr-v15
- En la cabecera de **Correo** aparece **«⧉ Abrir en ventana aparte»**. En el ordenador (Chrome o Edge, también con la app instalada) abre una ventana solo con el correo (bandeja, hilo, redactar, respuesta rápida, ajustes y selector de buzón), para tenerla al lado de la app mientras escribes o envías. Si la ventana ya estaba abierta, se reutiliza y se trae al frente. Si el navegador bloquea la ventana, se intenta en una pestaña nueva o se muestra un aviso.
- En esa ventana, **«Volver a la app»** enfoca la ventana principal o la abre. El título es «Correo · Caminos y Ecos».
- Lo que envíes o marques como leído en una ventana se refleja en la otra (bandeja, contadores y, si era un borrador de lote, el marcado de enviado en Envíos y en la ficha). Iniciar o cerrar sesión en una también se nota en la otra.
- En el diálogo **«📤 Enviar desde la app»** hay un enlace **«Abrir en la ventana de correo»**: pasa el borrador (para, asunto, texto, De, municipio) a la ventana despegada, abre Redactar ya relleno y, al enviarlo, el lote sigue quedando marcado como enviado. El botón de enviar de la ficha y de Envíos funciona igual que antes.
- **iPad:** una PWA instalada no puede abrir una segunda ventana propia (se iría a Safari, con otra sesión y otros datos). En el iPad, con la app en la pantalla de inicio, el botón no abre nada y avisa: «En iPad usa la vista dividida con Safari».
- Abre la app instalada con conexión para recibir la actualización; no borres la app ni sus datos.

## Cuatro buzones · versión celr-v16
- La app muestra todos los buzones que devuelve el servidor. Además de Contacto y Director, aparecen **Promoción** (promocion@) y **Producción** (produccion@). Si más adelante hay otros, salen también, con el identificador capitalizado si no tienen etiqueta propia.
- El selector, el «De» al redactar o responder, los ajustes y las etiquetas de cada fila cubren todos los buzones. En **Envíos**, el remitente por defecto sigue siendo Director (los borradores van firmados por Daniel).
- Si un mismo correo llega a varios buzones, en la vista **«Todos»** se agrupa en una sola fila con varias etiquetas.
- El número del icono suma los no leídos de todos los buzones. El aviso «Nuevo correo» indica el buzón (Contacto, Director, Promoción o Producción).
- Firmas predeterminadas (si el servidor no tiene una guardada): Director = Daniel Torres Tear · director@; Contacto = Equipo de comunicación · contacto@; Promoción = Equipo de promoción · promocion@; Producción = Equipo de producción · produccion@. Las de Promoción y Producción son provisionales.
- Abre la app instalada con conexión para recibir la actualización; no borres la app ni sus datos.

## Correos no leídos resaltados · versión celr-v17
- En la bandeja, los correos **recibidos y no leídos** tienen un fondo ámbar claro (**#FFF3D6**; en modo oscuro, un ámbar oscuro **#3D2A12**), un borde izquierdo grueso en el color de acento, el remitente y el asunto en negrita y un punto indicador. Si el hilo tiene varios no leídos, aparece el número.
- Los ya leídos y los enviados no se resaltan. Vale también en la ventana de solo correo (`?vista=correo`) y en la vista «Todos» (agrupada por resend_id).
- Al abrir un hilo, la fila pierde el resaltado al momento (también se sincroniza con la otra ventana). En el hilo puedes pulsar **«Marcar como no leído»** para volver a destacarlo en la lista.
- Abre la app instalada con conexión para recibir la actualización; no borres la app ni sus datos.

## Selección de correos y envío a la papelera · versión celr-v19
- En la bandeja de **Correo** cada fila tiene una casilla para **seleccionar el correo sin abrirlo**. Arriba hay «Seleccionar todo», el recuento y el botón **«🗑️ Enviar a la papelera»** (se activa al marcar alguno). No pide confirmación: el envío a la papelera se puede deshacer.
- Tras moverlos aparece el aviso («3 correos movidos a la papelera») con un enlace **Deshacer**, que los devuelve a la carpeta en la que estaban.
- En la **Papelera**, el mismo botón pasa a **«↩️ Devolver a Recibidos»**. No hay borrado definitivo por lotes (sigue estando solo al abrir un hilo).
- La selección se borra al cambiar de carpeta, de buzón o de búsqueda. Si un mismo correo aparece agrupado en «Todos» (varios buzones), se mueve en todos ellos.
- Las filas seleccionadas tienen un fondo azulado distinto del ámbar de los no leídos, y un borde derecho; si además están no leídas, se conservan el fondo cálido, el borde izquierdo y la negrita.
- Abre la app instalada con conexión para recibir la actualización; no borres la app ni sus datos.

## Seis buzones y colores · versión celr-v20
- Se añaden **Suscripción** (suscripcion@caminosyecosdelarioja.com) e **Info** (info@caminosyecosdelarioja.com), junto a Contacto, Director, Promoción y Producción. El selector, el «De», los ajustes, las etiquetas y los avisos cubren los seis. En **Envíos**, el remitente por defecto sigue siendo Director.
- Firmas predeterminadas de Suscripción e Info (provisionales): Equipo de suscripciones · suscripcion@; Equipo de información · info@.
- Cada buzón tiene un color de fondo en la lista, en el filtro de Buzón y en las etiquetas, con una leyenda debajo. Los no leídos mantienen el borde granate de 4 px, la negrita y el punto, con un tono más intenso del mismo color. La fila seleccionada se distingue por un borde y un velo, sin tapar el color del buzón. Si un mismo correo llega a varios, en «Todos» el fondo combina esos colores.
- Si el servidor aún no conoce los buzones nuevos, no aparecen en el selector; si faltan en las estadísticas, el recuento se muestra como 0 y la app no se interrumpe.
- Abre la app instalada con conexión para recibir la actualización; no borres la app ni sus datos.

## Listado de suscriptores · versión celr-v21
- En **Correo** hay un botón **«👥 Suscriptores»** (también en la ventana de solo correo). Muestra el total y los activos, se puede buscar, y filtrar por Activos, Bajas o Todos.
- La tabla incluye email, nombre, fecha de alta, origen y estado. **«Dar de baja»** pide confirmación y no borra el registro (pasa a Baja). **«⬇️ Exportar CSV»** descarga la lista filtrada (UTF-8 con BOM, separador «;»).
- **«✉️ Escribir a los activos»** abre el redactado desde suscripcion@, con las direcciones activas en **CCO**, y no envía nada hasta que confirmes. El campo CCO se ha añadido al redactado (el servidor ya lo admitía).
- Si aún no hay suscriptores: «Todavía no hay suscriptores. El formulario de la web se activará cuando se publique.» Si el servidor no tiene el listado, se muestra un aviso claro, sin interrumpir la app.
- Abre la app instalada con conexión para recibir la actualización; no borres la app ni sus datos.

## Boletín a suscriptores · versión celr-v22
- En **👥 Suscriptores**, el botón **«✉️ Escribir al boletín»** abre un redactado específico (sin Para ni CCO). Cada suscriptor recibe su propio correo, con su enlace de baja personal, que exige la LSSI y el RGPD.
- Debajo del texto aparece el **pie legal** (solo lectura), que el servidor añade automáticamente a cada envío. El enlace «darte de baja aquí» se ve como enlace, pero en la vista previa no da de baja a nadie.
- Botones: **«Comprobar cupo»** (no envía: muestra destinatarios y envíos que quedan hoy y este mes), **«Enviar prueba a un suscriptor»** (pide el email; solo llega a ese activo) y **«Enviar a los N activos»** (pide confirmación con el número; primero comprueba el cupo y, si se superaría, no envía). Nada se envía al abrir ni al guardar, ni si falta el asunto.
- Tras un envío se muestra el resultado (enviados y fallidos) y se abre la carpeta **Enviados** de suscripcion@. En Bajas, si el servidor informa la fecha, se ve «Baja el dd/mm/aaaa»; el CSV incluye la columna `unsubscribed_at`.
- El redactado normal (con campo CCO) no cambia.
- Abre la app instalada con conexión para recibir la actualización; no borres la app ni sus datos.

## Aviso legal en los correos · versión celr-v23
- En **Redactar nuevo**, **Responder** y el **boletín**, debajo de la firma de cada buzón se añade automáticamente un pie de **aviso legal** y **confidencialidad**, separado por una línea «——». Puedes editarlo antes de enviar.
- Al cambiar el «De», la firma y el aviso se sustituyen juntos, sin duplicarse. En las respuestas queda después de la firma y antes de la cita del mensaje original. En el boletín va debajo de «Equipo de suscripciones»; el pie de baja que añade el servidor no se modifica.
- Si el envío va en HTML (el boletín), los títulos «AVISO LEGAL.» y «CONFIDENCIALIDAD.» van en negrita y el bloque en gris, con letra algo menor.
- Abre la app instalada con conexión para recibir la actualización; no borres la app ni sus datos.

## Aviso legal en los borradores de Envíos · versión celr-v24
- Los **borradores de campaña** de la sección Envíos (ayuntamientos, asociaciones, carta de Soto, reenganche) llevan también el pie de **aviso legal** debajo de la firma, separado por «——», igual que al redactar desde Correo.
- Al cambiar el buzón, `cambiaFirma` sustituye la firma y deja el aviso una sola vez. Al copiar, abrir en Proton, enviar o pasar el borrador a la ventana de correo, no se duplica.
- Si tenías un borrador guardado sin el aviso, se añade solo al final y solo si falta; los mensajes de Facebook y las ediciones que no llevan firma no se tocan.
- Abre la app instalada con conexión para recibir la actualización; no borres la app ni sus datos.

## Eliminar definitivamente en la Papelera · versión celr-v25
- En la carpeta **Papelera** de Correo, al seleccionar correos con las casillas aparece el botón rojo **🗑️ Eliminar definitivamente**, junto a «Devolver a Recibidos».
- Pide confirmación («¿Eliminar definitivamente N correos? No se puede deshacer.») y borra esos mensajes para siempre con `DELETE /api/emails/<id>`. No hay Deshacer.
- Si una fila está agrupada (mismo correo en varios buzones), se borran todos sus identificadores. El botón se desactiva mientras borra, muestra el resultado, refresca la lista y los contadores, y limpia la selección.
- También hay **Vaciar papelera**, con su propia confirmación, para borrar todos los correos visibles de la papelera en el buzón o filtro actual.
- Fuera de la Papelera nada cambia.
- Abre la app instalada con conexión para recibir la actualización; no borres la app ni sus datos.

## Agenda de teléfonos, preferencia de envío y canal de WhatsApp · versión celr-v26
- Nueva sección **📇 Agenda** (distinta de la 📅 Agenda de fechas de la campaña): guarda contactos con nombre, teléfono, organización/pueblo, categoría (Ayuntamiento, Venue, Patrocinador, Festival, Músico, Prensa, Otro) y notas.
- El teléfono de 9 cifras se normaliza a +34. En cada ficha hay **📞 Llamar** (`tel:`) y **💬 WhatsApp** (`wa.me`). Se puede buscar, filtrar por categoría, editar y borrar (el borrado pide confirmación).
- **Exportar / importar CSV** propio de la agenda, y también va en el CSV general de la app (bloque `#agenda`). Se guarda en este navegador, junto al resto de datos; «Restablecer todo» también borra los contactos.
- En **👥 Suscriptores**, cada persona tiene preferencia de recepción (**Correo**, **WhatsApp** o **Ambos**, por defecto Correo) y un teléfono opcional, guardados en este dispositivo e indexados por email. Si el servidor ya trae canal o teléfono, se respeta y no se sobrescribe. Hay contadores Correo / WhatsApp / Ambos; el CSV incluye esas columnas.
- Ajuste **Enlace del Canal de WhatsApp**, también en este dispositivo (editable). El valor predeterminado es el canal de Caminos y Ecos: `https://whatsapp.com/channel/0029VbEQ1nMIN9iguGT5dz3H`. Debe empezar por `https://whatsapp.com/channel/` (también se admite `www.`). Si dejas el campo vacío y guardas, se restaura ese enlace.
- En **✉️ Escribir al boletín**, el botón **📢 Publicar en el canal** copia al portapapeles el asunto y el cuerpo en texto plano, **sin** el aviso legal del correo ni el pie de baja de email, y añade: «Para dejar de recibir estas publicaciones, pulsa “Dejar de seguir” en este canal.» Luego abre el enlace del canal. Si aún no está configurado, avisa. El envío por correo no cambia: llega a todos los activos; en esta versión no se filtra por preferencia (queda dicho en la confirmación y en el informe).
- Abre la app instalada con conexión para recibir la actualización; no borres la app ni sus datos.

## Tráfico de la web · versión celr-v27
- Nueva pestaña **📊 Tráfico**: visitas a la web del proyecto, con rango (7, 30 o 90 días, este año o fechas personalizadas).
- Tarjetas de totales: visitas, visitantes únicos (aprox.), altas del boletín en el rango (según los suscriptores de la app) y clics al canal de WhatsApp (suma de `whatsapp:seguir-canal`).
- Gráfico de líneas diario (SVG propio) y tablas con barras: países (nombre en español y bandera), comunidades de España (acepta código o nombre, p. ej. «La Rioja»), ciudades, pueblos y ciudades de La Rioja de origen, pueblos del ciclo (`pueblo:Nombre`; si no hay, avisa de que se registra al abrir un pueblo en la web), interacciones (programa, canal de WhatsApp, suscripciones, formulario, enlaces externos), páginas, fuentes (Google, Facebook, Instagram, WhatsApp, Boletín, Directo; la navegación interna se muestra aparte) y dispositivos (móvil, tablet, ordenador).
- **Exportar CSV** del rango elegido. Aviso: «Estadística propia sin cookies; la ubicación es aproximada (por la conexión).»
- Usa la misma sesión del correo que el resto de la app (`GET /api/stats?from=&to=`). Si el contador aún no está en el servidor, se muestra: «Aún no hay datos: el contador se activará en la web en breve», sin interrumpir el resto.
- Abre la app instalada con conexión para recibir la actualización; no borres la app ni sus datos.

## Séptimo buzón colaboradores@ · versión celr-v41
- Se añade **Colaboradores** (colaboradores@caminosyecosdelarioja.com), junto a Contacto, Director, Promoción, Producción, Suscripción e Info. El selector, el «De» al redactar o responder, los ajustes, las etiquetas, los colores, los avisos (push y Proton) y las respuestas automáticas de primera vez cubren los siete. En **Envíos**, el remitente por defecto sigue siendo Director.
- Firma predeterminada de Colaboradores: Daniel Torres Tear · colaboradores@caminosyecosdelarioja.com · 621 38 83 46. El color del buzón es un verde agua, distinto de los demás.
- Abre la app instalada con conexión para recibir la actualización; no borres la app ni sus datos.
