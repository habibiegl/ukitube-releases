# UkiTube — YouTube Research & Content Strategy Toolkit
> Senjata rahasia YouTuber Indonesia untuk meledakkan views, subscriber, dan dominasi niche.

---

## Kenapa UkiTube?

YouTube bukan lagi soal "upload dan berharap". Kompetitor yang sukses punya **data**, punya **strategi**, punya **tools**. UkiTube memberikan semua itu dalam satu aplikasi desktop — tanpa langganan bulanan, tanpa batasan.

---

## 10 Fitur Utama

---

### 1. Dashboard Multi-Channel

**Pantau hingga 50 channel sekaligus dalam satu layar.**

- Masukkan handle atau URL channel (bisa paste banyak sekaligus)
- Data real-time: subscriber, total views, video count, video trending
- **Channel Health Score** (0-100) — skor kesehatan channel berdasarkan 4 metrik:
  - Efisiensi views per video
  - Produktivitas upload
  - Pertumbuhan subscriber
  - View-to-subscriber ratio
- **Evaluasi AI per channel** — kekuatan, kelemahan, peluang, dan action plan 90 hari
- Auto-refresh setiap 5 menit
- Import dari file `.txt`
- Sorting per kolom (klik header)
**Gunanya:** Monitor kompetitor, track progress channel sendiri, temukan channel yang patut ditiru.

---

### 2. Radar Trending

**Deteksi channel baru yang meledak di trending YouTube.**

- Multi-kategori fetch otomatis (Musik, Hiburan, Gaming, Pendidikan, Blog & Orang)
- 100-200+ video trending dari 40+ negara
- **Preset Filter:**
  - **Semua** — semua video trending tanpa filter
  - **Rising Star** — channel < 1 tahun, ATM > 50
  - **Breakout** — channel < 6 bulan, ATM > 70, VPH > 500
- **Badge otomatis:**
  - 💎 Channel Baru — umur < 6 bulan, subs < 10K
  - 🔥 VPH Tinggi — views per hour > 500
  - 🚀 ATM Tinggi — opportunity score > 70
  - ⚡ Breakout — kombinasi ketiganya
- Auto-refresh (15/30/60 menit)
- Historical tracking 7 hari
- Filter Shorts (hanya video long-form)
**Gunanya:** Temukan niche yang sedang naik SEBELUM kompetitor tahu. Channel baru yang meledak = peluang emas untuk ditiru.

---

### 3. Keyword Radar

**Analisis keyword YouTube dengan data real.**

- **YouTube Suggestions API** — ambil keyword yang benar-benar dicari user
- **3-level expansion** — dari 1 keyword jadi 50+ keyword unik
- **Data real per keyword:**
  - Estimasi volume pencarian (dari median views top 20 video)
  - Kompetisi score (dari avg subscriber channel top performers)
  - Difficulty (Low/Medium/High)
  - SEO Score (0-100)
  - **Trend Indicator** — View Share Method, bukan VPH biasa
- **AI Niche Blueprint** — strategi otomatis berdasarkan data
- **AI Idea per keyword** — judul, thumbnail hook, 5 detik pertama
- Filter by difficulty, sort by volume/competition/score/trend
- Export CSV
**Gunanya:** Riset keyword yang grounded in data real, bukan tebakan. Tahu persis keyword mana yang worth dibidik.

---

### 4. Video Scout

**Cari dan bedah video berdasarkan keyword.**

- Search YouTube dengan filter mendalam:
  - Max subscriber (temukan channel kecil yang berhasil)
  - Min views
  - Upload date (hari ini/minggu/bulan/tahun)
  - Durasi (pendek/sedang/panjang)
  - Kategori (16 kategori)
  - Negara (200+ negara)
- **Metrik per video:**
  - **VPH** (Views Per Hour) — kecepatan views sejak upload
  - **ATM Score** (0-100) — composite opportunity score
  - Engagement rate
  - Tags video (klik untuk lihat semua + copy)
  - Channel age
- **Status auto-tagging:**
  - 🔥 Trending — channel kecil, video viral cepat
  - 🚀 Rekomendasi — views melebihi subs
  - 💬 Diminati — engagement tinggi
  - 🌿 Evergreen — video lama, views konsisten
  - ⚡ Viral — 100K+ views dalam 7 hari
  - 💎 Underrated — views tinggi, subs sedikit
  - 📱 Short Viral — short video meledak
