# Belajar Database

## Pengantar Kelas Database
- **Instruktur**: Eko Kurniawan, seorang database engineer dengan pengalaman lebih dari 12 tahun.
- Fokus pada konsep dan pemodelan database, serta penerapan dalam dunia nyata.

## Agenda
- Memahami apa itu database.
- Membahas database systems dan relational data models.
- Mempelajari data normalization dan aplikasi database systems.

## Definisi Database
- **Database** adalah kumpulan data yang terorganisir, yang memungkinkan penyimpanan, pengambilan, dan pengelolaan data dengan efisien. 
- Data dalam database merepresentasikan fakta dunia nyata, seperti informasi tentang karyawan, pelanggan, produk, dan transaksi.
- Data dapat disimpan dalam berbagai format, termasuk teks, angka, gambar, dan file multimedia lainnya.

## Pentingnya Mengorganisir Data
- Mengorganisir data sangat penting untuk memastikan bahwa informasi dapat diakses dengan cepat dan efisien. 
- Operasi kunci dalam database dikenal dengan istilah **CRUD**:
  - **Create**: Menambahkan data baru ke dalam database. Contohnya, menambahkan informasi pelanggan baru.
  - **Read**: Mengambil data dari database. Misalnya, mencari informasi tentang pelanggan tertentu.
  - **Update**: Memperbarui data yang sudah ada. Contohnya, mengubah alamat pelanggan.
  - **Delete**: Menghapus data dari database. Misalnya, menghapus informasi pelanggan yang sudah tidak aktif.

## Manfaat Menggunakan Database
- **Kecepatan**: Database memungkinkan pengambilan data yang cepat, yang sangat penting dalam aplikasi yang memerlukan respons waktu nyata, seperti sistem pemesanan online.
- **Efisiensi Penyimpanan**: Database dirancang untuk menggunakan ruang penyimpanan secara optimal, mengurangi redundansi data dan meminimalkan biaya penyimpanan.
- **Akurasi dan Ketersediaan**: Dengan menggunakan database, data dapat diperbarui secara terpusat, sehingga meningkatkan akurasi dan ketersediaan informasi bagi pengguna.
- **Keamanan dan Berbagi**: Database memungkinkan pengaturan akses yang ketat, sehingga hanya pengguna yang berwenang yang dapat mengakses atau memodifikasi data. Ini penting untuk menjaga kerahasiaan dan integritas data.

## Aplikasi Dunia Nyata dari Database
- **Bank**: Mengelola informasi rekening, transaksi, dan nasabah. Database memungkinkan bank untuk melacak transaksi secara real-time dan memberikan layanan yang lebih baik kepada nasabah.
- **Rumah Sakit**: Menyimpan data pasien, rekam medis, dan jadwal dokter. Dengan database, rumah sakit dapat mengelola informasi pasien dengan lebih efisien dan meningkatkan kualitas perawatan.
- **Sekolah**: Mengelola data siswa, kurikulum, dan nilai. Database membantu sekolah dalam menyimpan dan mengelola informasi akademik serta administrasi.
- **E-commerce**: Mengelola produk, transaksi, dan informasi pelanggan. Database memungkinkan platform e-commerce untuk melacak inventaris, memproses pesanan, dan menganalisis perilaku pelanggan.

## Sistem Manajemen Database (DBMS)
- **DBMS** adalah perangkat lunak yang mengelola database, memungkinkan pengguna untuk berinteraksi dengan data. DBMS menyediakan antarmuka untuk melakukan operasi CRUD dan mengelola struktur data.
- Contoh DBMS yang populer termasuk:
  - **MySQL**: Sistem manajemen database open-source yang banyak digunakan untuk aplikasi web.
  - **PostgreSQL**: DBMS open-source yang dikenal karena kemampuannya dalam menangani data yang kompleks.
  - **Microsoft SQL Server**: DBMS komersial yang banyak digunakan di perusahaan besar.
  - **Oracle**: DBMS yang kuat dan banyak digunakan dalam aplikasi enterprise.
- Komponen DBMS meliputi:
  - **Hardware**: Perangkat fisik tempat database disimpan, seperti server.
  - **Operating System**: Sistem operasi yang menjalankan DBMS, seperti Windows atau Linux.
  - **Users**: Pengguna yang berinteraksi dengan database, termasuk administrator, pengembang, dan pengguna akhir.

## Pemodelan Data
- **Data modeling** adalah proses mendefinisikan struktur data dan hubungan antar data. Pemodelan data membantu dalam merancang database yang efisien dan efektif.
- **Entity-Relationship Diagram (ERD)** adalah metode populer untuk pemodelan data yang menggambarkan entitas dan hubungan di antara mereka. ERD membantu dalam visualisasi struktur database.

## Komponen ERD
- **Entities**: Item data individu yang relevan dalam sistem, seperti pasien, dokter, atau produk. Setiap entitas biasanya direpresentasikan sebagai persegi panjang dalam ERD.
- **Attributes**: Karakteristik dari entitas, seperti ID pasien, nama, dan
