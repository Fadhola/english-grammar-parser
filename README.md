# Parser — Belajar Tata Bahasa Inggris

Website frontend interaktif untuk belajar tata bahasa Inggris dari nol. Bongkar setiap kata, lihat perannya, lalu uji pemahaman lewat latihan.

**Live:** https://english-grammar-parser-pi.vercel.app

## Fitur

- **Parser interaktif** — klik kata mana pun di kalimat, lihat part of speech-nya (10 warna konsisten).
- **Materi lengkap** — Part of Speech (10 jenis), Struktur Kalimat, Frasa, Klausa, dan Grammar (12 tenses, agreement, modal, voice, conditional, reported speech).
- **Latihan** — 24 soal: tebak part of speech, klasifikasi kalimat, pilih tense, cocokkan conditional, flip card active↔passive. Progres tersimpan di browser (localStorage).
- **Responsive** — mobile-first, bottom nav di layar kecil, top nav di desktop, scrollspy aktif.

## Stack

Satu file `index.html` — HTML + CSS + vanilla JS, tanpa build step. Buka langsung atau serve statis.

Font: Space Grotesk (display), Newsreader (body), JetBrains Mono (formula).

## Jalankan lokal

```bash
python -m http.server 8000
# buka http://localhost:8000
```

Atau cukup klik-dobel `index.html`.

## Deploy

Terhubung ke Vercel — push ke `main` otomatis deploy ke produksi.