- **Mini Sparkline Chart** — visual VPH per video
- **ATM Tooltip** — hover untuk detail breakdown skor
- **Video Compare** — pilih 2-3 video, bandingkan side-by-side
- **Filter by Status** — klik badge untuk filter
- Pagination "Cari Lebih Dalam"
- Export CSV (14 kolom)
**Gunanya:** Temukan celah pasar. Video dari channel kecil yang meledak = pola yang bisa ditiru.

---

### 5. Spy & Tools

**Bedah strategi kompetitor secara menyeluruh.**

#### Spy Video
- Masukkan URL video → bedah lengkap:
  - Info: judul, deskripsi, upload date + jam, views, likes
  - Thumbnail HD (download resolusi penuh)
  - Hidden tags (lihat + copy semua)
  - **AI Script Summary** — ringkasan naskah dari transcript via Gemini

#### Spy Channel
- Masukkan URL/handle channel → analisis mendalam:
  - **Ambil SEMUA video** dari channel (tanpa batas, pagination)
  - **5 Analytics Panel:**
    - **Channel Stats Summary** — subs, avg views, engagement, upload/bulan, avg durasi
    - **Best Upload Time** — hari & jam terbaik untuk upload
    - **Top Tags Frequency** — tag paling sering dipakai kompetitor
    - **Duration Strategy** — durasi video mana yang paling berhasil
    - **Title Patterns** — kata kunci & frase populer di judul
  - **Engagement Distribution** — distribusi engagement rate
  - Views Distribution Chart (Recharts)
  - **AI Pattern Analysis** — pola kesuksesan + rekomendasi judul baru
  - Filter: Views, Terbaru, Engagement, Trending (VPH)
  - Copy tags per video
  - Export PDF
**Gunanya:** Tahu persis apa yang dilakukan kompetitor yang berhasil — kapan upload, pakai tag apa, durasi berapa, judul seperti apa.

---

### 6. Simulator Thumbnail

**A/B testing thumbnail dengan skor berbasis data real.**

- Upload hingga 3 variasi thumbnail
- Preview realistis di mockup YouTube (mobile & desktop)
- **3-Layer Scoring System:**
  - **Layer 1: Visual Quality (30%)** — Canvas API pixel analysis
    - Brightness, contrast, saturation
    - Face detection, text detection
  - **Layer 2: Benchmark (40%)** — perbandingan dengan top performers
    - Ambil thumbnail video viral untuk topik sama
    - Hitung similarity score
  - **Layer 3: AI Quality (30%)** — Gemini Vision analysis
    - Emotional impact, visual clarity, text readability
    - Color impact, title synergy
- **Composite Score** (0-100) dengan interpretasi:
  - 85-100: Excellent
  - 70-84: Good
  - 50-69: Average
  - 30-49: Below Average
  - 0-29: Needs Work
- Detail breakdown per layer
- Ranking otomatis V1/V2/V3
**Gunanya:** Tahu thumbnail mana yang paling menarik SEBELUM upload. Bukan tebakan — berdasarkan data visual real + benchmark YouTube.

---

### 7. AI Focus Group

**Simulasi reaksi 5 persona penonton terhadap ide video.**

Input: ide video + deskripsi thumbnail + kategori.

5 persona AI yang masing-masing memberikan reaksi unik:
1. **Si Haters** — skeptis, kritis tajam
2. **Si Fans Berat** — antusias, loyal
3. **Si Kritis** — analis konten
4. **Si Bocil** — suka viral, bahasa gaul
5. **Si Emak-Emak** — cari manfaat praktis

**Gunanya:** Dapat feedback beragam tanpa perlu survey sungguhan. Tahu reaksi berbeda-beda dari tipe penonton yang berbeda.

---

### 8. Generator AI SEO

**Generate metadata SEO lengkap berdasarkan data real YouTube.**

#### Single SEO
1. **Benchmark real YouTube** — ambil data top 20 video untuk topik sama
2. **Channel benchmark** — cari channel dengan ATM Score aman untuk ditiru
3. **Generate dengan konteks data real:**
   - 5 variasi judul (masing-masing dengan SEO score, karakter count, angle)
   - Deskripsi 300+ kata (SEO score, word count, keyword density)
   - 25+ tags (score per tag, type: short-tail/mid-tail/long-tail)
   - 5 hashtag (score per hashtag)
   - 2 konsep thumbnail (prediksi CTR)
4. **Bahasa fleksibel** — pilih bahasa output dari dropdown (50+ bahasa)

#### Bulk Kalender
- Roadmap konten 30 hari (10 ide video berkaitan)

#### Post Komunitas
- 5 ide Community Tab (poll, Q&A, teaser, BTS, giveaway)
**Gunanya:** Generate metadata SEO yang bukan karangan — berdasarkan data video yang sudah terbukti berhasil.

