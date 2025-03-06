# Materi Belajar Basis Data

## 1. Pengantar Basis Data
Basis data (database) adalah kumpulan data yang terorganisir dan dapat diakses, dikelola, serta diperbarui dengan mudah.

### 1.1 Definisi Basis Data
- Kumpulan data yang terstruktur.
- Memungkinkan penyimpanan, manipulasi, dan pengelolaan data secara efisien.

### 1.2 Manfaat Basis Data
- Meningkatkan efisiensi dalam penyimpanan dan pengambilan data.
- Mengurangi redudansi dan inkonsistensi data.
- Mendukung keamanan dan integritas data.
- Memudahkan akses data bagi banyak pengguna secara bersamaan.

## 2. Model Basis Data
### 2.1 Model Hierarki
- Data disusun dalam bentuk pohon (tree).
- Contoh: IBM Information Management System (IMS).

### 2.2 Model Relasional
- Data disimpan dalam tabel (relasi) yang memiliki baris dan kolom.
- Contoh: MySQL, PostgreSQL, SQL Server.

### 2.3 Model NoSQL
- Tidak menggunakan tabel seperti model relasional.
- Contoh: MongoDB (dokumen), Redis (key-value), Neo4j (graf).

## 3. SQL (Structured Query Language)
SQL adalah bahasa yang digunakan untuk mengelola dan mengakses basis data relasional.

### 3.1 Perintah Dasar SQL
- **DDL (Data Definition Language):** Digunakan untuk mendefinisikan struktur basis data.
  ```sql
  CREATE TABLE mahasiswa (
      id INT PRIMARY KEY,
      nama VARCHAR(100),
      jurusan VARCHAR(50)
  );
  ```
  - `CREATE TABLE` – Membuat tabel baru.
  - `ALTER TABLE` – Mengubah struktur tabel.
  - `DROP TABLE` – Menghapus tabel.

- **DML (Data Manipulation Language):** Digunakan untuk manipulasi data.
  ```sql
  INSERT INTO mahasiswa (id, nama, jurusan) VALUES (1, 'Budi', 'Informatika');
  ```
  - `INSERT INTO` – Menambahkan data.
  - `UPDATE` – Memperbarui data.
  - `DELETE` – Menghapus data.

- **DQL (Data Query Language):** Digunakan untuk mengambil data.
  ```sql
  SELECT * FROM mahasiswa;
  ```
  - `SELECT` – Mengambil data dari tabel.

## 4. Normalisasi Basis Data
Normalisasi adalah proses pengorganisasian data untuk mengurangi redundansi dan meningkatkan integritas data.

### 4.1 Bentuk Normal
- **1NF (First Normal Form):** Setiap kolom hanya memiliki satu nilai (atomicity).
- **2NF (Second Normal Form):** 1NF + Semua kolom non-kunci harus bergantung pada primary key.
- **3NF (Third Normal Form):** 2NF + Tidak ada ketergantungan transitif pada primary key.

## 5. Indeks dan Optimasi Query
- **Indeks** membantu mempercepat pencarian data.
  ```sql
  CREATE INDEX idx_nama ON mahasiswa(nama);
  ```
- **Optimasi Query** bertujuan meningkatkan performa database, misalnya dengan menggunakan `EXPLAIN` untuk menganalisis query.
  ```sql
  EXPLAIN SELECT * FROM mahasiswa WHERE nama='Budi';
  ```

## 6. Keamanan Basis Data
- **Autentikasi dan Otorisasi:** Menentukan siapa yang dapat mengakses database.
- **Backup dan Recovery:** Mencegah kehilangan data dengan membuat cadangan.
- **Enkripsi Data:** Melindungi data dari akses yang tidak sah.
