# ETHOS Perinatal (PWA)

Herramienta **docente** de apoyo a emergencias obstetricas (hemorragia posparto/Codigo Rojo,
sindrome hipertensivo del embarazo y sepsis obstetrica). **Borrador en validacion** — no reemplaza
el juicio clinico ni constituye un protocolo aprobado.

## Publicar en GitHub Pages
1. Crear un repositorio publico llamado `ethos-perinatal`.
2. Subir estos archivos a la raiz: `index.html`, `manifest.json`, `sw.js`, `icono-192.png`, `icono-512.png`.
3. En el repo: Settings -> Pages -> Source: "Deploy from a branch" -> Branch: `main` / carpeta `/ (root)` -> Save.
4. Esperar 1-2 min. La URL queda como: `https://<usuario>.github.io/ethos-perinatal/`

## Instalar en el telefono (como app)
- **iPhone (Safari):** abrir la URL -> boton Compartir -> "Agregar a pantalla de inicio".
- **Android (Chrome):** abrir la URL -> menu -> "Instalar app" / "Agregar a pantalla de inicio".
- Abrir una vez **con internet**; despues funciona **sin conexion**.

## Actualizar la app
Al cambiar `index.html`, subir el numero de version del cache en `sw.js`
(`ethos-perinatal-v0_1` -> `-v0_2`...) para que los telefonos tomen la version nueva.
