# 📚 Student Grade Management System

**Student Grade Management System** adalah aplikasi desktop berbasis **Java Swing GUI** yang digunakan untuk mengelola data siswa dan nilai akademik secara sederhana dan terstruktur.

Aplikasi ini memungkinkan pengguna untuk **menambah, mengedit, menghapus data siswa**, serta **menginput dan mengubah nilai mata pelajaran** melalui antarmuka grafis yang mudah digunakan.

Project ini dikembangkan sebagai bagian dari **tugas akademik sekaligus portfolio pengembangan aplikasi desktop menggunakan Java dan konsep Object-Oriented Programming (OOP).**

---

# 📌 Project Overview

Aplikasi ini dirancang untuk membantu proses pengelolaan data siswa di lingkungan pendidikan dengan menyediakan fitur manajemen data yang terintegrasi dalam satu sistem.

Fitur utama aplikasi meliputi:

* Manajemen data siswa
* Input nilai mata pelajaran
* Edit dan update nilai siswa
* Tampilan data siswa dalam tabel
* Antarmuka GUI yang interaktif

Project ini mengimplementasikan konsep **CRUD (Create, Read, Update, Delete)** menggunakan pendekatan **Object-Oriented Programming (OOP)**.

---

# 🚀 Features

## 👨‍🎓 Student Management

Pengguna dapat mengelola data siswa dengan fitur:

* Menambahkan data siswa baru
* Mengedit data siswa
* Menghapus data siswa
* Menyimpan informasi siswa seperti:

  * Nama
  * NIS (Nomor Induk Siswa)
  * Kelas
  * Foto siswa

---

## 📊 Grade Management

Sistem memungkinkan pengelolaan nilai siswa untuk beberapa mata pelajaran dengan fitur:

* Input nilai siswa
* Edit nilai siswa
* Menyimpan nilai berdasarkan siswa
* Menampilkan nilai dalam tabel

---

## 📋 Data Visualization

Semua data siswa dan nilai ditampilkan dalam bentuk **tabel GUI (JTable)** sehingga memudahkan pengguna dalam membaca dan mengelola data.

---

# 🧰 Tech Stack

| Technology | Description                 |
| ---------- | --------------------------- |
| Java       | Programming Language        |
| Java Swing | GUI Framework               |
| OOP        | Object-Oriented Programming |
| JTable     | Data Table Visualization    |

---

# 📁 Project Structure

```id="o36vrb"
Student-Grade-Management/
│
├── ManajemenGui.java
├── Manajemen.java
├── Siswa.java
├── Main.java
└── README.md
```

---

# ⚙️ System Requirements

Untuk menjalankan aplikasi ini diperlukan:

* **Java Development Kit (JDK) 8** atau lebih baru
* IDE Java seperti:

  * IntelliJ IDEA
  * Eclipse
  * NetBeans

### Supported Operating Systems

* Windows
* macOS
* Linux

---

# 🧩 Code Architecture

## ManajemenGui.java

Kelas ini bertanggung jawab untuk membangun **antarmuka pengguna (GUI)** menggunakan Java Swing.

Fungsi utama:

* Menampilkan form input siswa
* Menampilkan tabel data siswa
* Menyediakan tombol operasi CRUD
* Mengelola interaksi pengguna

Komponen GUI yang digunakan antara lain:

* `JPanel`
* `JButton`
* `JTable`
* `JTextField`
* `JComboBox`

---

## Manajemen.java

Kelas ini berfungsi sebagai **logic layer** yang mengelola seluruh data siswa dan nilai.

Fungsi utama:

* Menyimpan daftar siswa
* Menambah siswa
* Mengedit siswa
* Menghapus siswa
* Mengelola nilai siswa

Data disimpan menggunakan struktur **List / ArrayList**.

---

## Siswa.java

Kelas ini merepresentasikan **model data siswa**.

Data yang disimpan meliputi:

* ID siswa
* Nama
* NIS
* Kelas
* Foto
* Nilai mata pelajaran

Kelas ini menyediakan **getter dan setter methods** untuk mengakses dan memperbarui data.

---

## Main.java

Merupakan **entry point aplikasi**.

Fungsi utama:

* Menjalankan program
* Memanggil kelas `ManajemenGui`
* Menampilkan GUI aplikasi

---

# ▶️ How to Run

## 1 Clone Repository

```id="1opj2j"
git clone https://github.com/username/student-grade-management.git
```

## 2 Open Project in IDE

Buka project menggunakan IDE Java seperti:

* IntelliJ IDEA
* Eclipse
* NetBeans

## 3 Run Application

Jalankan file berikut:

```id="s90j74"
Main.java
```

Aplikasi GUI akan terbuka dan siap digunakan.

---

# 🧠 Application Workflow

Setelah aplikasi berjalan, pengguna dapat melakukan beberapa operasi berikut:

### Tambah Siswa

1. Pilih menu **Tambah Siswa**
2. Masukkan data siswa
3. Klik **Tambah Siswa**

### Edit Siswa

1. Pilih menu **Edit Siswa**
2. Pilih siswa berdasarkan ID
3. Ubah data
4. Klik **Edit Siswa**

### Hapus Siswa

1. Pilih menu **Hapus Siswa**
2. Pilih siswa dari daftar
3. Klik **Hapus Siswa**

### Input Nilai

1. Pilih menu **Input Nilai**
2. Pilih siswa
3. Masukkan nilai mata pelajaran
4. Klik **Simpan**

### Edit Nilai

1. Pilih menu **Edit Nilai**
2. Pilih siswa
3. Perbarui nilai
4. Klik **Edit Nilai**

### Lihat Nilai

1. Pilih menu **Lihat Nilai**
2. Sistem akan menampilkan tabel nilai siswa

---

# 🎯 Project Purpose

Project ini dibuat sebagai:

* Implementasi **Java Swing Desktop Application**
* Latihan konsep **Object-Oriented Programming (OOP)**
* Implementasi **CRUD Data Management**
* Portfolio project dalam pengembangan aplikasi desktop

---

# 👨‍💻 Author

**Mukhamad Sofyan**
GitHub: https://github.com/mukhamadsofyan

---

# 🤝 Contributors

Project ini dikembangkan oleh:

* **Mukhamad Sofyan**
* **Moh. Ravlindo Saputra**

---

# 📊 Languages Used

* HTML — 76.0%
* Java — 10.0%
* JavaScript — 7.7%
* CSS — 6.3%

---

# 📄 License

Project ini dibuat untuk **tujuan pembelajaran dan portfolio akademik**.
