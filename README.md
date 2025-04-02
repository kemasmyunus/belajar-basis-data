# Belajar Basis Data

## 1. Pengantar Basis Data
Basis data (database) adalah kumpulan data yang terorganisir dengan baik dan dapat diakses, dikelola, serta diperbarui dengan mudah.

**Manfaat Basis Data:**
- Penyimpanan data yang lebih terstruktur
- Akses data yang lebih cepat dan efisien
- Keamanan data yang lebih baik
- Integritas data terjaga

## 2. Jenis Basis Data
1. **Relasional (RDBMS)**: Data disimpan dalam tabel (contoh: MySQL, PostgreSQL, SQL Server).
2. **Non-Relasional (NoSQL)**: Data tidak disimpan dalam bentuk tabel (contoh: MongoDB, Redis, Cassandra).
3. **Hierarkis**: Data disusun dalam bentuk pohon (contoh: IBM Information Management System).
4. **Jaringan**: Data memiliki hubungan kompleks antar entitas.

## 3. Model Basis Data
- **Hierarchical Model**
- **Network Model**
- **Relational Model**
- **Object-Oriented Model**
- **Document-Oriented Model**

## 4. Struktur Basis Data
- **Tabel**: Kumpulan data yang terdiri dari baris (record) dan kolom (field).
- **Kunci (Key)**:
  - **Primary Key**: Unik untuk setiap record.
  - **Foreign Key**: Menghubungkan tabel yang satu dengan lainnya.
- **Index**: Mempercepat pencarian data.
- **View**: Tampilan virtual dari tabel.

## 5. Bahasa Basis Data (SQL)
### 5.1 Data Definition Language (DDL)
- `CREATE TABLE` → Membuat tabel baru.
- `ALTER TABLE` → Mengubah struktur tabel.
- `DROP TABLE` → Menghapus tabel.

### 5.2 Data Manipulation Language (DML)
- `INSERT INTO` → Menambahkan data.
- `UPDATE` → Mengubah data.
- `DELETE` → Menghapus data.
- `SELECT` → Mengambil data.

### 5.3 Data Control Language (DCL)
- `GRANT` → Memberikan hak akses.
- `REVOKE` → Mencabut hak akses.

## 6. Normalisasi
Normalisasi adalah proses untuk mengurangi redundansi data dalam database.
- **1NF**: Menghapus duplikasi kolom.
- **2NF**: Memastikan setiap atribut bergantung pada primary key.
- **3NF**: Menghilangkan ketergantungan transitif.
- **BCNF**: Versi lebih ketat dari 3NF.

## 7. Transaksi dan ACID
**ACID (Atomicity, Consistency, Isolation, Durability)** adalah sifat utama dalam sistem basis data.
- **Atomicity**: Transaksi harus dilakukan sepenuhnya atau tidak sama sekali.
- **Consistency**: Data tetap dalam kondisi valid sebelum dan sesudah transaksi.
- **Isolation**: Transaksi tidak boleh mengganggu transaksi lain.
- **Durability**: Hasil transaksi tetap tersimpan meskipun terjadi kegagalan sistem.

## 8. Indexing dan Optimasi Query
- **Indexing**: Meningkatkan kecepatan pencarian data.
- **Query Optimization**: Teknik untuk meningkatkan efisiensi eksekusi query.

## 9. Backup dan Recovery
- **Backup**: Salinan data yang digunakan untuk pemulihan.
- **Recovery**: Mengembalikan data jika terjadi kegagalan sistem.

## 10. Keamanan Basis Data
- **Authentication**: Memastikan hanya pengguna yang sah yang bisa mengakses.
- **Authorization**: Mengontrol hak akses pengguna.
- **Encryption**: Melindungi data dari akses tidak sah.
