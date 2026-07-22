# 📺 StreamHub

Player de TV online gratuito con canales en vivo y en directo.

## 🌐 Ver online
**[→ Abrir StreamHub](https://Claudio-Barrios-83.github.io/StreamHub/)**

## 📋 Lista M3U (para Kodi, VLC, TiviMate)
```
https://raw.githubusercontent.com/Claudio-Barrios-83/StreamHub/refs/heads/main/streamhub-completa.m3u
```

## 📁 Estructura
```
StreamHub/
├── categorias/          # JSON de canales por categoría
├── canales-script/      # Listas consolidadas (TVLIBRE, Pluto, etc.)
├── listas/              # Índice de playlists para el player
├── web-url/             # Fuentes externas de streams
├── peliculas/           # JSON de películas
├── logos/               # Logos de canales (PNG)
├── .github/workflows/   # Automatización
└── streamhub-completa.m3u  # Lista M3U generada automáticamente
```

## ⚙️ GitHub Actions
| Workflow | Frecuencia | Función |
|---|---|---|
| validar-canales | Cada 12h | Verifica canales activos/inactivos |
| actualizar-pluto | Cada 6h | Actualiza canales de Pluto TV |
| generar-m3u | En cada push | Genera la lista M3U completa |
| ~~rotar-tokens~~ | — | Deshabilitado (listas M3U antiguas ya no existen) |

## 📊 Canales disponibles
- ⚽ Deportes (90+)
- 🌍 Mundial 2026
- 🎬 Cine y Series
- 📰 Noticias
- 👶 Infantil
- 🎵 Música
- 🌐 Canales Internacionales
- 🏙️ Buenos Aires
- Y más...
"# StreamHub" 
