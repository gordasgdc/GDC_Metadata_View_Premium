**🌐 Limbă / Language / Idioma:** **Română** | [English](README.en.md) | [Español](README.es.md)

---

# GDC Metadata View

**GDC Metadata View** este o aplicație web de nivel profesional, rulată direct în browser (100% procesare locală), destinată analizei și comparației detaliate side-by-side a metadatelor tehnice și de producție pentru fișiere media (video, audio, imagini și XML sidecar Sony).

Aplicația are acum interfață disponibilă în **română, engleză și spaniolă**, cu un selector de limbă (RO/EN/ES) în antet. Preferința de limbă este salvată local în browser (`localStorage`) și este reținută la vizitele următoare.

---

## 🚀 Caracteristici principale

- **Analiză 100% Locală (Privacy First):** Toate fișierele sunt procesate direct în browser-ul tău. Niciun fișier media nu este încărcat pe servere externe.
- **Comparație Side-by-Side:** Încarcă mai multe fișiere simultan pentru a compara parametrii tehnici într-un tabel dinamic.
- **Suport XML Sidecar Sony:** Asociază automat clipurile video MP4/MOV de la camerele Sony cu fișierele lor `.XML` de tip sidecar (sau extrage metadatele XML direct din pachetele eșantion embedate) pentru a afișa profilul **Log / Gamma** (S-Log3, S-Gamut3.Cine etc.), **Exposure Index (EI)**, **Culoare**, etc.
- **Setări Captură per-cadru (Pistă RTMD):** Extrage din primul cadru parametrii reali din teren: **ISO, Timp de expunere, Diafragmă (f-stop), Balans de alb**.
- **Analiză EXIF & GPS pentru Imagini:** Afișează modelul camerei, obiectivul, timpul de expunere, ISO, distanța focală și coordonatele GPS exacte.
- **Tag-uri ID3v2 pentru Audio:** Extrage titlul, artistul, albumul și genul muzical pentru fișiere MP3.
- **Filtrare și Căutare Avansată:**
  - Evidențiere automată a diferențelor între fișiere.
  - Ascundere rânduri identice pentru o inspecție rapidă.
  - Căutare instantanee după parametri (ex: *Gamma, Codec, ISO, FrameRate*).
- **Interfață multilingvă (RO / EN / ES):** Selector de limbă în antet, cu preferința salvată în `localStorage`.
- **Export Rapoarte:**
  - **PDF:** Raport comparativ structurat și stilizat automat pe pagină A3 landscape. Numele fișierului include limba selectată (ex. `metadata_report_RO.pdf`).
  - **JSON:** Export structurat al tuturor datelor extrase pentru procesare ulterioară (ex. `metadata_report_RO.json`).

---

## 🛠️ Tehnologii Utilizate

Aplicația este construită ca o aplicație **Single Page Application (SPA)**, 100% HTML + CSS + JavaScript vanilla (fără framework-uri), utilizând:

- **HTML5 & CSS3 Vanilla** (interfață modernă cu stilizare completă, temă Dark UI).
- **[MediaInfo.js](https://github.com/emscripten-ports/MediaInfoLib)** – parsare container multimedia.
- **[exifr](https://github.com/MikeKovarik/exifr)** – extragere metadate EXIF & GPS din imagini.
- **[jsPDF](https://github.com/parallax/jsPDF)** & **[html2canvas](https://github.com/niklasvh/html2canvas)** – generare rapoarte PDF.

---

## 📖 Cum se folosește

1. **Deschiderea aplicației:**
   - Deschide fișierul prin dublu click pe `index.html` sau accesează link-ul generat prin **GitHub Pages**.
2. **Alegerea limbii:**
   - Folosește selectorul **RO / EN / ES** din antet. Preferința rămâne salvată în browser.
3. **Încărcarea fișierelor:**
   - Trage (*drag & drop*) unul sau mai multe fișiere media (video, audio, imagini, XML Sony) în zona dedicată sau apasă pe casetă pentru a le selecta.
4. **Analiză & Comparație:**
   - Fișierele vor apărea alăturate în tabel.
   - Bifează opțiunea **Evidențiază diferențele** pentru a observa rapid neconcordanțele.
   - Folosește căsuța de căutare pentru a găsi un parametru specific.
5. **Export:**
   - Apasă pe **Exportă PDF** pentru a descărca o fișă de inspecție tehnică (`metadata_report_RO.pdf`).
   - Apasă pe **Exportă JSON** pentru a salva datele brute (`metadata_report_RO.json`).

---

## 👤 Autor

Proiect realizat și dezvoltat de **Cristi Gordas** (**GDC**).

- **Facebook:** [Cristi Gordas](https://www.facebook.com/cristiGDC)
- **YouTube:** [@cristigordas](https://www.youtube.com/@cristigordas)
