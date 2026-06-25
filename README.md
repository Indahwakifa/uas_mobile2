# uas_mobile2

# NAMA : INDAH WAFIKAH

# NIM : 312410559

# KELAS: I241E


# linkfigma : https://www.figma.com/design/MDewN9mHFkcg2bUf0GVYLA/Untitled?node-id=280-23&t=Sfw8ToSQpc7DTtj0-1
# clickup : https://app.clickup.com/90181885942/v/li/901816393651
# youtobe : https://youtube.com/shorts/VLKTdD7HRLY?si=YoQarWMafIP9uzBG

# 📚 Cerita Nusantara v1.0 – Digital Folklore Application

## 👩‍🎓 Identitas Mahasiswa

**Nama : Indah Wafikah**  
**NIM : 312410559**  
**Kelas : I241E**  
**Mata Kuliah : Pemrograman Mobile**

---

# 📖 Deskripsi Aplikasi

Cerita Nusantara merupakan aplikasi mobile berbasis Android yang menyediakan kumpulan cerita rakyat Indonesia dalam bentuk digital. Aplikasi ini dirancang untuk membantu pengguna mengenal berbagai cerita daerah secara lebih mudah, menarik, dan praktis melalui perangkat smartphone.

Melalui aplikasi ini, pengguna dapat membaca cerita rakyat dari berbagai daerah di Indonesia, melihat detail cerita secara lengkap, serta menyimpan cerita favorit untuk dibaca kembali di kemudian hari.

Aplikasi ini dikembangkan sebagai proyek UAS Mata Kuliah Pemrograman Mobile Semester 4.

---

# 🎯 Tujuan Pengembangan

Tujuan pengembangan aplikasi ini adalah:

- Melestarikan budaya Indonesia melalui media digital.
- Mempermudah akses masyarakat terhadap cerita rakyat nusantara.
- Menyediakan media pembelajaran yang interaktif dan menarik.
- Mengimplementasikan konsep pengembangan aplikasi Android menggunakan Flutter.
- Memenuhi tugas akhir Mata Kuliah Pemrograman Mobile.

---

# 🚀 Fitur Utama

### 📚 Koleksi Cerita

Menampilkan berbagai cerita rakyat Indonesia dalam satu aplikasi.

### 📖 Detail Cerita

Pengguna dapat membaca isi cerita secara lengkap.

### ⭐ Favorite Story

Menyimpan cerita favorit untuk dibaca kembali.

### 🎨 User Friendly Interface

Tampilan sederhana, menarik, dan mudah digunakan.

### ⚡ Fast Navigation

Navigasi antar halaman cepat dan responsif.

---

# 🛠️ Teknologi yang Digunakan

| Teknologi | Fungsi |
|------------|---------|
| Flutter | Framework pengembangan aplikasi |
| Dart | Bahasa pemrograman utama |
| Material Design | Desain antarmuka aplikasi |
| Shared Preferences | Penyimpanan data sederhana |
| Android Studio | IDE pengembangan |
| GitHub | Version Control |

---

# 🏗️ Arsitektur Sistem

Aplikasi menggunakan arsitektur sederhana berbasis Flutter.

## 1. Presentation Layer

Menampilkan seluruh antarmuka pengguna.

- Splash Screen
- Home Screen
- Detail Story Screen
- Favorite Screen

## 2. Business Logic Layer

Mengelola proses:

- Menampilkan daftar cerita
- Menampilkan detail cerita
- Menyimpan favorit
- Menghapus favorit

## 3. Data Layer

Mengelola data cerita yang digunakan aplikasi.

---

# 📱 Flow Aplikasi

```text
Splash Screen
      │
      ▼
Halaman Selamat Datang
      │
      ▼
Koleksi Cerita
      │
 ┌────┴─────┐
 ▼          ▼
Detail      Favorit
Cerita      Story
```

---

# 📑 Use Case Diagram

```text
                +-------------+
                |  Pengguna   |
                +-------------+
                       |
    ------------------------------------
    |                |                |
    ▼                ▼                ▼

Melihat       Membaca Detail     Menyimpan
Daftar Cerita Cerita             Favorit

                       |
                       ▼

               Melihat Favorit
```

---

# 🔄 Activity Diagram

## Membaca Cerita

