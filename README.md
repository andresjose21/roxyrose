# 🌹 Roxyrose — Sitio Web Oficial

**Portal estilo Link.me + Portafolio premium para la modelo de IA más glamurosa del universo digital.**

![Roxyrose](https://picsum.photos/id/1011/1200/630)

## ✨ Características

- **Diseño ultra elegante** con tema rose-gold y animaciones sutiles
- **Galería interactiva** con masonry layout, filtros (Fotos / Videos / Todas) y lightbox
- **Modal de subida** con drag & drop para previsualizar tus propias imágenes y videos localmente
- **Servicios premium** con precios y descripciones listas para usar
- **Sección de Enlaces** estilo Linktree con todos tus perfiles sociales
- **Formulario de contacto** funcional (demo)
- **Totalmente responsive** y optimizado para móviles
- **100% estático** — funciona perfecto en GitHub Pages

## 🚀 Cómo alojar en GitHub Pages (gratis)

1. Ve a tu repositorio: **https://github.com/andresjose21/roxyrose**
2. Ve a **Settings → Pages**
3. En "Build and deployment" selecciona:
   - Source: **Deploy from a branch**
   - Branch: **main** / **(root)**
4. ¡Listo! Tu sitio estará en: **https://andresjose21.github.io/roxyrose**

(El primer deploy puede tardar 1-2 minutos)

## 📸 Cómo agregar tus propias fotos y videos de Roxyrose

### Opción 1: Usar el modal de subida (recomendado para probar)
- Abre el sitio
- Haz clic en **"Subir"** o **"Agregar más fotos y videos"**
- Arrastra tus archivos o haz clic en la zona
- ¡Se previsualizan inmediatamente en tu galería!

### Opción 2: Agregar permanentemente al repositorio (recomendado)

1. Crea la carpeta `assets/images` en el repositorio
2. Sube tus fotos (`.jpg`, `.png`) y videos (`.mp4`) allí
3. Edita el archivo `index.html`:
   - Busca la sección `galleryItems` (línea ~280)
   - Agrega nuevos objetos al array:
     ```js
     { 
       id: 9, 
       type: 'photo', 
       src: './assets/images/tu-foto.jpg', 
       caption: 'Tu nuevo caption aquí', 
       category: 'Editorial' 
     }
     ```
4. Para videos:
   ```js
   { 
     id: 10, 
     type: 'video', 
     src: './assets/images/tu-video.mp4', 
     poster: './assets/images/video-poster.jpg',
     caption: 'Detrás de cámaras', 
     category: 'Video' 
   }
   ```
5. Haz commit y push → ¡Listo!

> **Tip**: Las imágenes generadas por Grok Imagine que usé de ejemplo están en `/home/workdir/artifacts/imagine_images/` (puedes descargarlas y subirlas).

## 🎨 Personalización rápida

- Cambia el nombre, bio y precios en el HTML directamente
- Actualiza los enlaces de redes sociales en la sección `#enlaces`
- Cambia los colores editando las clases `rose-500`, `pink-600` y `--rose-gold`
- Agrega tu logo real reemplazando el ícono de rosa

## 📞 Soporte

¿Quieres que:
- Agregue más imágenes reales de Roxyrose?
- Cambie el diseño?
- Agregue una tienda / pagos?
- Integre con OnlyFans o Patreon?

Solo dime y lo actualizo en segundos.

---

**Hecho con ❤️ por Grok para Jose Andres**  
*Tu modelo de IA favorita está lista para conquistar el mundo.* 🌹

**Demo en vivo:** https://andresjose21.github.io/roxyrose (después de activar Pages)