---

### 9. Riwayat Riset

**Log semua aktivitas riset.**

- Simpan otomatis setiap riset
- Filter: Semua / Favorit (bookmark)
- Search dalam riwayat
- Buka kembali hasil riset sebelumnya
- Tipe: keyword, ai-gen, ai-bulk, ai-community

**Gunanya:** Tidak perlu riset ulang. Semua hasil tersimpan dan bisa diakses kapan saja.

---

### 10. Pengaturan & Keamanan

- Konfigurasi API keys (YouTube, Gemini)
- Template deskripsi default
- Info versi & status auto-update
- **Sistem keamanan berlapis:**
  - HMAC-SHA256 license verification
  - HWID binding (composite fingerprint)
  - Encrypted storage (AES-256-GCM)
  - Anti-tampering (DevTools disabled production)
  - CSP headers
  - IPC sender validation
- **Auto-Update** — cek versi otomatis via GitHub Releases, download & silent install

---

## Ringkasan Fitur

| # | Fitur | Data | AI |
|---|---|---|---|
| 1 | Dashboard Multi-Channel | YouTube API | Gemini |
| 2 | Radar Trending | YouTube API | — |
| 3 | Keyword Radar | YouTube API | Gemini |
| 4 | Video Scout | YouTube API | — |
| 5 | Spy & Tools | YouTube API | Gemini |
| 6 | Simulator Thumbnail | Canvas API | Gemini Vision |
| 7 | AI Focus Group | — | Gemini |
| 8 | Generator AI SEO | YouTube API | Gemini |
| 9 | Riwayat Riset | SQLite | — |
| 10 | Pengaturan & Keamanan | — | — |

---

## Yang Kamu Butuhkan

| # | API Key | Fungsi | Wajib? |
|---|---|---|---|
| 1 | **YouTube Data API v3** | Semua fitur riset | Ya |
| 2 | **Google Gemini AI** | Semua fitur AI | Ya |

Kedua API key **gratis**. Panduan lengkap tersedia di dalam aplikasi.

---

## Siapa yang Butuh UkiTube?

- **YouTuber Pemula** — mulai dengan strategi yang tepat, bukan coba-coba
- **YouTuber Menengah** — meledak dari ribuan ke ratusan ribu subscriber
- **YouTuber Pro** — tetap di depan kompetitor dengan data-driven decisions
- **Agensi/Team** — kelola banyak channel klien sekaligus

---

## Minat?

### Harga

| Paket | Harga |
|---|---|
| **Bulanan** | Rp 80.000 |
| **Lifetime** (Selamanya) | Rp 250.000 |

### Cara Pembayaran

Transfer ke salah satu rekening berikut:

| Metode | Atas Nama | Nomor Rekening |
|---|---|---|
| **BNI** | RIZKY WILDAN HABIBIE | 1831249692 |
| **DANA** | RIZKY WILDAN HABIBIE | 081252225088 |
| **SEABANK** | RIZKY WILDAN HABIBIE | 9017 3351 3323 |

Setelah transfer, kirim bukti pembayaran ke **WhatsApp 081252225088** atau **Telegram** untuk mendapatkan kode lisensi.

---

## Hubungi

Telegram: **[@ukilats](https://t.me/ukilats)**

---

**© 2026 UkiTube Team**

---

## Preview Aplikasi

<img src="https://raw.githubusercontent.com/habibiegl/ukitube-releases/master/Ukitube.PNG" alt="UkiTube Dashboard" width="100%">

<img src="https://raw.githubusercontent.com/habibiegl/ukitube-releases/master/Ukitube 1.PNG" alt="Dashboard Multi-Channel" width="100%">

<img src="https://raw.githubusercontent.com/habibiegl/ukitube-releases/master/Ukitube 2.PNG" alt="Radar Trending" width="100%">

<img src="https://raw.githubusercontent.com/habibiegl/ukitube-releases/master/Ukitube 3.PNG" alt="Keyword Radar" width="100%">

<img src="https://raw.githubusercontent.com/habibiegl/ukitube-releases/master/Ukitube 4.PNG" alt="Video Scout" width="100%">

<img src="https://raw.githubusercontent.com/habibiegl/ukitube-releases/master/Ukitube 5.PNG" alt="Spy & Tools" width="100%">

<img src="https://raw.githubusercontent.com/habibiegl/ukitube-releases/master/Ukitube 6.PNG" alt="Simulator Thumbnail" width="100%">

<img src="https://raw.githubusercontent.com/habibiegl/ukitube-releases/master/1.PNG" alt="Generator AI SEO" width="100%">