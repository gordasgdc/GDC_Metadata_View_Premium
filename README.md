**🌐 Limbă / Language / Idioma:** **Română** | [English](README.en.md) | [Español](README.es.md)

---

# GDC Metadata View Premium

**Analiză profesională a metadatelor pentru fișiere media**

## 📸 Capturi de ecran

*(adaugă aici capturi de ecran ale aplicației)*

## 🚀 Caracteristici

- ✅ Analiză 100% locală (privacy first) — niciun fișier nu părăsește browserul
- ✅ Comparație side-by-side pentru mai multe fișiere simultan
- ✅ Suport XML sidecar Sony (asociere automată cu clipul + extragere din XML embedat)
- ✅ Setări captură per-cadru (ISO, diafragmă, timp expunere, balans de alb — pistă rtmd)
- ✅ Analiză EXIF & GPS pentru imagini
- ✅ Tag-uri ID3v2 pentru fișiere audio MP3
- ✅ Filtrare și căutare avansată, cu evidențierea diferențelor
- ✅ Export PDF, CSV și JSON
- ✅ Suport multilingv (RO / EN / ES), cu preferința salvată local
- ✅ Tooltip-uri explicative pentru parametrii tehnici (Gamma, EI, ISO etc.)
- ✅ Fișiere demo — testează aplicația fără fișiere proprii
- ✅ Buton de **Ajutor** cu instrucțiuni integrate, accesibil de la tastatură

## 📖 Cum se folosește

1. **Încarcă fișierele** — trage-le în zona dedicată sau apasă pentru a le selecta
2. **Analizează** — metadatele sunt extrase automat și afișate în tabel
3. **Compară** — vezi diferențele evidențiate între fișiere
4. **Filtrează** — folosește căutarea pentru a găsi un parametru specific
5. **Exportă** — descarcă raportul în PDF, CSV sau JSON

Apasă butonul **Ajutor** din antetul aplicației pentru instrucțiuni detaliate, direct în interfață, în limba selectată.

## 📁 Suport fișiere

| Tip | Formate |
|-----|---------|
| Video | MP4, MOV, MXF |
| Audio | MP3, WAV, AIFF |
| Imagine | JPEG, PNG, HEIC, TIFF |
| XML | Sony sidecar (`.XML`) |

## 🔍 Metadate extrase

- **Video**: Codec, Rezoluție, FrameRate, Bitrate, Gamma, Log Profile, Exposure Index
- **Audio**: Codec, SampleRate, Canale, Bitrate
- **Imagine**: EXIF, GPS, Model cameră, Obiectiv, ISO, Timp expunere
- **XML Sony**: S-Log, S-Gamut, Culoare, EI

## 📤 Export

- **PDF**: Raport structurat, gata de print (A3 landscape), cu numele fișierului adaptat la limba selectată
- **CSV**: Pentru prelucrare în Excel/Numbers/Sheets
- **JSON**: Date brute, structurate, pentru integrare în alte fluxuri de lucru

## 💡 Scurtături tastatură

- `Ctrl+F` / `Cmd+F` — focalizează căutarea în tabel
- `Ctrl+Shift+H` / `Cmd+Shift+H` — ascunde/afișează rândurile identice

## 🛠️ Tehnologii utilizate

Aplicație de tip **Single Page Application (SPA)**, 100% HTML + CSS + JavaScript vanilla, într-un singur fișier `index.html` (fără build step, fără framework-uri), folosind:

- **HTML5 & CSS3 Vanilla** (interfață Dark UI)
- **[MediaInfo.js](https://github.com/emscripten-ports/MediaInfoLib)** – parsare container multimedia
- **[exifr](https://github.com/MikeKovarik/exifr)** – extragere metadate EXIF & GPS din imagini
- **[jsPDF](https://github.com/parallax/jsPDF)** & **[html2canvas](https://github.com/niklasvh/html2canvas)** – generare rapoarte PDF

## 👤 Autor

Proiect realizat și dezvoltat de **Cristi Gordas** (**GDC**).

- **GitHub:** [gordasgdc](https://github.com/gordasgdc)
- **Facebook:** [Cristi Gordas](https://www.facebook.com/cristiGDC)
- **YouTube:** [@cristigordas](https://www.youtube.com/@cristigordas)

## 📄 Licență

MIT License
