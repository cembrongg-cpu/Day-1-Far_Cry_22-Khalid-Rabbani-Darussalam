# Day-1-Far_Cry_22-Khalid-Rabbani-Darussalam
## 📌 Data Peserta
| **Nama Lengkap** | Khalid Rabbani Darussalam |
| **Kelompok** | FarCary 22  |

---

## 🎯 Ringkasan & Tujuan Repositori
Repositori ini disusun sebagai bentuk dokumentasi hasil mengikuti **Workshop Day 1: "Building with AI, Managing Change with GitHub"** yang dibawakan oleh **Nugi Farhan**[cite: 1, 2]. 

**Tujuan Utama:**
1. Merekap materi pembelajaran seputar *Prompt Engineering*, Git, dan GitHub[cite: 4, 5, 13, 15].
2. Mendokumentasikan pembuatan aplikasi web *Student Task Planner* menggunakan bantuan AI[cite: 7, 9, 26].
3. Mempraktikkan *version control system* untuk mengelola riwayat perubahan kode[cite: 4, 13].

---

## 🧠 Rangkuman Pembelajaran (Key Takeaways)

### 🤖 1. Prompt Engineering
Teknik menyusun instruksi yang efektif agar model AI menghasilkan respons yang presisi dan sesuai kebutuhan[cite: 5, 11].

* **Formula Prompt (Role, Task, Context, Format):**
  * **Role:** Menentukan posisi/peran AI[cite: 8, 9] (contoh: *Senior Web Developer*).
  * **Task:** Tugas mendasar yang harus dieksekusi[cite: 8, 9] (contoh: *Membuat aplikasi task planner*).
  * **Context:** Batasan, audiens sasaran, dan konteks penggunaan[cite: 8, 9] (contoh: *Untuk mahasiswa tingkat pertama*)[cite: 7, 9].
  * **Format:** Bentuk luaran yang diharapkan[cite: 8, 9] (contoh: *HTML, CSS, dan JavaScript murni*)[cite: 9].

---

### 🔄 2. Git & GitHub
* **Git:** Tool *Distributed Version Control System* (DVCS) lokal buatan Linus Torvalds (2005) untuk mencatat riwayat perubahan file[cite: 13, 15].
* **GitHub:** Layanan berbasis cloud untuk menyimpan repositori Git online dan berkolaborasi[cite: 15].

#### 🛠️ Tiga Area Kerja di Git (Git Workflow):
1. **Working Directory:** Lokasi lokal tempat kita mengubah/menambah file[cite: 14].
2. **Staging Area:** Tempat penampungan sementara sebelum perubahan disimpan secara permanen (`git add`)[cite: 14, 16].
3. **.git Directory / Repository:** Database Git yang menyimpan snapshot riwayat proyek (`git commit`)[cite: 14, 16].

---

## 💻 Daftar Perintah Git yang Dipraktikkan

```bash
# Inisialisasi & Konfigurasi Identitas
git init
git config --global user.name "Nama Anda"
git config --global user.email "email@example.com"

# Pengelolaan File & Commit
git add .
git commit -m "feat: inisialisasi struktur proyek"

# Integrasi ke GitHub
git remote add origin <URL_REPOSITORY>
git push -u origin main
git pull origin main

# Pengujian Autentikasi SSH
ssh-keygen -t ed25519 -C "email@domain.com"
ssh -T git@github.com
```[cite: 16, 17, 18, 22, 24]

---

## 💻 Aplikasi Praktik: Student Task Planner
Aplikasi yang dikembangkan selama workshop merupakan planner tugas berbasis web dengan fitur utama[cite: 9, 26]:
* Menampilkan daftar sampel tugas beserta *due date*[cite: 9].
* Menandai tugas yang sudah selesai (*mark as completed*)[cite: 9].
* Menyaring tampilan tugas (*Filter All, Pending, Completed*)[cite: 9].
* Antarmuka responsif dan menggunakan struktur *vanilla code* (HTML/CSS/JS)[cite: 9].
