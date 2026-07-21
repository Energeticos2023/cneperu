# ⚡ Comunidad Nacional de Electricistas del Perú (CNEP)

Sitio web oficial de la comunidad que integra a técnicos electricistas de todas las regiones del Perú.

**Aliado estratégico:** ENERGÉTICOS · **App:** [TecGo](https://energeticos2023.github.io/Yacusol-app/)

## Contenido
- 12 especialidades IIEE con videos de YouTube
- Videoteca del electricista (paneles solares, termas solares, carrera de electricidad y más)
- Álbum de obras reales
- Ficha de evaluación de nuevos socios (Titulados, Bachilleres y Empíricos) conectada a WhatsApp
- Directorio "Nuestra comunidad" con filtros por nivel y por región
- Cursos de capacitación

## Cómo publicar en GitHub Pages
1. Crear un repositorio nuevo (sugerido: `cnep-peru`).
2. Subir el archivo `index.html` (todo está incluido dentro: logo y fotos van incrustados).
3. Ir a **Settings → Pages → Branch: main → Save**.
4. En unos minutos la web estará en: `https://TU-USUARIO.github.io/cnep-peru/`

## ✏️ Cómo agregar socios al directorio
1. Abrir `index.html` en GitHub (botón del lápiz ✏️ para editar).
2. Buscar el texto: `LISTA DE SOCIOS DE LA COMUNIDAD` (Ctrl+F).
3. Copiar una línea de socio y cambiar los datos:
   ```js
   {nombre:"Nombre Apellidos", nivel:"Titulado", region:"Arequipa", ciudad:"Camaná", especialidad:"Sistemas Fotovoltaicos"},
   ```
   - `nivel` puede ser: `"Titulado"`, `"Bachiller"` o `"Empírico"`
   - `region` debe escribirse igual que en la lista oficial (ej. `"La Libertad"`, `"Áncash"`)
4. Borrar los socios de EJEMPLO cuando tengan los reales.
5. Guardar (Commit changes). La web se actualiza sola en 1-2 minutos.

## Contacto
- WhatsApp: 934 608 162
- Correo: tecnicos.electricistas.del.peru@gmail.com
- [Facebook](https://www.facebook.com/profile.php?id=61579692151327)
