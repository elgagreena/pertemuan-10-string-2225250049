# Pertemuan 10 - String dan Pengolahan Teks

**Nama:** Elga Greena Rahma Tazkia
**NIM:** 2225250049
**Kelas:** 3B

## Tujuan

Mempelajari penggunaan string dalam Python, termasuk indeks dan slicing, metode string, pembersihan teks, pemisahan dan penggabungan kata, serta pencarian kata. Tugas utama menerapkan normalisasi data mahasiswa.

## Daftar Latihan

1. `01_dasar_string.py` — Dasar string.
2. `02_indeks_slicing.py` — Indeks dan slicing.
3. `03_method_string.py` — Metode string.
4. `04_bersihkan_teks.py` — Membersihkan teks.
5. `05_split_join.py` — Memisahkan dan menggabungkan kata.
6. `06_pencarian_kata.py` — Mencari kata dalam teks.

## Algoritma Tugas

1. Memasukkan nama mahasiswa dan kode kelas.
2. Menghapus spasi berlebih pada nama.
3. Mengubah nama menjadi format huruf kapital di awal setiap kata.
4. Mengubah kode kelas menjadi huruf kapital dan mengganti pemisah spasi dengan tanda hubung.
5. Menghitung jumlah kata pada nama dan membentuk inisial dari setiap kata.
6. Menampilkan hasil normalisasi.

## Cara Menjalankan

Pastikan Python sudah terpasang. Jalankan perintah berikut dari folder utama proyek:

```bash
python tugas/normalisasi_data_mahasiswa.py
```

Masukkan nama dan kode kelas ketika diminta program.

## Test Case

| No. | Input Nama              | Input Kode Kelas | Hasil yang Diharapkan                    | Status |
| --- | ----------------------- | ---------------- | ---------------------------------------- | ------ |
| 1   | `aan hendrayana`        | `pmat a 2026`    | `Aan Hendrayana \| PMAT-A-2026 \| AH`    | Lulus  |
| 2   | `fATHIYYAH mUTHMAINNAH` | `kelas b`        | `Fathiyyah Muthmainnah \| KELAS-B \| FM` | Lulus  |
| 3   | `BUDI`                  | `pmtk 01`        | `Budi \| PMTK-01 \| B`                   | Lulus  |
| 4   | `siti nur aisyah`       | `kelas c`        | `Siti Nur Aisyah \| KELAS-C \| SNA`      | Lulus  |

Hasil aktual sesuai dengan hasil yang diharapkan pada keempat pengujian.

## Refleksi

Salah satu kesalahan teks yang ditemukan adalah adanya spasi berlebih di antara kata. Kesalahan ini diperbaiki menggunakan `split()` dan `join()` agar setiap kata dipisahkan oleh satu spasi.
