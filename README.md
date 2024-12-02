# Tugas Praktikum 7

Buat program sederhana dengan mengaplikasikan penggunaan class. Buatlah class untuk menampilkan daftar nilai mahasiswa, dengan ketentuan:

- Method tambah() untuk menambah data

- Method tampilkan() untuk menampilkan data

- Method hapus(nama) untuk menghapus data berdasarkan nama

- Method ubah(nama) untuk mengubah data berdasarkan nama

- Buat diagram class, flowchart dan penjelasan programnya pada README.md.

- Commit dan push repository ke github.

# Tampilan Program

1. Diagram Class & Flowchart

  ![Flowchart (13)](https://github.com/user-attachments/assets/15768721-4164-46d5-9693-db68e4becb63)

  ![Flowchart (12)](https://github.com/user-attachments/assets/caf1b3b3-4274-4ee6-8d66-96b0240b849b)

2. Program Python

  ![image](https://github.com/user-attachments/assets/4643d107-284d-4547-81f5-8a09075b1ae7)

  ![image](https://github.com/user-attachments/assets/9adc0b9a-e52f-4312-b6f1-cf5181c89a67)

  ![image](https://github.com/user-attachments/assets/039143be-4ec4-427f-8220-b429fc0f86bb)

  ![image](https://github.com/user-attachments/assets/4b6f64d8-c941-44f5-9328-a049f85380a8)

  ![image](https://github.com/user-attachments/assets/7ca1dc01-0662-4630-8a4e-9b610cdeda07)

3. Penjelasan

  - Pembuatan Class Mahasiswa:

    - Berfungsi untuk mengelola data mahasiswa seperti menambah, mengubah, menghapus, dan menampilkan data.
    
    - Data mahasiswa disimpan sebagai private attribute untuk menjaga aksesibilitas.

  - Inheritance:

    - Class Person mewarisi seluruh method dari class Mahasiswa.
    
    - Method cetak_data di class Person menimpa method bawaan class Mahasiswa untuk menunjukkan contoh overriding.

  - Penggunaan Menu:
    - Mengelola input dan logika utama berdasarkan pilihan pengguna.

  - Fungsi Menu:

    - Tambah Data:

      Pengguna diminta memasukkan nama, NIM, nilai tugas, UTS, dan UAS. Nilai akhir dihitung dengan formula (tugas * 0.3) + (uts * 0.35) + (uas * 0.35), kemudian data disimpan ke dalam list __data_mahasiswa menggunakan method tambah().
    
    - Tampilkan Data:

      Method tampilkan() menampilkan data mahasiswa dalam bentuk tabel yang rapi, atau menampilkan pesan jika tidak ada data.
    
    - Hapus Data:

      Pengguna memasukkan nama mahasiswa yang ingin dihapus. Jika data ditemukan, data tersebut dihapus dari list menggunakan method hapus().

    - Ubah Data:

      Pengguna memasukkan nama mahasiswa yang ingin diubah. Jika data ditemukan, pengguna dapat memasukkan nilai baru untuk atribut NIM, tugas, UTS, dan UAS. Nilai akhir dihitung ulang, dan data diperbarui menggunakan method ubah().
    
    - Keluar Program:

      Program berhenti setelah mencetak pesan perpisahan.

  - Private Attribute:

    - Atribut __data_mahasiswa bersifat private untuk melindungi data agar tidak diakses atau diubah langsung dari luar class.

  - Overriding:

    - Method cetak_data() di class Person menimpa method bawaan dengan tambahan fungsionalitas, menunjukkan fleksibilitas penggunaan inheritance.

4. Input & Output

   ![image](https://github.com/user-attachments/assets/7f53762a-7b55-421b-b5b1-00d4fe72fdfc)

   ![image](https://github.com/user-attachments/assets/48871875-82c5-4999-ae4f-4af92308f72f)
