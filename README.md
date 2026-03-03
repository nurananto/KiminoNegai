# Kimi no Negai ga Kanau made

> Minto Shishido, seorang siswa SMA yang mengaku playboy, tiba-tiba diisolasi bersama seluruh teman sekelasnya di sebuah fasilitas yang mirip sekolah saat sedang study tour.Tempat itu adalah ruang tertutup yang dibuat oleh suara misterius—'Tak bisa keluar sampai semua keinginan terpenuhi.'Dan lebih jauh lagi, tubuh seluruh murid mulai mengalami perubahan aneh!?

---

## Info

| | |
|---|---|
| Judul | Kimi no Negai ga Kanau made |
| Judul Alternatif | きみの願いが叶うまで |
| Author | Asazuki Norito |
| Tipe | Manga (Hitam Putih) |
| Genre | Seinen · Gender Bender · Drama · Comedy · Romance · School Life · Slice of Life |

## Link

- [MangaDex](https://mangadex.org/title/90d81edd-accb-4c8d-b44c-e38254d77935/kimi-no-negai-ga-kanau-made)
- [Raw](https://comic-walker.com/detail/KC_006693_S)

---

## Struktur

```
KiminoNegai/
├── manga-config.json     # Metadata manga
├── manga.json            # Data chapter (auto-generated)
├── manga-automation.js   # Script automation
├── encrypt-manifest.js   # Script enkripsi manifest
├── daily-views.json      # Data views harian
└── <chapter>/
    └── manifest.json     # Daftar halaman (encrypted)
```

## Automation

Semua proses berjalan otomatis via GitHub Actions:

1. Push chapter baru (folder + manifest.json)
2. `encrypt-manifest.yml` — enkripsi manifest
3. `manga-automation.yml` — regenerate manga.json
4. Trigger rebuild ke website utama
5. `sync-cover.yml` — sinkronisasi cover dari website

---

Bagian dari [Nurananto Scanlation](https://nuranantoscans.my.id)