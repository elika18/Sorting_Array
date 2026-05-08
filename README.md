# Bubble Sort (Ascending & Descending) – Java

Repository ini berisi implementasi algoritma **Bubble Sort** menggunakan bahasa **Java**, dengan dua jenis pengurutan:
- Ascending (kecil → besar)
- Descending (besar → kecil)

Project ini dibuat sebagai bagian dari pembelajaran algoritma sorting dan logika perulangan bersarang.

---

## Deskripsi Singkat

Bubble Sort adalah algoritma pengurutan sederhana yang bekerja dengan cara:
- Membandingkan dua elemen array yang bersebelahan
- Menukar posisi elemen jika urutannya tidak sesuai
- Mengulangi proses hingga seluruh data terurut

Disebut *bubble* karena elemen terbesar atau terkecil akan “menggelembung” ke posisi yang benar secara bertahap.

---

## Cara Kerja Algoritma

1. Menggunakan **dua buah perulangan (nested loop)**  
2. Perulangan luar menentukan jumlah iterasi  
3. Perulangan dalam membandingkan elemen yang bersebelahan  
4. Pertukaran nilai dilakukan menggunakan variabel sementara (`temp`)  

### Ascending
- Tukar data jika elemen kiri **lebih besar** dari elemen kanan

### Descending
- Tukar data jika elemen kiri **lebih kecil** dari elemen kanan

Struktur algoritma tetap sama, yang membedakan hanya **operator perbandingannya**.

---

## Contoh Data

Array awal:
200 50 10 4 300 1

Hasil Ascending:
1 4 10 50 200 300

Hasil Descending:
300 200 50 10 4 1

---

## Kompleksitas Waktu

- **Time Complexity:** O(n²)
- **Space Complexity:** O(1)

Karena kompleksitasnya kuadratik, Bubble Sort kurang efisien untuk data berukuran besar, namun sangat cocok untuk:
- Pembelajaran dasar algoritma
- Pemahaman logika sorting
- Latihan perulangan dan kondisi

---

## Cara Menjalankan Program

1. Pastikan Java sudah terinstall
2. Compile program:
   ```bash
   javac BubbleSort.java
3. Jalankan proram:
java BubbleSort
