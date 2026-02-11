# Freepass Challenge POROS 2026 🚀⚙️

![devops_loop](https://github.com/user-attachments/assets/2941c294-37ef-411d-a945-8d8dd44efe5c)

## Containerized CI/CD Pipeline with Orchestration for Multi-Service Application

---

## Deskripsi 🛠️

Freepass Challenge POROS 2026 menantang peserta untuk membangun **pipeline CI/CD end-to-end** hingga tahap **deployment aplikasi yang benar-benar berjalan**, dengan memanfaatkan **containerization dan orchestration**.

Challenge ini merepresentasikan praktik **DevOps di dunia nyata**, mulai dari pengelolaan source code, otomatisasi proses build dan testing, hingga menjalankan aplikasi multi-service dalam satu sistem yang terorkestrasi.

Fokus utama challenge ini meliputi:

- Otomatisasi proses CI/CD secara menyeluruh  
- Penerapan container pada setiap service  
- Penggunaan orkestrasi untuk menjalankan dan mengelola beberapa service sekaligus  
- Integrasi antar service hingga aplikasi dapat diakses dan digunakan dengan baik  

⚠️ **Setiap peserta wajib menggunakan project yang berbeda.**

---

## Kriteria Umum 📌

### 1️⃣ Aplikasi Multi-Service (Wajib)

Project yang dibuat **wajib terdiri dari minimal 3 service**, contohnya:

- Frontend  
- Backend  
- Database  

Service tambahan seperti authentication service, worker, cache, atau message broker diperbolehkan.

Ketentuan:

- Setiap service harus berjalan secara terpisah  
- Seluruh service wajib dikemas dalam container  
- Antar service harus saling terhubung dan dapat berkomunikasi dengan baik  

Teknologi yang digunakan **bebas**, misalnya:

- Frontend: React, Vue, Svelte, dan lainnya  
- Backend: Node.js, Spring Boot, Flask, Laravel, dan lainnya  
- Database: MySQL, PostgreSQL, MongoDB, dan lainnya  

Aplikasi boleh dikembangkan sendiri atau hasil adaptasi, **namun tidak boleh sama antar peserta**.

---

### 2️⃣ Pipeline CI/CD 🔄

Peserta wajib membangun pipeline CI/CD yang berjalan otomatis setiap kali terjadi perubahan kode pada repository.

Pipeline minimal harus mencakup:

- Proses **build** container image untuk setiap service  
- Proses **test** (minimal pada sisi backend)  
- Proses **deploy** hingga aplikasi benar-benar berjalan  

Pipeline **tidak boleh berhenti pada tahap build saja**, tetapi harus menghasilkan aplikasi yang aktif dan dapat diakses melalui sistem orkestrasi.

Tools CI/CD yang digunakan **bebas**, seperti:

- Jenkins  
- GitHub Actions  
- GitLab CI  
- atau tools sejenis lainnya  

---

### 3️⃣ Containerization & Orchestration 🐳☸️

Seluruh service wajib dijalankan dalam container dan dikelola menggunakan sistem orkestrasi container.

Ketentuan:

- Penggunaan orkestrasi **wajib**  
- Kubernetes **tidak diwajibkan**  
- Peserta bebas memilih tools orkestrasi, seperti:
  - Docker Compose  
  - Kubernetes  
  - atau orkestrator lain yang relevan  

Sistem yang dibangun harus menunjukkan bahwa:

- Semua service dapat berjalan secara bersamaan  
- Komunikasi antar service berjalan dengan baik  
- Aplikasi dapat diakses dan digunakan secara normal  

---

## Kriteria Penilaian 📊

### 🔹 Pipeline CI/CD

Penilaian pipeline mencakup:

- Kemampuan berjalan otomatis saat terjadi perubahan kode  
- Alur build, test, dan deploy yang tersusun dengan jelas  
- Log pipeline yang informatif dan mudah dipahami  

---

### 🔹 Containerization & Orchestration

Penilaian implementasi container dan orkestrasi meliputi:

- Seluruh service berhasil dijalankan dalam container  
- Minimal tiga service terhubung dalam satu sistem orkestrasi  
- Aplikasi berjalan dengan baik dan dapat diakses  

---

### 🔹 Dokumentasi 📄

Dokumentasi merupakan bagian penting dari challenge ini.

Peserta wajib menyediakan:

#### 📌 README.md

Berisi:

- Penjelasan arsitektur aplikasi  
- Struktur repository  
- Cara menjalankan pipeline dan proses deployment  

#### 📌 Laporan PDF

Berisi penjelasan rinci mengenai:

- Alur CI/CD pipeline  
- Proses containerization  
- Cara kerja orkestrasi dan deployment  
- Bukti keberhasilan setiap tahapan, mulai dari pipeline hingga aplikasi berhasil berjalan  

---

### 🔹 Inovasi Tambahan (Opsional) 🌟

Peserta dapat menambahkan fitur tambahan sebagai nilai plus, seperti:

- Monitoring pipeline atau aplikasi  
- Centralized logging  
- Load balancing  
- Deployment ke cloud atau environment staging  
- Optimasi ukuran image container  

---

## Pengumpulan 📤

- Source code diunggah ke **GitHub**  
- Repository **wajib dalam keadaan public**  
- Sertakan link repository pada laporan PDF  

---

## Deadline ⏳

- **Start**: 11 Februari 2026, 12.30  
- **End**: 18 Februari 2026, 17.00  

---

## Contact Person 📞

| Nama | Contact |
|------|----------|
| 📱 **Aldura** | [Whatsapp](https://wa.me/+6281333093230) |
| 📱 **Hasbi** | [Whatsapp](https://wa.me/+6287868287838) |

---

## Catatan Penting ⚠️

- Minimal **3 service (wajib)**  
- Orkestrasi **wajib digunakan**  
- Project **harus berbeda untuk setiap peserta**  
