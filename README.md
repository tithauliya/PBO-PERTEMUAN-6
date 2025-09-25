## Penerapan JDialog pada GUI Database (Java + PostgreSQL)

Laporan ini disusun untuk memenuhi tugas mata kuliah **Pemrograman Berorientasi Obyek** dengan fokus pada implementasi **Java Swing (JFrame & JDialog)** yang terhubung dengan **PostgreSQL**.  

---

## 👨‍🏫 Dosen Pengampu
Bayu Adhi Nugroho, Ph.D.  

## 👤 Identitas
- **Nama**  : Titha Auliya Khotim  
- **NIM**   : 09010624017  
- **Kelas** : H7B.3  
- **Program Studi** : Sistem Informasi  
- **Fakultas** : Sains dan Teknologi  
- **Universitas** : UIN Sunan Ampel Surabaya  
- **Tahun** : 2025  

---

## 📌 Deskripsi Proyek
Pada praktikum ini dibuat sebuah **Sistem Data Roti** menggunakan **Java Swing** yang terhubung dengan **PostgreSQL**.  
Fitur utama berupa penerapan **JDialog** untuk mendukung operasi **CRUD (Create, Read, Update, Delete)** dengan tampilan grafis interaktif.  

### ✨ Fitur Utama
- **Insert (Tambah Data)** → Form JDialog untuk menambahkan data roti.  
- **Update (Perbarui Data)** → Form JDialog untuk mengubah data roti yang dipilih.  
- **Delete (Hapus Data)** → Dialog konfirmasi sebelum menghapus data.  
- **Read (Tampilkan Data)** → JTable menampilkan seluruh data dari database.  
- **Exception Handling** → Validasi input, pesan peringatan, dan penanganan error.  

---

## 🗄️ Struktur Database
Gunakan PostgreSQL dengan database `PBO4` dan tabel `tokoroti`:  

```sql
CREATE TABLE tokoroti (
    id_kue VARCHAR(10) PRIMARY KEY,
    nama_kue VARCHAR(50),
    harga INT,
    stock INT
);

