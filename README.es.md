**🌐 Idioma / Language / Limbă:** [Română](README.md) | [English](README.en.md) | **Español**

---

# GDC Metadata View Premium

**Análisis profesional de metadatos para archivos multimedia**

## 📸 Capturas de pantalla

*(añade aquí capturas de pantalla de la aplicación)*

## 🚀 Características principales

- ✅ Análisis 100% local (privacidad primero) — ningún archivo sale de tu navegador
- ✅ Comparación lado a lado de varios archivos a la vez
- ✅ Soporte de XML adjunto de Sony (asociado automáticamente con el clip + extracción del XML incrustado)
- ✅ Ajustes de captura por cuadro (ISO, diafragma, tiempo de exposición, balance de blancos — pista rtmd)
- ✅ Análisis EXIF y GPS para imágenes
- ✅ Etiquetas ID3v2 para archivos de audio MP3
- ✅ Filtrado y búsqueda avanzados, con las diferencias resaltadas
- ✅ Exportación en PDF, CSV y JSON
- ✅ Interfaz multilingüe (RO / EN / ES), con la preferencia guardada localmente
- ✅ Tooltips explicativos para los parámetros técnicos (Gamma, EI, ISO, etc.)
- ✅ Archivos demo — prueba la aplicación sin tus propios archivos
- ✅ Botón de **Ayuda** con instrucciones integradas, accesible por teclado

## 📖 Cómo se usa

1. **Carga tus archivos** — arrástralos a la zona indicada o haz clic para seleccionarlos
2. **Analiza** — los metadatos se extraen automáticamente y se muestran en la tabla
3. **Compara** — observa las diferencias resaltadas entre archivos
4. **Filtra** — usa la búsqueda para encontrar un parámetro específico
5. **Exporta** — descarga el informe en PDF, CSV o JSON

Haz clic en el botón **Ayuda** del encabezado de la aplicación para ver instrucciones detalladas, directamente en la interfaz, en el idioma seleccionado.

## 📁 Formatos compatibles

| Tipo | Formatos |
|------|----------|
| Video | MP4, MOV, MXF |
| Audio | MP3, WAV, AIFF |
| Imagen | JPEG, PNG, HEIC, TIFF |
| XML | Sony sidecar (`.XML`) |

## 🔍 Metadatos que extraemos

- **Video**: Códec, Resolución, FrameRate, Bitrate, Gamma, Log Profile, Exposure Index
- **Audio**: Códec, SampleRate, Canales, Bitrate
- **Imagen**: EXIF, GPS, Modelo de cámara, Objetivo, ISO, Tiempo de exposición
- **XML Sony**: S-Log, S-Gamut, Color, EI

## 📤 Exportar

- **PDF**: Informe estructurado, listo para imprimir (A3 horizontal), con el nombre de archivo según el idioma seleccionado
- **CSV**: Para procesar en Excel/Numbers/Sheets
- **JSON**: Datos en bruto y estructurados para integrarlos en otros flujos de trabajo

## 💡 Atajos de teclado

- `Ctrl+F` / `Cmd+F` — enfoca el cuadro de búsqueda de la tabla
- `Ctrl+Shift+H` / `Cmd+Shift+H` — muestra/oculta las filas idénticas

## 🛠️ Tecnologías utilizadas

Aplicación construida como una **Single Page Application (SPA)**, 100% HTML + CSS + JavaScript puro en un único archivo `index.html` (sin proceso de compilación, sin frameworks), utilizando:

- **HTML5 y CSS3 puro** (tema Dark UI)
- **[MediaInfo.js](https://github.com/emscripten-ports/MediaInfoLib)** – análisis de contenedores multimedia
- **[exifr](https://github.com/MikeKovarik/exifr)** – extracción de metadatos EXIF y GPS de imágenes
- **[jsPDF](https://github.com/parallax/jsPDF)** y **[html2canvas](https://github.com/niklasvh/html2canvas)** – generación de informes PDF

## 👤 Autor

Proyecto creado y desarrollado por **Cristi Gordas** (**GDC**).

- **GitHub:** [gordasgdc](https://github.com/gordasgdc)
- **Facebook:** [Cristi Gordas](https://www.facebook.com/cristiGDC)
- **YouTube:** [@cristigordas](https://www.youtube.com/@cristigordas)

## 📄 Licencia

Licencia MIT
