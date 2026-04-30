# 🦷 Dra. Genesis Garcia — PWA Dental

Portafolio web progresivo (PWA) para la Dra. Genesis Garcia, con agenda de citas integrada.

## 📁 Archivos incluidos

| Archivo | Descripción |
|---------|-------------|
| `index.html` | Página principal completa |
| `manifest.json` | Configuración PWA (instalable) |
| `sw.js` | Service Worker (soporte offline) |

## 🚀 Cómo publicar en GitHub Pages

1. Crea un repositorio en GitHub (ej: `dra-genesis`)
2. Sube los 3 archivos al repositorio
3. Ve a **Settings → Pages → Source: main branch / root**
4. La PWA estará disponible en `https://tuusuario.github.io/dra-genesis`

## 📱 Cómo hacerla instalable (íconos)

Necesitas añadir dos imágenes:
- `icon-192.png` — 192×192 px, logo o diente estilizado
- `icon-512.png` — 512×512 px, misma imagen en mayor resolución

Puedes crearlas gratis en: https://realfavicongenerator.net

## ✏️ Personalización rápida

En `index.html` busca y reemplaza:

| Texto a buscar | Reemplazar por |
|----------------|---------------|
| `Calle Principal #12, Santiago, RD` | Dirección real |
| `+1 (809) 000-0000` | Teléfono real |
| `contacto@dragenesis.com` | Email real |
| `Cédula Prof. 00000` | Número real de colegiatura |

## 📋 Secciones de la PWA

- **Inicio (Hero)** — Presentación con estadísticas
- **Servicios** — 6 servicios con íconos y descripciones
- **Sobre mí** — Perfil y logros académicos
- **Testimonios** — 3 reseñas de pacientes
- **Agendar cita** — Formulario completo con modal de confirmación
- **Footer** — Contacto y redes sociales

## 🔧 Próximas mejoras posibles

- Integrar Firebase para guardar citas en base de datos
- Conectar WhatsApp Business API para confirmar citas automáticamente
- Añadir galería de antes/después
- Panel de administración para la Dra. (ver citas del día)
