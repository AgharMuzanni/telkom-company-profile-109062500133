# Telkom University Company Profile - Praktikum 
 
Project simulasi HTML, CSS, PHP native, MySQL/MariaDB, dan Git. 

Perubahan ini dibuat dari simulasi Laptop B.

## Dokumentasi Simulasi Merge Conflict

- **Penyebab Conflict**: Terjadi bentrokan saat merge branch `conflict-navbar` ke `main` karena kedua branch mengubah baris kode yang sama pada file `includes/header.php` (perubahan teks label menu navigasi)[cite: 37, 38].
- **Langkah Penyelesaian**:
  1. Buka file `includes/header.php` yang mengalami conflict[cite: 37].
  2. Menghapus marker conflict (`<<<<<<<`, `=======`, `>>>>>>>`)[cite: 38].
  3. Memilih teks label final yang digunakan[cite: 38].
  4. Menyimpan file, men-stage dengan `git add includes/header.php`, lalu membuat commit penyelesaian (`git commit -m "merge: selesaikan conflict navbar"`)[cite: 38].