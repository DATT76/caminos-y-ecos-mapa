# Mapa y agenda · Caminos y Ecos de La Rioja 2027

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
1. Crea un repositorio en GitHub (por ejemplo `celr2027`).
2. Sube el contenido de la carpeta (`index.html`, `manifest.webmanifest`, `sw.js`, `icons/`).
3. Ve a *Settings → Pages → Branch: main / (root) → Save*.
4. La app quedará en `https://TU_USUARIO.github.io/celr2027/`.

⚠️ **Privacidad:** la app contiene los contactos y los borradores, y quien tenga el enlace podrá verlos. Las anotaciones (estados y notas) no se suben a ningún sitio: se quedan en cada dispositivo. En GitHub Pages gratuito el repositorio es público; para que no aparezca en buscadores, usa Netlify o no compartas el enlace.

### Instalarla
- **Ordenador (Chrome o Edge):** abre la dirección https y pulsa el icono de instalar en la barra de direcciones (⊕ o pantalla con flecha), o *Menú ⋮ → Instalar Caminos y Ecos…*.
- **Android (Chrome):** abre la dirección, *Menú ⋮ → Instalar aplicación* (o *Añadir a pantalla de inicio*).
- **iPhone/iPad (Safari):** abre la dirección en Safari, pulsa *Compartir* (cuadrado con flecha) y luego *Añadir a pantalla de inicio*.

Una vez abierta la primera vez, la app funciona sin conexión.

### Importante
- Cada dispositivo guarda sus propios datos. Para pasar el seguimiento del ordenador al móvil, usa *Exportar CSV* y luego *Importar*.
- Si actualizas la app (subes una versión nueva), los datos guardados se mantienen mientras la dirección no cambie.
- *Copiar texto* usa el portapapeles. En el HTML abierto con doble clic, si el navegador no lo permite, el texto se selecciona para copiarlo con Ctrl+C.

Nada se envía automáticamente: los emails se copian y se envían a mano.
