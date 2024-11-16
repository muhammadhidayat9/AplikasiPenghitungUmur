# Aplikasi Penghitung Umur

Aplikasi ini dirancang untuk menghitung umur pengguna berdasarkan tanggal lahir yang dimasukkan. Setelah pengguna memilih tanggal lahir dan menekan tombol **Hitung**, aplikasi akan menampilkan umur dalam format **tahun**, **bulan**, dan **hari**.

## Fitur

- **Input Tanggal Lahir**: 
  Menggunakan komponen GUI `JDateChooser` untuk memilih tanggal lahir.
- **Perhitungan Usia**: 
  Menghitung dan menampilkan umur dalam format tahun, bulan, dan hari.
- **Event Handling**: 
  - Mendukung interaksi dengan tombol **Hitung** menggunakan `ActionListener`.
  - Memperbarui hasil secara otomatis saat tanggal lahir diubah dengan `PropertyChangeListener`.
- **Fitur Tambahan**:
  - Menampilkan tanggal ulang tahun berikutnya.
  - Integrasi dengan API eksternal untuk menampilkan peristiwa penting yang terjadi pada tanggal lahir.

## Komponen GUI

Aplikasi ini dibangun menggunakan komponen GUI berikut:
- `JFrame`: Untuk jendela utama aplikasi.
- `JPanel`: Sebagai wadah untuk mengorganisir komponen GUI.
- `JLabel`: Untuk menampilkan teks atau label di layar.
- `JDateChooser`: Untuk memilih tanggal lahir pengguna.
- `JButton`: Untuk memulai proses perhitungan.
- `JTextField`: Untuk menampilkan hasil perhitungan.

## Logika Program

Logika program menggunakan:
- **`LocalDate`**: Untuk memanipulasi dan menghitung tanggal.
- Perhitungan selisih waktu antara tanggal lahir dan tanggal saat ini.

## Event Handling

- **`ActionListener`**: 
  Digunakan untuk menangani aksi tombol **Hitung**.
- **`PropertyChangeListener`**: 
  Mendeteksi perubahan tanggal pada komponen `JDateChooser`.

## Variasi Fitur

- Menyediakan informasi tambahan seperti tanggal ulang tahun berikutnya.
- Mendukung integrasi API eksternal untuk menampilkan informasi penting berdasarkan tanggal lahir.

## Cara Menggunakan

1. Jalankan aplikasi.
2. Pilih tanggal lahir menggunakan komponen `JDateChooser`.
3. Tekan tombol **Hitung**.
4. Umur Anda akan ditampilkan dalam format tahun, bulan, dan hari.
5. (Opsional) Informasi tambahan seperti tanggal ulang tahun berikutnya dan peristiwa penting akan ditampilkan.

---

### Catatan

Aplikasi ini dibangun menggunakan Java Swing. Pastikan Anda sudah memiliki lingkungan pengembangan Java yang mendukung untuk menjalankan aplikasi ini.


- Muhammad Hidayat 2210010354
- Latihan 2 
