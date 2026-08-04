**🌐 Language / Limbă / Idioma:** [Română](README.md) | **English** | [Español](README.es.md)

---

# GDC Metadata View Premium

**Professional metadata analysis for media files**

## 📸 Screenshots

*(add app screenshots here)*

## 🚀 Key Features

- ✅ 100% local analysis (privacy first) — no file ever leaves your browser
- ✅ Side-by-side comparison of multiple files at once
- ✅ Sony sidecar XML support (auto-matched with the clip + extraction from embedded XML)
- ✅ Per-frame capture settings (ISO, aperture, exposure time, white balance — rtmd track)
- ✅ EXIF & GPS analysis for images
- ✅ ID3v2 tags for MP3 audio files
- ✅ Advanced filtering and search, with differences highlighted
- ✅ PDF, CSV and JSON export
- ✅ Multilingual interface (RO / EN / ES), with the preference saved locally
- ✅ Explanatory tooltips for technical parameters (Gamma, EI, ISO, etc.)
- ✅ Demo files — try the app without your own files
- ✅ **Help** button with built-in instructions, keyboard accessible

## 📖 How to Use

1. **Load your files** — drag them into the drop zone or click to select them
2. **Analyze** — metadata is extracted automatically and shown in the table
3. **Compare** — see the differences highlighted between files
4. **Filter** — use search to find a specific parameter
5. **Export** — download the report as PDF, CSV or JSON

Click the **Help** button in the app header for detailed instructions, right inside the interface, in your selected language.

## 📁 File Support

| Type | Formats |
|------|---------|
| Video | MP4, MOV, MXF |
| Audio | MP3, WAV, AIFF |
| Image | JPEG, PNG, HEIC, TIFF |
| XML | Sony sidecar (`.XML`) |

## 🔍 Metadata We Extract

- **Video**: Codec, Resolution, FrameRate, Bitrate, Gamma, Log Profile, Exposure Index
- **Audio**: Codec, SampleRate, Channels, Bitrate
- **Image**: EXIF, GPS, Camera model, Lens, ISO, Exposure time
- **Sony XML**: S-Log, S-Gamut, Color, EI

## 📤 Export

- **PDF**: Structured, print-ready report (A3 landscape), with the filename matching the selected language
- **CSV**: For processing in Excel/Numbers/Sheets
- **JSON**: Structured raw data for integration into other workflows

## 💡 Keyboard Shortcuts

- `Ctrl+F` / `Cmd+F` — focus the table search box
- `Ctrl+Shift+H` / `Cmd+Shift+H` — show/hide identical rows

## 🛠️ Technologies Used

Built as a **Single Page Application (SPA)**, 100% vanilla HTML + CSS + JavaScript in a single `index.html` file (no build step, no frameworks), using:

- **Vanilla HTML5 & CSS3** (Dark UI theme)
- **[MediaInfo.js](https://github.com/emscripten-ports/MediaInfoLib)** – multimedia container parsing
- **[exifr](https://github.com/MikeKovarik/exifr)** – EXIF & GPS metadata extraction from images
- **[jsPDF](https://github.com/parallax/jsPDF)** & **[html2canvas](https://github.com/niklasvh/html2canvas)** – PDF report generation

## 👤 Author

Project created and developed by **Cristi Gordas** (**GDC**).

- **GitHub:** [gordasgdc](https://github.com/gordasgdc)
- **Facebook:** [Cristi Gordas](https://www.facebook.com/cristiGDC)
- **YouTube:** [@cristigordas](https://www.youtube.com/@cristigordas)

## 📄 License

MIT License
