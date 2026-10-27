# belajar-python

Website belajar Python dari nol untuk pemula, dalam satu file `index.html` (HTML + CSS + JavaScript murni, tanpa backend).

## Menjalankan

Cukup buka `index.html` di browser. Atau jalankan server statis:

```bash
python3 -m http.server 8000
```

Lalu buka `http://localhost:8000`. Progress belajar tersimpan di `localStorage` browser.

## Alur belajar

- 10 level, 68 materi, dari `print()` sampai mini project.
- **Level 4–10** (konsep yang paling sulit) dilengkapi:
  - **Versi paling sederhana** — penjelasan ulang tanpa istilah asing, ditaruh tepat setelah **Penjelasan sederhana**.
  - **Kamus kecil** — arti setiap istilah teknis di materi itu.
  - **Pertanyaan yang sering muncul** — FAQ untuk kebingungan yang paling umum.
  - Materi jembatan/rangkuman di tiap level supaya tidak ada lompatan konsep.
- **Cek pemahaman sebelum lanjut**: setiap materi punya satu pertanyaan pilihan ganda.
  Tombol "Tandai selesai & lanjut" dan link "Berikutnya" baru aktif setelah jawaban benar
  dan pengguna menekan "Sudah paham, lanjut". Kalau jawabannya salah, muncul petunjuk,
  bantuan setelah percobaan kedua, dan tombol untuk membaca ulang penjelasannya.
  Status kelulusan tersimpan di `localStorage` (kunci `pdn_progress_v1` → `paham`).

Playground mendukung interpreter Python mini, termasuk `try` / `except` / `finally`.
