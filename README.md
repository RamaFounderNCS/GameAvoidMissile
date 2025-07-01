
# 🎮 GameAvoidMissile

**GameAvoidMissile** adalah sebuah browser game sederhana buatan *Newbie Cyber Security*. Di dalam game ini, pemain harus mengendalikan objek untuk menghindari rudal yang terus muncul. Game ini dibuat dengan HTML, CSS, dan JavaScript.

---

## 📌 Table of Contents
1. [Demo](#-demo)
2. [Fitur](#-fitur)
3. [Screenshot](#-screenshot)
4. [Instalasi & Cara Main](#-instalasi--cara-main)
5. [Cara Bermain](#-cara-bermain)
6. [Struktur Folder](#-struktur-folder)
7. [Teknologi](#-teknologi)
8. [Kontribusi](#-kontribusi)
9. [Lisensi](#-lisensi)
10. [Kontak](#-kontak)

---

## 🔗 Demo
Game ini dapat dimainkan langsung di halaman GitHub Pages berikut:  
https://ramafounderncs.github.io/GameAvoidMissile/

---

## 🧩 Fitur
- Gameplay sederhana: hindari rudal yang jatuh (atau muncul).
- Penambahan skor dinamis.
- Game over ketika tertabrak rudal.
- Reset dan restart otomatis setelah game over.
- Desain minimalis dan responsif.

---

## ⚙️ Instalasi & Cara Main
1. **Clone repository**  
   ```bash
   git clone https://github.com/RamaFounderNCS/GameAvoidMissile.git
   ```
2. **Masuk ke direktori**  
   ```bash
   cd GameAvoidMissile
   ```
3. **Buka `index.html`** menggunakan browser:
   - Klik dua kali file `index.html`, atau
   - Jalankan dari terminal (Linux/Mac):
     ```bash
     open index.html
     ```
     atau (Windows):
     ```bash
     start index.html
     ```

---

## 🎮 Cara Bermain
- Gunakan **tombol kiri/kanan** atau **A/D** untuk menggerakkan objek.
- Hindari rudal yang turun dari atas layar.
- Setiap kali berhasil melewati rudal, **skor bertambah**.
- Saat terkena rudal → muncul *Game Over*, dan pemain bisa restart.

---

## 🗂️ Struktur Folder

```
/
├── index.html      ← file utama
├── styles.css      ← jika ada untuk styling
├── script.js       ← jika ada file JavaScript eksternal
└── assets/         ← folder untuk gambar/audio (opsional)
```

> Jika seluruh kode ditempatkan di `index.html`, cukup salin bagian `<style>` dan `<script>` ke file eksternal untuk pemisahan kode.

---

## 🛠️ Teknologi
- **HTML5** – Struktur halaman
- **CSS3** – Styling dasar
- **JavaScript** – Logika game (pengendalian objek, deteksi tabrakan, skor, dsb.)
- (Opsional) **Canvas API** – jika game menggunakan kanvas

---

## 🤝 Kontribusi
Terima kasih jika kamu mau berkontribusi!  
1. **Fork** repo ini.  
2. Buat **branch** fitur kamu:  
   ```bash
   git checkout -b nama-fitur-anda
   ```
3. **Commit** perubahan:  
   ```bash
   git commit -m "Tambah fitur X"
   ```
4. **Push** ke branch kamu:  
   ```bash
   git push origin nama-fitur-anda
   ```
5. Buat **pull request** di GitHub.  

**Fitur yang bisa ditambah**:
- Tingkat kesulitan dengan level (mudah → sulit).
- Power-up (misal: perisai sementara).
- Leaderboard atau penyimpanan skor lokal.
- Musik/dengan efek suara.

---

## 📄 Lisensi
Project ini dilisensikan di bawah **MIT License**—boleh digunakan, dimodifikasi, dan dibagikan.  
(Sertakan file `LICENSE` jika perlu.)

---

## 📬 Kontak
Dibuat oleh **Newbie Cyber Security** (alias RamaFounderNCS).  
Untuk saran/masukan:
- GitHub: [RamaFounderNCS](https://github.com/RamaFounderNCS)  
- Email: offcncs@gmail.com

---

## 🚀 Terima Kasih!
Selamat bermain dan semoga menyenangkan!  
Jangan ragu untuk kontribusi agar game ini semakin seru 🙌
