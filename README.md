# Freepass Challenge POROS 2026 🚀⚙️

![devops_loop](https://github.com/user-attachments/assets/2941c294-37ef-411d-a945-8d8dd44efe5c)

## Containerized CI/CD Pipeline with Orchestration for Multi-Service Application

---

## Deskripsi 🛠️

Freepass Challenge POROS 2026 menantang peserta untuk membangun **pipeline CI/CD end-to-end** hingga tahap **deployment aplikasi yang benar-benar berjalan**, menggunakan prinsip containerization dan orchestration.

Challenge ini merepresentasikan praktik DevOps di dunia nyata, mulai dari:

- Manajemen source code
- Automasi build dan testing
- Publishing container image
- Deployment terorkestrasi
- Aplikasi berjalan dan dapat diakses

⚠️ **Setiap peserta wajib menggunakan project yang berbeda.**

---

# Kriteria Umum 📌

## 1️⃣ Aplikasi Multi-Service (Wajib)

Project wajib terdiri dari **minimal 3 service**, contohnya:

- Frontend
- Backend
- Database

Service tambahan diperbolehkan:
- Authentication Service
- Cache (Redis)
- Message Broker
- Worker
- API Gateway
- dll.

### Ketentuan:

- Setiap service berjalan secara terpisah
- Seluruh service dikemas dalam container
- Antar service saling terhubung melalui network internal
- Aplikasi dapat diakses melalui browser atau endpoint API

Teknologi bebas digunakan.

---

## 2️⃣ Pipeline CI/CD 🔄

Pipeline harus berjalan otomatis ketika terjadi perubahan kode (push / pull request) pada repository.

### Pipeline minimal wajib mencakup:

1. **Build Stage**
   - Build container image untuk setiap service
   - Menggunakan Dockerfile yang terpisah
   - Tidak diperbolehkan manual build di luar pipeline

2. **Test Stage**
   - Minimal terdapat automated test pada backend
   - Test dijalankan di dalam pipeline
   - Pipeline harus gagal jika test gagal

3. **Push Image Stage**
   - Image wajib di-push ke container registry
   - Registry bebas (Docker Hub, GHCR, GitLab Registry, dll.)

4. **Deploy Stage**
   - Deployment dilakukan secara otomatis dari pipeline
   - Deployment mengambil image dari registry (bukan build ulang di server)
   - Setelah deploy, aplikasi harus benar-benar berjalan

---

## 3️⃣ Target Deployment 🌐

Deployment boleh dilakukan pada:

- Local VM
- Self-hosted runner
- VPS
- Cloud environment

Namun wajib memenuhi:

- Aplikasi dapat diakses (browser atau API endpoint)
- Semua service berjalan bersamaan
- Terdapat bukti screenshot/log bahwa sistem berhasil berjalan

---

## 4️⃣ Containerization & Orchestration 🐳☸️

Seluruh service wajib dikelola menggunakan sistem orkestrasi.

### Ketentuan:

- Orkestrasi wajib digunakan
- Kubernetes tidak wajib
- Boleh menggunakan:
  - Docker Compose
  - Kubernetes
  - Orchestrator lain yang relevan

### Minimal Requirement Orkestrasi

Jika menggunakan Docker Compose, wajib terdapat:

- Custom network
- Volume (untuk database atau persistence)
- Environment variables
- Depends_on / service dependency
- Konfigurasi yang jelas antar service

Jika menggunakan Kubernetes, minimal terdapat:

- Deployment
- Service
- Konfigurasi environment
- Pod berjalan dengan benar

---

# Kriteria Penilaian 📊

## 1️⃣ Pipeline CI/CD (35%)

- Pipeline berjalan otomatis
- Terdapat stage build, test, push, deploy
- Menggunakan registry
- Log pipeline jelas dan informatif
- Deployment benar-benar terjadi dari pipeline

---

## 2️⃣ Containerization & Orchestration (30%)

- Seluruh service berjalan dalam container
- Minimal 3 service saling terhubung
- Konfigurasi orkestrasi benar
- Aplikasi dapat diakses dan digunakan

---

## 3️⃣ Dokumentasi (20%)

Peserta wajib menyediakan:

### README.md

Berisi:
- Penjelasan arsitektur aplikasi
- Diagram arsitektur (opsional tapi disarankan)
- Struktur repository
- Penjelasan alur CI/CD
- Cara menjalankan sistem secara manual (jika diperlukan)

### Laporan PDF

Berisi:
- Penjelasan detail pipeline
- Screenshot setiap stage pipeline
- Bukti image berhasil di-push ke registry
- Bukti deployment berhasil
- Bukti aplikasi berjalan (browser/API response)

---

## 4️⃣ Inovasi Tambahan (15%) 🌟

Nilai tambahan diberikan jika peserta mengimplementasikan:

- Monitoring (Prometheus/Grafana)
- Centralized logging
- Reverse proxy (Nginx/Traefik)
- Load balancing
- Health check
- Deployment ke cloud
- Optimasi ukuran image
- Infrastructure as Code (Terraform/Ansible)

---

# Pengumpulan 📤

- Source code diunggah ke GitHub
- Repository wajib public
- Sertakan link repository pada laporan PDF
- Deadline submission tidak menerima perpanjangan

---

# Deadline ⏳

- Start: 11 Februari 2026, 12.30
- End: 18 Februari 2026, 17.00

---

# Contact Person 📞

| Nama | Contact |
|------|----------|
| 📱 Aldura | https://wa.me/+6281333093230 |
| 📱 Hasbi | https://wa.me/+6287868287838 |

---

# Catatan Penting ⚠️

- Minimal 3 service (wajib)
- Orkestrasi wajib
- Registry wajib
- Test wajib berjalan di pipeline
- Project harus berbeda untuk setiap peserta
