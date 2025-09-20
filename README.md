# 📷 Tugas Profile Instagram PBO

Proyek ini adalah **tugas praktikum** membuat tampilan **profile Instagram** menggunakan **HTML**, **CSS**, dan framework **TailwindCSS/Bootstrap**.

---

## 📝 Deskripsi
Repository ini berisi kode HTML dan CSS untuk meniru tampilan dasar profil Instagram, termasuk:
- Foto profil
- Username dan bio singkat
- Tombol Edit Profile
- Grid postingan (12 foto)
- Layout responsif dengan TailwindCSS atau Bootstrap

---

## 🚀 Teknologi yang Digunakan
- HTML5
- CSS3
- [TailwindCSS](https://tailwindcss.com/) atau [Bootstrap](https://getbootstrap.com/)

---

## 📂 Struktur Folder
```bash
project-folder/
│
├── index.html          # Halaman utama
├── style.css           # Custom style tambahan
└── images/             # Folder berisi foto profil & postingan
```

---

## ⚙️ Cara Menggunakan
1. Clone repository ini:
   ```bash
   git clone https://github.com/username/instagram-profile.git
   ```
   *(ganti username dan nama repo sesuai GitHub kamu)*

2. Masuk ke folder proyek:
   ```bash
   cd instagram-profile
   ```

3. Buka file `index.html` di browser atau gunakan Live Server di VSCode.

---

## 📸 Menambahkan Foto Profil & Postingan
- Letakkan foto profil dan postingan di folder `images/`.
- Ubah `src` pada `<img>` di `index.html` sesuai nama file foto yang kamu masukkan.
- Contoh:
  ```html
  <img src="images/profile.jpg" alt="Foto Profil" class="rounded-full w-24 h-24">
  ```
- Untuk postingan grid:
  ```html
  <img src="images/post1.jpg" alt="Postingan 1" class="w-full h-auto object-cover">
  ```

---

## 📝 Catatan
- Pastikan link CDN Tailwind/Bootstrap sudah benar di `index.html`.
- Ukuran foto postingan sudah diatur agar mirip Instagram (square grid).
- Bisa ditambahkan efek hover atau modal untuk preview foto.

---

## 👤 Pembuat
Nama: Ramzy ahmad ardany
NIM: 2411102441206  
Mata Kuliah: Pemrograman Web / Praktikum PBO
