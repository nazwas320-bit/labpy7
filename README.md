## Nama : Nazwa Salsabila
## Nim : 312510155
## kelas : TI.25.A2
## pertemuan : 12

## Input kode praktikum 7

<img width="840" height="695" alt="Tangkapan Layar 2025-12-04 pukul 09 19 33" src="https://github.com/user-attachments/assets/723ae4d5-bd08-4e91-9cf6-5a100e340f46" />

## Output kode praktikum 7

<img width="1002" height="300" alt="Tangkapan Layar 2025-12-04 pukul 09 19 56" src="https://github.com/user-attachments/assets/a08e6909-f5f0-44bc-8a6b-3955210a50f1" />

##flowchart
```
               ┌───────────────┐
               │     Mulai     │
               └───────┬───────┘
                       │
               ┌───────▼────────┐
               │  Buat Object   │
               │ NilaiMahasiswa │
               └───────┬────────┘
                       │
             ┌─────────▼──────────┐
             │    tambah()        │
             └─────────┬──────────┘
                       │
             ┌─────────▼──────────┐
             │   tampilkan()      │
             └─────────┬──────────┘
                       │
             ┌─────────▼──────────┐
             │      ubah()        │
             └─────────┬──────────┘
                       │
             ┌─────────▼──────────┐
             │    tampilkan()     │
             └─────────┬──────────┘
                       │
             ┌─────────▼──────────┐
             │     hapus()        │
             └─────────┬──────────┘
                       │
             ┌─────────▼──────────┐
             │    tampilkan()     │
             └─────────┬──────────┘
                       │
                  ┌────▼────┐
                  │  Selesai│
                  └─────────┘
```
## DIAGRAM CLASS (UML)
```
+--------------------------------+
|        NilaiMahasiswa          |
+--------------------------------+
| - data : dict                  |
+--------------------------------+
| + tambah(nama, nilai)          |
| + tampilkan()                  |
| + hapus(nama)                  |
| + ubah(nama, nilai_baru)       |
+--------------------------------+
```
Keterangan:

data → dictionary penyimpanan (nama → nilai)

tambah() → menambah data

tampilkan() → menampilkan data

hapus() → menghapus data

ubah() → mengubah nilai mahasiswa

## Penjelasan README.md

## Praktikum 8 – Program Daftar Nilai Mahasiswa (OOP)

Program ini dibuat untuk memenuhi tugas Praktikum 8 dengan menerapkan konsep **Object-Oriented Programming (OOP)** dalam bahasa Python.  
Program menggunakan sebuah class bernama `NilaiMahasiswa` yang berfungsi untuk mengelola data nilai mahasiswa.

---

## Tujuan Program
- Mengaplikasikan pemrograman berbasis objek (OOP)
- Menggunakan class, atribut, dan method
- Melakukan operasi tambah, tampilkan, hapus, dan ubah data mahasiswa

---

## Fitur Program

### 1. `tambah(nama, nilai)`
Menambahkan data mahasiswa baru ke dalam dictionary.

### 2. `tampilkan()`
Menampilkan semua data mahasiswa.  
Jika belum ada data, akan muncul pesan: **"Belum ada data."**

### 3. `hapus(nama)`
Menghapus data berdasarkan nama mahasiswa.  
Jika nama tidak ditemukan, tampil pesan error.

### 4. `ubah(nama, nilai_baru)`
Mengubah nilai mahasiswa.  
Jika nama tidak ada dalam data, tampil pesan error.

---


---

## 📘 Penjelasan Program

Program ini menggunakan konsep dasar OOP:

### ✔ **Class**
`NilaiMahasiswa` digunakan untuk menyimpan dan mengelola data mahasiswa.

### ✔ **Atribut**
- `self.data` → dictionary yang menyimpan pasangan (nama: nilai)

### ✔ **Method**
- `tambah()` → memasukkan data baru
- `tampilkan()` → menampilkan seluruh data
- `hapus()` → menghapus data berdasarkan kunci
- `ubah()` → memperbarui nilai mahasiswa
