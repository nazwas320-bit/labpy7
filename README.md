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
             │    tampilkan()      │
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
