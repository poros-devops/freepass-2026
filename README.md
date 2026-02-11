# Freepass Challenge POROS 2026 🚀⚙️

![devops_loop](https://github.com/user-attachments/assets/2941c294-37ef-411d-a945-8d8dd44efe5c)

## Containerized CI/CD Pipeline with Orchestration for Multi-Service Application

---

## Deskripsi 🛠️
Freepass Challenge POROS 2026 menantang peserta untuk membangun **pipeline CI/CD end-to-end** hingga tahap **deployment aplikasi yang berjalan** menggunakan **container dan orkestrasi**.

Challenge ini merepresentasikan alur kerja **DevOps di dunia nyata**, mulai dari pengelolaan source code, automasi build dan test, hingga menjalankan aplikasi multi-service dalam satu sistem terorkestrasi.

Fokus utama challenge ini adalah:
- Automasi proses CI/CD dari awal hingga akhir  
- Penerapan container pada setiap service  
- Orkestrasi untuk menjalankan dan mengelola banyak service sekaligus  
- Integrasi antar service hingga aplikasi dapat diakses dan digunakan  

⚠️ **Setiap peserta freepass wajib menggunakan project yang berbeda.**

---

## Kriteria Umum 📌

### Aplikasi Multi-Service (Wajib)
Project yang dibuat **wajib terdiri dari minimal 3 service**, misalnya:
- Frontend  
- Backend  
- Database  

Service tambahan seperti authentication service, worker, cache, atau message broker diperbolehkan.

Ketentuan umum:
- Setiap service berjalan secara terpisah
- Seluruh service dikemas dalam container
- Antar service saling terhubung dan berkomunikasi

Teknologi yang digunakan **bebas**, contoh:
- Frontend: React, Vue, Svelte, dsb  
- Backend: Node.js, Spring Boot, Flask, Laravel, dsb  
- Database: MySQL, PostgreSQL, MongoDB, dsb  

Aplikasi boleh hasil pengembangan sendiri atau adaptasi, **namun tidak boleh sama antar peserta**.

---

### Pipeline CI/CD 🔄
Peserta harus membangun pipeline CI/CD yang berjalan otomatis ketika terjadi perubahan kode pada repository.

Pipeline minimal mencakup:
- Proses **build** container image untuk setiap service
- Proses **test**, minimal pada sisi backend
- Proses **deploy** hingga aplikasi benar-benar berjalan

Pipeline **tidak berhenti di build**, tetapi harus menghasilkan aplikasi yang aktif dan dapat diakses melalui sistem orkestrasi.

Tools CI/CD **bebas digunakan**, contoh:
- Jenkins  
- GitHub Actions  
- GitLab CI  

---

### Containerization & Orchestration 🐳☸️
Seluruh service wajib dijalankan dalam container dan dikelola menggunakan **orkestrasi container**.

Ketentuan:
- Orkestrasi **wajib digunakan**
- Kubernetes **tidak wajib**
- Peserta bebas memilih tools orkestrasi, seperti:
  - Docker Compose  
  - Kubernetes  
  - Orkestrator lain yang relevan  

Sistem yang dibangun harus menunjukkan bahwa:
- Semua service berjalan bersamaan
- Komunikasi antar service berjalan dengan baik
- Aplikasi dapat diakses dan digunakan

---

## Kriteria Penilaian 📊

### Pipeline CI/CD
Pipeline dinilai berdasarkan:
- Kemampuan berjalan otomatis saat ada perubahan kode
- Alur build, test, dan deploy yang tersusun dengan jelas
- Log pipeline yang informatif dan mudah dipahami

---

### Containerization & Orchestration
Implementasi container dan orkestrasi dinilai dari:
- Seluruh service berhasil dijalankan dalam container
- Minimal tiga service terhubung dalam satu sistem orkestrasi
- Aplikasi berjalan dan dapat diakses

---

### Dokumentasi 📄
Dokumentasi merupakan bagian penting dari challenge ini.

Peserta wajib menyediakan:
- **README.md** yang menjelaskan:
  - Arsitektur aplikasi
  - Struktur repository
  - Cara menjalankan pipeline dan deployment
- **Laporan PDF** yang menjelaskan secara rinci:
  - Alur CI/CD pipeline
  - Proses containerization
  - Cara kerja orkestrasi dan deployment
  - Bukti keberhasilan setiap proses dari pipeline CI/CD sampai deployment

---

### Inovasi Tambahan (Opsional) 🌟
Peserta dapat menambahkan inovasi sebagai nilai tambah, seperti:
- Monitoring pipeline atau aplikasi
- Centralized logging
- Load balancing
- Deployment ke cloud atau environment staging
- Optimasi ukuran image container

---

## Pengumpulan 📤
- Source code diunggah ke **GitHub**
- Repository **wajib public**
- Sertakan link repository pada laporan

---

## Deadline ⏳
- **Start**: 11 Februari 2026, 12.30 🕕
- **End**: 18 Februari 2026 , 17.00 ⏰

---

## Contact Person 📞
 | Nama  | Contact |
|-------|----------|
| 📱 **Aldura** | [Whatsapp](https://wa.me/+6281333093230)   |
| 📱 **Hasbi** | [Whatsapp](https://wa.me/+6287868287838)  |

---

## Catatan Penting ⚠️
- Minimal **3 service (wajib)**
- Orkestrasi **wajib**
- Project **harus berbeda untuk setiap peserta**
