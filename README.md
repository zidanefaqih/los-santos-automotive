# Los Santos Automotive

Marketplace jual-beli mobil berbasis web — TUBES mata kuliah **Implementasi dan Pengujian Perangkat Lunak (CAK3AAB3)**, Program Studi Informatika, Telkom University.

**Kelompok 8**
- Fikri Ahmad Zidane (2211102336)
- Ananda Tegar Pratama Saulaka (2211102356)

## Ringkasan Aplikasi

Pengguna (user) dapat mencari mobil, memasukkan ke keranjang, melakukan checkout dengan pembayaran simulasi (menghitung kembalian), lalu mencetak struk/invoice. Pengguna juga dapat memasang iklan mobil untuk dijual. Admin bertugas memverifikasi iklan dan mengelola pengguna.

## Tech Stack

| Bagian | Teknologi |
|---|---|
| Bahasa/Framework | JavaScript — Node.js + Express |
| UI / IMK | EJS + Bootstrap 5 |
| Database | PostgreSQL (Docker Compose) |
| ORM | Prisma |
| Testing | Jest |
| Tools | GitHub, Trello, VS Code |

## Struktur Repositori

```
docs/
├── 01-rencana-konstruksi/   Tugas #1 — rencana konstruksi (docx + html)
├── 02-skpl/                 SKPL v1.0 (md, docx, pdf, diagram)
└── 03-dppl/                 DPPL (diagram desain; dokumen menyusul)
src/                         (menyusul) kode aplikasi
```

## Dokumentasi

- **SKPL** — `docs/02-skpl/SKPL-Los-Santos-Automotive.pdf` — 10 halaman: kebutuhan fungsional/non-fungsional, use case, ERD, kamus data
- **DPPL** — `docs/03-dppl/` — class diagram + sequence diagram (checkout, login, pasang iklan); dokumen lengkap menyusul
- **Rencana Konstruksi** — `docs/01-rencana-konstruksi/` — tabel rencana per minggu (M3–M15)
- **Progress board** — Trello: https://trello.com/b/RkDauRKl/los-santos-automotive

## Alur Inti

1. **Pembeli** — cari mobil → keranjang → checkout → input uang bayar → struk + kembalian → cetak
2. **Penjual** — pasang iklan → menunggu verifikasi admin → iklan tampil di katalog
3. **Admin** — verifikasi iklan → kelola pengguna

## Status Pengerjaan

- [x] Tugas #1 — Rencana Konstruksi PL
- [x] Tugas #2 — Akun & repositori GitHub kelompok
- [x] SKPL v1.0
- [ ] DPPL (target 4 Okt 2026)
- [ ] Implementasi IMK
- [ ] Implementasi Basis Data
- [ ] Generate code (class & sequence diagram)
- [ ] Defensive coding & refactoring
- [ ] Unit testing & DUPL / UAT
- [ ] OO Metric & presentasi TUBES
