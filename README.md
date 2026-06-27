# LafleuParser — Belajar Tata Bahasa Inggris

Website frontend interaktif untuk belajar tata bahasa Inggris dari nol. Bongkar setiap kalimat, lihat peran tiap kata, lalu uji pemahaman lewat latihan.

> **Parse** = membedah kalimat jadi bagian-bagiannya (subjek, verb, objek, klausa). LafleuParser = *si pembedah kalimat*.

**Live:** https://lafleuparser.vercel.app

## Fitur

- **Parser interaktif** — klik kata mana pun, lihat part of speech-nya (10 warna konsisten) + anatomi kalimat (Subject/Verb/Object/Complement/Adverbial, bilingual).
- **Materi lengkap** — Part of Speech, Struktur Kalimat, Frasa, Klausa, Grammar (12 tenses, agreement, modal, voice, conditional, reported speech, there is/are, gerund vs infinitive, articles, relative clauses, prepositions, punctuation).
- **Vocabulary** — bedah essay, collocations, phrasal verbs, linking words, idioms, expressions, dan **word bank TOEFL/IELTS** (132 kata) dengan status hafalan (Belum/Lagi belajar/Tahu) + filter.
- **Latihan** — 34 soal, progres tersimpan di browser (localStorage).
- **UX** — reading progress bar, rail mini-map (desktop), sub-index, responsive mobile-first.

## Stack

Satu file `index.html` — HTML + CSS + vanilla JS, tanpa build step. Font: Space Grotesk (display), Newsreader (body), JetBrains Mono (formula).

## Jalankan lokal

```bash
python -m http.server 8000
# buka http://localhost:8000
```

Atau klik-dobel `index.html`.

## Deploy

Terhubung ke Vercel — push ke `main` otomatis deploy ke produksi.
