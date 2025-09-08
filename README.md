# Laporan Praktikum Layout flutter
# praktikum 1
## Langkah 1: Buat Project Baru
Membuat sebuah project flutter baru dengan nama layout_flutter. 
## Langkah 2: Buka file lib/main.dart
Buka file main.dart lalu Isi nama dan NIM
<img width="489" height="395" alt="image" src="https://github.com/user-attachments/assets/62c0a00f-c7cb-4ecf-95c2-40b64343c526" />

<img width="647" height="663" alt="image" src="https://github.com/user-attachments/assets/30539ea3-0c36-4abc-ae50-673c09abc698" />
<img width="319" height="694" alt="Cuplikan layar 2025-09-08 152956" src="https://github.com/user-attachments/assets/cb0f6b00-dfd8-4406-a2d8-f4b34a33b4fd" />
## Langkah 3: Identifikasi layout diagram
Elemen yang lebih besar (gambar Danau bedugul), kemudian ada judul(Danau Bedugul), dan judul kedua (Bali, Indonesia), kemudian ada icon, disebelah kanan atas icon ada sebuah rating untuk penilaian, kemudian dibawah ico terdapat deskripsi. 
<img width="311" height="656" alt="image" src="https://github.com/user-attachments/assets/1bce367b-6903-4cf8-860b-645f959b45cd" />
## Langkah 4: Implementasi title row
Expanded + Column: Menampung judul dan lokasi, dengan crossAxisAlignment: CrossAxisAlignment.start.Icon: Bintang merah,Text: Angka "41".
Semua ini dibungkus dalam satu baris (Row) dan diberi padding.
<img width="458" height="668" alt="image" src="https://github.com/user-attachments/assets/39150f40-ab48-43fb-ae30-80475cecb68c" />

# praktikum 2
## Langkah 1: Buat method Column _buildButtonColumn
 <img width="745" height="552" alt="image" src="https://github.com/user-attachments/assets/b783912b-aeb0-4fdd-8665-985c91db9139" />


## Langkah 2: Buat widget buttonSection
Widget buttonSection = Row(
  mainAxisAlignment: MainAxisAlignment.spaceEvenly,
  children: [
    _buildButtonColumn(color, Icons.call, 'CALL'),
    _buildButtonColumn(color, Icons.near_me, 'ROUTE'),
    _buildButtonColumn(color, Icons.share, 'SHARE'),
  ],
);
## Langkah 3: Tambah button section ke body
<img width="773" height="358" alt="image" src="https://github.com/user-attachments/assets/f69b0541-7bc7-4ebb-bc9e-a8284e6d1fa5" />

Buttonsection suah dimasukkan kedalam body seperti ini :
body: ListView(children: [buttonSection]),

# praktikum 3
## Langkah 1: Buat widget textSection
  <img width="940" height="621" alt="image" src="https://github.com/user-attachments/assets/f75350c9-0570-40ae-9b7f-3cdcc3dc74b0" />
## Langkah 2: Tambahkan variabel text section ke body
<img width="491" height="309" alt="image" src="https://github.com/user-attachments/assets/5c890980-1b18-43b3-a180-04a7fea5a19e" />

# praktikum 4
## Langkah 1: Siapkan aset gambar
<img width="736" height="313" alt="image" src="https://github.com/user-attachments/assets/8c503fa9-2a8a-4332-9fba-fcb52e0c1cc8" />
## Langkah 2: Tambahkan gambar ke body
<img width="762" height="271" alt="image" src="https://github.com/user-attachments/assets/e6e62fec-1762-4852-8510-65c8676a42a3" />
## Langkah 3: Terakhir, ubah menjadi ListView
<img width="491" height="219" alt="image" src="https://github.com/user-attachments/assets/5357ab0d-3a4d-4594-96c9-8ec04d3c3201" />


