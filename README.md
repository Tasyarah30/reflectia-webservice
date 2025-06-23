# 📔 Reflectia - Mobile Diary App with Web Service Integration

Reflectia adalah aplikasi diary pribadi berbasis mobile yang terhubung dengan web service (API). Aplikasi ini dibangun menggunakan Flutter dan menggunakan backend PHP + MySQL sebagai sumber data.

Reflectia is a mobile diary app integrated with a RESTful web service. Built using Flutter and a PHP + MySQL backend.

---

## 🔧 Fitur Aplikasi | Features

- ✅ Menulis dan menyimpan entri diary
- ✅ Melihat daftar entri sebelumnya
- ✅ Edit & hapus entri
- ✅ Pencarian entri berdasarkan tanggal atau kata kunci
- ✅ Autentikasi pengguna (login/register)
- ✅ Terhubung dengan REST API (GET, POST, PUT, DELETE)

---

## 🛠️ Teknologi yang Digunakan | Technologies Used

### Mobile (Client)
- **Flutter** (Dart)
- **HTTP Package** (API Call)
- **Provider / GetX** (state management, jika digunakan)
- **UI Design**: Material Design

### Backend (API)
- **PHP** (Native or Framework)
- **MySQL**
- **RESTful API**
- **JSON Response**
- **Postman** (untuk testing API)

---

## 🗃️ Struktur Backend (Contoh)

- `api/` – Folder API
  - `get_entries.php`
  - `add_entry.php`
  - `update_entry.php`
  - `delete_entry.php`
- `config/` – Koneksi database
- `db.php` – File koneksi
- `readme_api.md` – Dokumentasi endpoint

---

## 🎯 Tujuan Proyek | Project Purpose

Proyek ini bertujuan untuk menerapkan pengembangan aplikasi mobile dengan teknik **client-server** menggunakan **REST API**, serta membangun backend sederhana untuk manajemen data diary pribadi.

This project aims to practice building a client-server mobile application using REST API, and to implement a simple backend for diary data management.

---

## 👩‍💻 Developer

**Tasya Rahmadina Zahrah**  
Universitas BSI – Sistem Informasi  
Proyek Mata Kuliah Pemrograman Mobile dengan Web Service
