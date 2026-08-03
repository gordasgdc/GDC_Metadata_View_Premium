**🌐 Idioma / Language / Limbă:** [Română](README.md) | [English](README.en.md) | **Español**

---

# GDC Metadata View

**GDC Metadata View** es una aplicación web de nivel profesional, que se ejecuta directamente en el navegador (100% procesamiento local), diseñada para el análisis y la comparación detallada lado a lado de metadatos técnicos y de producción de archivos multimedia (video, audio, imágenes y XML adjunto de Sony).

La aplicación ahora tiene una interfaz disponible en **rumano, inglés y español**, con un selector de idioma (RO/EN/ES) en el encabezado. La preferencia de idioma se guarda localmente en el navegador (`localStorage`) y se recuerda en las próximas visitas.

---

## 🚀 Características principales

- **Análisis 100% local (privacidad primero):** Todos los archivos se procesan directamente en tu navegador. Ningún archivo multimedia se sube a servidores externos.
- **Comparación lado a lado:** Carga varios archivos a la vez para comparar los parámetros técnicos en una tabla dinámica.
- **Soporte de XML adjunto de Sony:** Asocia automáticamente los clips de video MP4/MOV de cámaras Sony con sus archivos `.XML` adjuntos (o extrae los metadatos XML directamente de los paquetes de muestra incrustados) para mostrar el perfil **Log / Gamma** (S-Log3, S-Gamut3.Cine, etc.), **Exposure Index (EI)**, **color**, y más.
- **Ajustes de captura por cuadro (pista RTMD):** Extrae del primer cuadro los parámetros reales del rodaje: **ISO, tiempo de exposición, diafragma (f-stop), balance de blancos**.
- **Análisis EXIF y GPS para imágenes:** Muestra el modelo de cámara, el objetivo, el tiempo de exposición, el ISO, la distancia focal y las coordenadas GPS exactas.
- **Etiquetas ID3v2 para audio:** Extrae el título, el artista, el álbum y el género musical de archivos MP3.
- **Filtrado y búsqueda avanzados:**
  - Resaltado automático de las diferencias entre archivos.
  - Ocultar filas idénticas para una inspección rápida.
  - Búsqueda instantánea por parámetro (ej: *Gamma, Codec, ISO, FrameRate*).
- **Interfaz multilingüe (RO / EN / ES):** Selector de idioma en el encabezado, con la preferencia guardada en `localStorage`.
- **Exportación de informes:**
  - **PDF:** Informe comparativo estructurado y estilizado automáticamente en una página A3 horizontal. El nombre del archivo incluye el idioma seleccionado (ej. `metadata_report_ES.pdf`).
  - **JSON:** Exportación estructurada de todos los datos extraídos para su procesamiento posterior (ej. `metadata_report_ES.json`).

---

## 🛠️ Tecnologías utilizadas

La aplicación está construida como una **Single Page Application (SPA)**, 100% HTML + CSS + JavaScript puro (sin frameworks), utilizando:

- **HTML5 y CSS3 puro** (interfaz moderna con estilo completo, tema Dark UI).
- **[MediaInfo.js](https://github.com/emscripten-ports/MediaInfoLib)** – análisis de contenedores multimedia.
- **[exifr](https://github.com/MikeKovarik/exifr)** – extracción de metadatos EXIF y GPS de imágenes.
- **[jsPDF](https://github.com/parallax/jsPDF)** y **[html2canvas](https://github.com/niklasvh/html2canvas)** – generación de informes PDF.

---

## 📖 Cómo se usa

1. **Abrir la aplicación:**
   - Haz doble clic en `index.html` para abrirla localmente, o visita el enlace generado por **GitHub Pages**.
2. **Elegir el idioma:**
   - Usa el selector **RO / EN / ES** del encabezado. La preferencia se guarda en tu navegador.
3. **Cargar los archivos:**
   - Arrastra (*drag & drop*) uno o varios archivos multimedia (video, audio, imagen, XML de Sony) a la zona indicada, o haz clic en el recuadro para seleccionarlos.
4. **Analizar y comparar:**
   - Los archivos aparecerán uno al lado del otro en la tabla.
   - Marca la opción **Resaltar diferencias** para detectar rápidamente las discrepancias.
   - Usa el cuadro de búsqueda para encontrar un parámetro específico.
5. **Exportar:**
   - Haz clic en **Exportar PDF** para descargar una ficha de inspección técnica (`metadata_report_ES.pdf`).
   - Haz clic en **Exportar JSON** para guardar los datos en bruto (`metadata_report_ES.json`).

---

## 👤 Autor

Proyecto creado y desarrollado por **Cristi Gordas** (**GDC**).

- **Facebook:** [Cristi Gordas](https://www.facebook.com/cristiGDC)
- **YouTube:** [@cristigordas](https://www.youtube.com/@cristigordas)
