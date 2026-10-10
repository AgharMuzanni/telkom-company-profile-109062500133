# Telkom University Company Profile - Praktikum 
 
Project simulasi HTML, CSS, PHP native, MySQL/MariaDB, dan Git. 

Perubahan ini dibuat dari simulasi Laptop B.

  ## Dokumentasi Simulasi Merge Conflict

- **Penyebab Conflict**: Terjadi bentrokan saat merge branch `conflict-navbar` ke `main` karena kedua branch mengubah baris kode yang sama pada file `includes/header.php` (perubahan teks label menu navigasi).
- **Langkah Penyelesaian**:
  1. Buka file `includes/header.php` yang mengalami conflict.
  2. Menghapus marker conflict (`<<<<<<<`, `=======`, `>>>>>>>`).
  3. Memilih teks label final yang digunakan.
  4. Menyimpan file, men-stage dengan `git add includes/header.php`, lalu membuat commit.