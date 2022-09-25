NAMA : NURHALIZA

NIM : 2110131120007

---

#### PERBEDAAN STRUKTUR SISTEM OPERASI : STRUKTUR SEDERHANA, SISTEM BERLAPIS, DAN KERNEL MIKRO

1. STRUKTUR SEDERHANA
   * Semua komponen sistem operasi bercampur
   * semua rutin sistem operasi dapat mengakses rutin yang lainnya
   * tidak ada pemisah yang jelas antara aplikasi dan sistem operasi

2. SISTEM BERLAPIS
   * komponen sistem operasi di kelompokkan dalam lapisan - lapisan(layered)
   * suatu lapisan hanya boleh menggunakan lapisan di bawahnya
   * lapisan atas menangani interface user, lapisan bawah menangani detil operasi perangkat keras

3. MIKRO KERNEL
   * menyusun sistem operasi dengan menghapus semua komponen yang tidak esensial dari kernel, dan mengimplementasikannya sebagai sistem program dan level pengguna
   * menyediakan hanya sekumpulan kecil abstraksi perangkat keras sederhana, dan menggunakan aplikasi-aplikasi yang disebut sebagai server untuk menyediakan fungsi - fungsi lainnya.
   * mendukung fasilitas komunikasi antara program klien 