```text
Start
  │
  ▼
Buka Aplikasi
  │
  ▼
Halaman Utama
  │
  ▼
Pilih Cerita
  │
  ▼
Tampilkan Detail Cerita
  │
  ▼
Baca Cerita
  │
  ▼
Selesai
```

---

## Menambahkan Cerita ke Favorit

```text
Start
  │
  ▼
Pilih Cerita
  │
  ▼
Buka Detail Cerita
  │
  ▼
Klik Tombol Favorit
  │
  ▼
Data Disimpan
  │
  ▼
Muncul di Halaman Favorit
  │
  ▼
Selesai
```

---

# 🖼️ Screenshot UI

## 1. Splash Screen

Menampilkan logo aplikasi saat pertama kali dijalankan.

(<img width="194" height="118" alt="image" src="https://github.com/user-attachments/assets/19b33ee8-08d9-4bc0-8184-37099112c7c1" />


---

## 2. Halaman Selamat Datang

Menampilkan ucapan selamat datang dan ilustrasi buku.

![Welcome Screen](<img width="50" height="104" alt="Screenshot 2026-06-25 212758" src="https://github.com/user-attachments/assets/5d4e28be-2678-4ea9-9d71-f8e486a4d4d6" />
)

---

## 3. Halaman Koleksi Cerita

Menampilkan daftar cerita rakyat yang tersedia.

### Daftar Cerita:

- Malin Kundang
- Sangkuriang
- Legenda Danau Toba
- Timun Mas
- Bawang Merah Bawang Putih

![Story Collection](<img width="44" height="104" alt="image" src="https://github.com/user-attachments/assets/c871c6c9-1365-4891-9960-b53f07305c68" />
)

---

## 4. Halaman Detail Cerita

Menampilkan isi lengkap cerita yang dipilih pengguna.

![Story Detail](<img width="46" height="104" alt="image" src="https://github.com/user-attachments/assets/c78c3879-40d4-4f7d-bdec-13cba2852cb9" />
)

---

## 5. Halaman Favorit

Menampilkan daftar cerita yang telah disimpan sebagai favorit.

![Favorite Story](<img width="49" height="102" alt="image" src="https://github.com/user-attachments/assets/b951e7c0-03fc-4d3a-98ad-efeea4f868a2" />
)

---

# 📂 Struktur Folder Project

```text
lib/
│
├── main.dart
│
├── screens/
│   ├── splash_screen.dart
│   ├── welcome_screen.dart
│   ├── home_screen.dart
│   ├── detail_story_screen.dart
│   └── favorite_screen.dart
│
├── models/
│   └── story_model.dart
│
├── data/
│   └── story_data.dart
│
└── widgets/
    └── custom_widget.dart
```

---

# 📊 Pengujian Aplikasi

Pengujian dilakukan menggunakan metode Black Box Testing.

| No | Fitur | Hasil |
|----|--------|--------|
| 1 | Splash Screen | Berhasil |
| 2 | Welcome Screen | Berhasil |
| 3 | Menampilkan Daftar Cerita | Berhasil |
| 4 | Membuka Detail Cerita | Berhasil |
| 5 | Menambah Favorit | Berhasil |
| 6 | Menampilkan Favorit | Berhasil |

---

# ⭐ Keunggulan Aplikasi

- Tampilan sederhana dan mudah dipahami.
- Mendukung pelestarian budaya Indonesia.
- Ringan dan cepat digunakan.
- Cocok untuk media pembelajaran.
- Navigasi mudah digunakan oleh semua kalangan.

---

# 🔮 Pengembangan Selanjutnya

Beberapa fitur yang dapat dikembangkan pada versi berikutnya:

- Pencarian cerita.
- Kategori cerita berdasarkan daerah.
- Audio storytelling.
- Mode gelap (Dark Mode).
- Bookmark halaman terakhir.
- Database online menggunakan Firebase.

---

# 🎓 Kesimpulan

Cerita Nusantara merupakan aplikasi mobile berbasis Android yang bertujuan untuk memperkenalkan serta melestarikan cerita rakyat Indonesia melalui media digital. Dengan fitur koleksi cerita, detail cerita, dan favorit story, aplikasi ini dapat menjadi sarana edukasi sekaligus hiburan yang mudah diakses oleh masyarakat.

---
