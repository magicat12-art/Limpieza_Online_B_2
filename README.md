# Limpieza de áreas comunes · Edificio B Tepetlapa

- `index.html` es la página que ven los vecinos. Solo consulta, se actualiza sola cada pocos minutos.
- `admin.html` es la página donde tú editas, desde celular o computadora.
- `data.json` guarda los datos. El botón «Publicar cambios» lo actualiza por ti.

## Instalación (una sola vez)
1. En github.com crea un repositorio nuevo, por ejemplo `limpieza-edificio-b`.
2. **Add file → Upload files**: sube `index.html`, `admin.html`, `data.json` y este `README.md`. Confirma con **Commit changes**.
3. **Settings → Pages**: en *Build and deployment* elige **Deploy from a branch**, rama `main`, carpeta `/ (root)`. Guarda.
4. En uno o dos minutos GitHub muestra la dirección, algo como `https://TU-USUARIO.github.io/limpieza-edificio-b/`.
   - Vecinos: esa dirección.
   - Tú: esa dirección más `admin.html`. Guárdala en favoritos o en la pantalla de inicio del celular.

## Conectar tu celular y tu computadora (una vez en cada uno)
1. Abre `admin.html`. Se abre la pestaña **Publicación**.
2. Crea el token como indica esa pestaña (Contents: Read and write, solo para este repositorio).
3. Pega usuario, repositorio y token, y pulsa **Guardar y probar**.

## Uso diario
1. Abre `admin.html` y registra los pagos.
2. Pulsa **Publicar cambios**. En 1 o 2 minutos los vecinos ven la actualización.

## Seguridad
- Cualquiera puede abrir `admin.html`, pero sin tu token no puede publicar nada. Sus cambios solo existirían en su propio navegador.
- El token vive solo en tu dispositivo. Si lo pierdes, bórralo en GitHub (Settings → Developer settings → Personal access tokens) y crea otro.
- No agregues colaboradores al repositorio.
- Un repositorio público y su página los ve cualquiera con el enlace. Por eso la página pública muestra solo números de departamento y los nombres no están en `data.json`.
