# AGENTS.md — cerivitas-collabstories

## What

Collab Stories, permainan menulis "pass the pen" ala Cerivitas. Berisi cerita kolaboratif,
karakter, dan gambar pendukung.

## Map — source of truth

| Data | File |
|---|---|
| Ringkasan dan aturan permainan | `README.md`, `index.md` |
| Cerita | `stories/` |
| Karakter | `karakter/` |
| Gambar | `images/` |

## Run

Tidak ada build. Repo konten.

## Rules

- Satu cerita = satu file di `stories/`.
- Nama karakter harus konsisten dengan `karakter/`.
- `git pull --rebase` sebelum menulis.

## Don't

- Jangan commit secret/credential (ref: `vaultwarden:<item>/<field>`).
- Jangan mengubah `index.md` tanpa menyesuaikan daftar cerita.

## State

`STATE.md` — baca di awal sesi, **update sebelum berhenti**.
