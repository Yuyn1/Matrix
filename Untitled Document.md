Penjumlahan Matriks Sederhana dengan Python
Program ini merupakan script Python sederhana untuk melakukan penjumlahan dua buah matriks 2D yang ukurannya bisa bervariasi per baris, selama kedua matriks memiliki struktur baris dan kolom yang sama.

💡 Deskripsi
Kode ini menjumlahkan dua buah matriks A dan B elemen demi elemen, dan menghasilkan matriks baru sebagai hasil penjumlahan. Setiap elemen pada posisi [i][j] di matriks hasil merupakan hasil penjumlahan dari elemen A[i][j] + B[i][j].

🧾 Contoh Matriks
python
Salin
Edit
A = [
    [1, 2, 3, 4, 5],
    [6, 7, 8, 9, 10],
    [11, 12, 13, 14],
    [16, 17, 18, 19],   
    [21, 22, 23, 24],
]

B = [
    [2, 3, 4, 5, 6],
    [15, 16, 17, 18, 19],
    [100, 101, 102, 103, 104],
    [25, 26, 27, 28, 29],
    [29, 30, 31, 32, 33],
]
⚙️ Cara Kerja
Definisi Fungsi:
Fungsi add_matrices(A, B) menerima dua matriks sebagai input.

Perulangan:
Menggunakan nested loop (for) untuk menelusuri setiap baris dan kolom.

Penjumlahan:
Setiap elemen pada posisi [i][j] dari A dan B dijumlahkan, lalu dimasukkan ke matriks hasil.

Output:
Menampilkan hasil penjumlahan matriks ke layar.

💻 Output Contoh
less
Salin
Edit
Hasil Penjumlahan Matriks A dan B:
[3, 5, 7, 9, 11]
[21, 23, 25, 27, 29]
[111, 113, 115, 117]
[41, 43, 45, 47]
[50, 52, 54, 56]
📌 Catatan
Pastikan kedua matriks memiliki ukuran baris dan kolom yang sama untuk menghindari error.

Cocok digunakan untuk latihan dasar pengolahan array/matrix dalam Python.

🚀 Cara Menjalankan
Simpan script ini sebagai file Python, misalnya penjumlahan_matriks.py.

Jalankan di terminal dengan perintah:

bash
Salin
Edit
python penjumlahan_matriks.py
