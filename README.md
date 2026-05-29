# Backstage XV — Landing Page
> by Víctor Domínguez · Backstage Fotografía · Xalapa

---

## 📁 Estructura del repositorio

```
/
├── index.html          ← Landing page principal (NO editar estructura)
├── aviso-privacidad.html  ← Crear este archivo (texto simple)
└── assets/
    ├── logo.png            ← Logo Backstage (PNG con fondo transparente, ~200px alto)
    ├── hero.mp4            ← Video hero (autoplay muted, landscape, máx 15MB)
    ├── hero-poster.jpg     ← Imagen fallback del hero (1920×1080)
    ├── reel-poster.jpg     ← Thumbnail del reel (16:9)
    ├── avatar.mp4          ← Video vertical de Víctor (9:16, 35–60s)
    ├── avatar-poster.jpg   ← Thumbnail del avatar video (9:16)
    └── gallery/
        ├── g1.jpg          ← Foto vertical (tall) — imagen principal destacada
        ├── g2.jpg
        ├── g3.jpg
        ├── g4.jpg          ← Foto vertical (tall)
        ├── g5.jpg
        ├── g6.jpg
        ├── g7.jpg
        └── g8.jpg
```

---

## ✅ Checklist antes de publicar

### 1. Reemplaza tu número de WhatsApp
Busca en `index.html` todas las ocurrencias de:
```
529xxxxxxxxx
```
Y reemplaza con tu número completo (código país + lada + número):
```
5212281234567
```
*(México = 52, Xalapa lada = 228)*

### 2. Sube el logo
- Exporta `BK_LOGO_FINAL.jpg` como PNG con fondo transparente
- Nómbralo `logo.png` y ponlo en `/assets/`

### 3. Galería de fotos
- 8 imágenes: g1.jpg → g8.jpg en `/assets/gallery/`
- Resolución recomendada: 900×1200px (vertical 3:4)
- Peso máximo por foto: 300KB (comprimir en https://squoosh.app)

### 4. Video Hero
- Archivo: `assets/hero.mp4`
- Duración: 10–20 segundos en loop
- Resolución: 1920×1080 mínimo
- Peso: máximo 15MB (comprimir en https://handbrake.fr)
- Imagen poster: `assets/hero-poster.jpg` (misma resolución)

### 5. Reel
- **Opción A (YouTube):** En `index.html` busca `VIDEO_ID` y reemplaza con el ID de tu video de YouTube
- **Opción B (local):** Descomenta el bloque `<video>` y comenta el `<iframe>`

### 6. Video Avatar (Víctor)
- Archivo: `assets/avatar.mp4`
- Formato vertical 9:16 (como Instagram Reels)
- Duración: 35–60 segundos

### 7. Redes sociales en footer
Busca en `index.html`:
```
TU_USUARIO   ← tu @ de Instagram
TU_PAGINA    ← tu página de Facebook
```

### 8. Meta Pixel (cuando tengas campaña activa)
En `index.html`, al final del `<body>`, pega el código de Meta Pixel.
Luego descomenta la línea:
```javascript
// fbq('track', 'Lead');
```

---

## 🚀 Publicar con GitHub Pages

1. Crea repositorio en GitHub: `backstage-xv` (público)
2. Sube todos los archivos manteniendo la estructura de carpetas
3. Ve a **Settings → Pages → Branch: main → / (root)** → Save
4. Tu URL será: `https://TU-USUARIO.github.io/backstage-xv/`

## 🔗 URL corta con Bitly

1. Entra a https://bitly.com
2. Pega tu URL de GitHub Pages
3. Personaliza: `bit.ly/xv-backstage` o similar
4. Úsala en tus anuncios de Meta Ads

---

## 🎨 Paleta de colores (referencia)

| Variable       | Valor       |
|---------------|-------------|
| --black        | `#0a0a0a`   |
| --gold         | `#c9a96e`   |
| --gold-light   | `#e8d5a3`   |
| --champagne    | `#f2e8d5`   |
| --white        | `#f9f6f0`   |

---

*Backstage Fotografía · Historias que se sienten*
