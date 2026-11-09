# Basic Fraud Investigation 

Bahan untuk peserta Risk Training & Workshop: deck pengajaran, seluruh bahan praktik, dan template laporan yang Anda pakai menulis hasil kerja dua hari.

Repositori ini berisi bahan peserta saja. Kunci jawaban, run sheet, checklist persiapan, dan bahan instruktur lainnya tidak ada di sini.

## Isi

| Folder | Isi |
|---|---|
| `deck/` | Deck pengajaran dua hari, dalam bahasa Indonesia dan bahasa Inggris |
| `lab_kit/` | Seluruh bahan praktik: brief tiap sesi, worksheet, dan dataset |
| `laporan/` | Template laporan investigasi dan laporan forensik, beserta contoh terisinya |

Folder di dalam `lab_kit/` bernomor menurut urutan sesinya pada agenda dua hari, dari `01_` sampai `08_`. Mulai dari `lab_kit/00_PETA_LAB_DAN_DECK.docx` kalau ingin tahu slide mana yang dipakai pada sesi mana.

## Sebelum hari pertama

Lab A memeriksa berkas media dari command line. Pasang tiga hal ini di laptop Anda dan pastikan ketiganya jalan:

```
ffprobe      (bagian dari ffmpeg)
exiftool
sha256sum    (coreutils; pada macOS: shasum -a 256)
```

Ketiganya gratis dan tidak memerlukan hak administrator pada sebagian besar sistem. Kalau pemasangannya diblokir kebijakan kantor, beri tahu instruktur sebelum hari pertama — ada jalan lain, tetapi perlu disiapkan.

## Cara memakai bahan lab

Seluruh bahan di `lab_kit/` berformat Word (.docx) supaya dapat langsung diisi dan diubah. Setiap folder lab dibuka dengan berkas `00_BRIEF_*.docx`. Di dalamnya ada tujuan sesi, jalannya lab menit per menit, apa yang dianggap selesai, dan apa yang dikumpulkan. Baca itu lebih dulu, baru buka worksheet-nya.

Dua hal yang berlaku di seluruh lab:

- Setiap dataset memuat kasus yang **sengaja tidak dapat disimpulkan**. Menuliskan "tidak dapat disimpulkan" beserta alasannya adalah jawaban yang benar, bukan kegagalan.
- Setiap worksheet meminta tingkat keyakinan dan **negative findings**. Keduanya wajib, bukan tambahan.

Keluaran hari 1 dipakai lagi di hari 2. Simpan semuanya.

## Tentang datanya

Seluruh dataset dan berkas media di sini **sintetis dan dibuat khusus untuk pelatihan**. Tidak ada data pengguna sungguhan, data korban, atau data produksi di dalamnya. Berkas media pada Lab A adalah pola uji yang dibangkitkan dengan ffmpeg, bukan rekaman wajah — ia melatih pembacaan container, metadata, hash, dan kesegaran sesi, bukan pemeriksaan visual.

Tidak ada demonstrasi serangan, tidak ada tools ofensif, dan tidak ada pembongkaran aplikasi di bahan mana pun.

## Lisensi

Materi pelatihan: CC BY-NC-SA 4.0 — lihat `LICENSE`. Pemakaian komersial memerlukan izin tertulis dari penyusun.

Disusun oleh Agus Supriyadi.
