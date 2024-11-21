#  Vallencya Della // NIM : 352310368 (PRAKTIKUM 6)
# Deskripsi Program Daftar Nilai Mahasiswa

Program ini digunakan untuk mengelola data mahasiswa, menghitung nilai akhir, dan menampilkan daftar mahasiswa dalam tabel : 

![tugas 6 part 1](https://github.com/user-attachments/assets/610d4bac-b3f3-4f8d-bf09-4cbe61383948)
![tugas 6 part 2](https://github.com/user-attachments/assets/24866b6b-2883-4ea2-afc5-1ef15d899ea0)

## Program menggunakan `hitung_nilai_akhir`

### Tujuan
Menghitung total nilai mahasiswa berdasarkan hasil dari tugas, Ujian Tengah Semester (UTS), dan Ujian Akhir Semester (UAS).

### Indikator acuan
- **nilai_tugas**: Nilai tugas mahasiswa.
- **nilai_uts**: Nilai UTS mahasiswa.
- **nilai_uas**: Nilai UAS mahasiswa.

### Rumus nilai akhir 
Nilai akhir = (Tugas * 0.3) + (UTS * 0.35) + (UAS * 0.35)

### Return
Fungsi ini mengembalikan total nilai akhir yang telah dihitung dalam bentuk angka desimal (float).

## Inisialisasi Data

`data_mahasiswa` adalah struktur data yang digunakan untuk menyimpan informasi mahasiswa, di mana Nomor Induk Mahasiswa (NIM) berfungsi sebagai kunci, sementara nilai yang disimpan mencakup nama, nilai tugas, nilai Ujian Tengah Semester (UTS), nilai Ujian Akhir Semester (UAS), dan nilai akhir.

## Input Data Mahasiswa

1. **Nama**: Nama mahasiswa.
2. **NIM**: Nomor Induk Mahasiswa.
3. **Nilai Tugas**: Nilai dari tugas.
4. **Nilai UTS**: Nilai Ujian Tengah Semester.
5. **Nilai UAS**: Nilai Ujian Akhir Semester.

Setelah pengguna selesai memasukkan data mahasiswa, program akan melakukan perhitungan untuk menentukan total nilai akhir dengan menggunakan fungsi `hitung_nilai_akhir`. Fungsi ini mengolah nilai tugas, UTS, dan UAS untuk menghasilkan nilai akhir yang mencerminkan kinerja akademis mahasiswa secara keseluruhan.

## Simpan Data dan Menanyakan Tambah Data

Data mahasiswa disimpan dalam format dictionary di dalam `data_mahasiswa`, di mana setiap NIM menjadi kunci dan informasi mahasiswa menjadi nilai. Setelah memasukkan data mahasiswa, program menanyakan kepada pengguna apakah ingin menambah data mahasiswa lagi. Jika pengguna memasukkan 'y', program akan kembali ke awal loop. Jika tidak, program akan melanjutkan untuk menampilkan daftar mahasiswa.

## Menampilkan Daftar Mahasiswa

Setelah pengguna memilih untuk tidak menambah data lagi, program menampilkan daftar semua mahasiswa yang telah dimasukkan dalam format tabel. Tabel mencakup:
- **No**: Nomor urut mahasiswa.
- **Nama**: Nama lengkap mahasiswa.
- **NIM**: Nomor Induk Mahasiswa.
- **Tugas**: Nilai tugas mahasiswa.
- **UTS**: Nilai Ujian Tengah Semester.
- **UAS**: Nilai Ujian Akhir Semester.
- **Akhir**: Nilai akhir yang telah dihitung.

### Contoh Output

![outputnya](https://github.com/user-attachments/assets/88e7282a-be3d-4033-8fdb-dbf3e1f05719)


### Flowchart 

![program phyton](https://github.com/user-attachments/assets/1bbeb674-3b5b-4025-8ba0-1825c2f4817a)
