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
- **Latihan kecil yang divalidasi**: di setiap materi, editor latihan dimulai dari kode awal
  (data + petunjuk), **tanpa kode jawaban**. Yang ditampilkan hanyalah instruksi dan
  **hasil output yang diharapkan**. Peserta menulis kode sendiri lalu menekan
  "Periksa jawaban"; hasilnya divalidasi terhadap output target dan konsep wajib materi
  tersebut. Boleh mencoba berkali-kali tanpa batas. Setelah 2 kegagalan muncul tombol
  petunjuk, setelah 3 kegagalan muncul tombol "Lihat jawaban". Kode jawaban juga bisa
  dibuka setelah berhasil, untuk membandingkan cara penyelesaian.
- **Cek pemahaman sebelum lanjut**: setiap materi punya satu pertanyaan pilihan ganda.
  Tombol "Tandai selesai & lanjut" dan link "Berikutnya" baru aktif setelah **latihan kecil
  lolos validasi dan** jawaban pertanyaan benar. Kalau jawabannya salah, muncul petunjuk,
  bantuan setelah percobaan kedua, dan tombol untuk membaca ulang penjelasannya.
  Status tersimpan di `localStorage` (kunci `pdn_progress_v1` → `latihan` dan `paham`;
  `selesai` dari versi lama tetap dihormati).

Playground mendukung interpreter Python mini, termasuk `try` / `except` / `finally`.
Soal yang memakai `input()` memakai isian tetap saat divalidasi supaya hasilnya deterministik.
