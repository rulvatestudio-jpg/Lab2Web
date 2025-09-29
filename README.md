# Lab2Web

Tujuan
Memahami konsep dasar CSS.
Memahami aturan penulisan CSS (internal, eksternal, inline).
Mengenal selector: elemen, class, dan id.
Mampu menerapkan CSS pada halaman HTML.
Persiapan
Text editor: VSCode
Browser untuk preview hasil
Validator CSS: https://jigsaw.w3.org/css-validator/

 1.Membuat text menjadi ditengah dengan menggunakan metode text-align; center dan membuat sisanya menjadi italic dengan cara <i> </i>
 <img width="1920" height="1200" alt="Screenshot 2025-09-29 130402" src="https://github.com/user-attachments/assets/1e630cb6-5d5a-43c4-b665-362a8ba85839" />

 2.Membuat text di paragraf kedua menjadi ditengah juga dengan cara yang sama dan menambahkan warna pada textnya dengan cara text-align; center; color #778FA
<img width="1920" height="1200" alt="Screenshot 2025-09-29 132358" src="https://github.com/user-attachments/assets/e046bc1f-b8eb-472b-a6d3-fabab6440511" />

3.Membuat Box Text di bagian navbar agar mempecantik web dengan cara menggunakan external css dengan <link rel="stylesheet" href="nama file css">
<img width="1920" height="1200" alt="Screenshot 2025-09-29 132812" src="https://github.com/user-attachments/assets/1700f8c6-b14f-4a18-990d-c35d59ec58eb" />

4.Membuat border dan memberi warna di bagian isi halaman dengan metode yang sama
<img width="1920" height="1200" alt="Screenshot 2025-09-29 134405" src="https://github.com/user-attachments/assets/12db9896-2ca7-40ea-8f15-b0d40f733447" />


# PERTNAYAAN DAN TUGAS PRAKTIKUM 2

1. Eksperimen Mengubah dan Menambah Properti CSS
Saya mencoba melakukan beberapa eksperimen di file CSS untuk melihat perbedaan hasil di browser.
Contoh kode CSS setelah diubah:

body {
  font-family: 'Open Sans', sans-serif;
  background-color: #f2f2f2;     /* ubah warna latar belakang halaman */
  line-height: 1.5;              /* tambahkan jarak antarbaris */
}

nav {
  background: #007BFF;           /* ganti warna navbar jadi biru */
  padding: 12px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.2); /* efek bayangan pada navbar */
}

.button {
  padding: 15px 30px;            /* perbesar padding tombol */
  border-radius: 6px;            /* sudut tombol jadi tumpul */
  font-weight: bold;             /* teks tombol jadi tebal */
  transition: background 0.3s ease;
}

.button:hover {
  background: #0056b3;           /* warna tombol berubah saat di-hover */
}


2. Perbedaan h1 { ... } dengan #intro h1 { ... }
h1 { ... } adalah selector elemen biasa, berlaku untuk semua <h1> di halaman.
#intro h1 { ... } adalah selector yang lebih spesifik, hanya berlaku untuk elemen <h1> yang ada di dalam elemen yang memiliki id="intro".

3. Prioritas Internal vs Eksternal vs Inline CSS

Saya menguji tiga jenis penulisan CSS pada elemen <p> yang sama:

<head>
  <style>
    p { color: green; }          /* Internal CSS */
  </style>
  <link rel="stylesheet" href="style.css"> <!-- Eksternal CSS -->
</head>
<body>
  <p style="color: red;">Teks Percobaan</p> <!-- Inline CSS -->
</body>

4. Prioritas Antara ID Selector dan Class Selector

Saya membuat contoh elemen <p> yang memiliki ID dan Class sekaligus:

#paragraf-1 {
  color: blue;
  font-weight: bold;
}

.text-paragraf {
  color: green;
  font-style: italic;
}

HTML

<p id="paragraf-1" class="text-paragraf">Contoh Paragraf</p>








