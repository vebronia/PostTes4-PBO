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

## Cara Menjalankan
1. Clone repository ini ke komputer lokal.  
2. Buka project di IDE (NetBeans, IntelliJ, Eclipse).  
3. Jalankan file Main.java di package main.  
4. Ikuti menu interaktif untuk tambah, lihat, ubah, hapus, dan cari koleksi.  

## Contoh Output

<img width="263" height="200" alt="image" src="https://github.com/user-attachments/assets/08783e8f-628a-4bc5-a883-fb9d0ec800ec" />

