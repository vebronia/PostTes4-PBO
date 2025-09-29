# PostTes4-PBO
| Nama                      | NIM           | Kelas             |
|---------------------------|---------------|-------------------|
|  Vebronia vitania Lusi    | 2409116112    | Sistem Informasi C|


## Deskripsi
Project ini dibuat untuk memenuhi tugas Post Test Pemrograman Berorientasi Objek.  
Program  mengelola data koleksi alat olahraga menggunakan konsep OOP (Encapsulation, Inheritance, Abstraction, dan Polymorphism) serta menyediakan fitur CRUD melalui menu interaktif.

## Struktur Package

<img width="529" height="358" alt="Screenshot 2025-09-28 215550" src="https://github.com/user-attachments/assets/e12064f4-c71f-4658-bd63-e87b333ce98e" />

## Penerapan Konsep OOP
- Encapsulation  
  Atribut nama, harga, dan stok di class Properti dibuat private, diakses melalui getter dan setter.

- Inheritance  
  Properti sebagai superclass abstract.  
  AlatOlahraga sebagai subclass umum.  
  Bola dan Raket sebagai subclass spesifik.

- Abstraction  
  Properti adalah abstract class dengan method info().  
  Transaksi adalah interface dengan method printNota().

- Polymorphism  
  Overloading: method setHarga(double harga) dan setHarga(double harga, double diskon) pada Properti.  
  Overriding: method info() di AlatOlahraga, Bola, dan Raket.

- Nilai Tambah  
  Kombinasi abstract class (Properti) dan interface (Transaksi) digunakan bersamaan.


## Alur Program
  1. Tambah Koleksi
  
<img width="551" height="399" alt="Screenshot 2025-09-29 153457" src="https://github.com/user-attachments/assets/fda92ccd-d32c-4d3e-84a0-c731d927ea32" />

Saat memilih menu Tambah Koleksi, pengguna memasukkan data baru berupa nama, harga, stok, dan jenis olahraga. Data tersebut kemudian disimpan dalam daftar koleksi. Pada contoh output, koleksi yang ditambahkan adalah Ring dengan harga 300000, stok 2, dan jenis olahraga Basket

2. Lihat Koleksi

   <img width="820" height="709" alt="Screenshot 2025-09-29 154035" src="https://github.com/user-attachments/assets/0ebfb50a-5bfe-48f3-8408-9f2818582e1b" />

3. ubah koleksi

   <img width="477" height="426" alt="Screenshot 2025-09-29 153659" src="https://github.com/user-attachments/assets/11e73aff-0459-4ac9-ad15-bde1fa5b7e8f" />

Saat memilih menu Ubah Koleksi, pengguna menentukan nomor data yang ingin diubah lalu memasukkan data baru. Pada contoh output, koleksi nomor 2 diubah menjadi Gawang dengan harga 1000000, stok 2, dan jenis olahraga Sepak bola. Program kemudian menampilkan pesan bahwa data berhasil diubah

4. Hapus Koleksi

<img width="620" height="630" alt="Screenshot 2025-09-29 154100" src="https://github.com/user-attachments/assets/f263ec49-9c0a-4f01-b5af-305e24b4b9b0" />

   Pada menu Hapus Koleksi, program menampilkan semua data koleksi beserta nomor urutnya. Pengguna memilih nomor 1 (Raket), lalu program menghapus data tersebut dan menampilkan pesan bahwa data berhasil dihapus.

5. Cari Koleksi

   <img width="541" height="383" alt="Screenshot 2025-09-29 154121" src="https://github.com/user-attachments/assets/d29b1139-adef-47ad-8a84-8f132d8ca28a" />

6. Keluar

<img width="379" height="195" alt="image" src="https://github.com/user-attachments/assets/5951f82e-c665-4cab-aba7-6c4c4a1c7c3c" />


   
