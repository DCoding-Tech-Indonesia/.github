# 🏢 Selamat Datang di Tim Dcoding! | Team Workspace & Guidelines

Dokumen ini berfungsi sebagai panduan utama, aturan internal, dan pembagian peran (*roles*) untuk seluruh anggota tim di **Dcoding**. Harap pahami dan ikuti ketentuan di bawah ini untuk menciptakan lingkungan kerja yang profesional, produktif, dan kolaboratif.

---

## 📜 Ketentuan Umum & Etos Kerja (Code of Conduct)

Di Dcoding, kami menghargai efisiensi, komunikasi yang transparan, dan rasa saling menghormati. Seluruh anggota tim wajib mematuhi standar kerja berikut:

### 1. 🕒 Profesionalisme & Ketepatan Waktu
* **Stand-up Meeting:** Hadir tepat waktu dalam rapat harian atau mingguan yang telah dijadwalkan.
* **Manajemen Tugas:** Selalu perbarui status pekerjaan Anda di *Project Management Tool* (seperti Jira, Trello, atau GitHub Projects) secara berkala.
* **Komunikasi:** Tanggap dalam merespons pesan internal (Slack/Teams) selama jam kerja operasional.

### 2. 🔐 Keamanan Data & Kerahasiaan (NDA)
* **Kredensial:** Dilarang keras menuliskan atau melakukan *hardcode* kredensial, token API, atau password ke dalam repositori publik maupun private tanpa enkripsi (gunakan Secrets/Environment Variables).
* **Data Perusahaan:** Segala bentuk kode sumber, data klien, dan strategi internal Dcoding bersifat rahasia dan dilindungi oleh *Non-Disclosure Agreement* (NDA).

### 3. 🛠️ Standar Kode & Kolaborasi
* **Kualitas Kode:** Setiap kode yang ditulis harus mengikuti standar *style guide* yang telah disepakati tim dan lolos tahap *linting*.
* **Dokumentasi:** Setiap fitur baru atau perubahan arsitektur wajib disertai dengan dokumentasi atau pembaruan pada file README terkait.

---

## 🎭 Struktur Peran Kerja (Team Roles & Responsibilities)

Untuk memastikan alur kerja berjalan dengan terstruktur, berikut adalah pembagian peran di dalam proyek Dcoding:

| Peran (Role) | Ikon | Tanggung Jawab Utama | Hak Akses / Otoritas |
| :--- | :---: | :--- | :--- |
| **Project Manager / Tech Lead** | 💼 | Mengatur *timeline* proyek, membagi tugas, memimpin arsitektur teknis, dan mengambil keputusan akhir. | Akses penuh (Owner) pada organisasi GitHub, manajemen infrastruktur cloud, dan persetujuan arsitektur utama. |
| **Senior Developer / Maintainer** | 🛡️ | Melakukan peninjauan kode (*Code Review*), membimbing junior, dan memastikan kualitas integrasi kode tetap terjaga. | Hak untuk melakukan *merge* ke branch utama (`main`/`production`), serta mengelola *issues* dan *pull requests*. |
| **Developer (Full-Stack/FE/BE)** | 🚀 | Mengembangkan fitur baru, memperbaiki *bug*, dan menulis unit pengujian (*unit testing*) sesuai tugas yang diberikan. | Akses untuk membuat *branch* baru, mengajukan *Pull Request*, dan melakukan peninjauan sejawat (*peer review*). |
| **QA Engineer / Tester** | 🔍 | Melakukan pengujian fitur (manual maupun otomatis) dan memastikan aplikasi berjalan tanpa kendala sebelum dirilis. | Hak untuk membuka *issue bug* baru, memberikan status *Approve/Reject* pada pengujian fitur, dan mengelola pelaporan *bug*. |

---

## 📈 Alur Kerja & Kontribusi (Git Workflow)

Setiap anggota tim Dcoding wajib mengikuti alur *Feature Branch Workflow* berikut untuk menghindari konflik pada kode:

```text
 🔄 Pull Latest Main ──> 🌿 Create Branch (feat/fix/chore) ──> 💻 Coding & Test ──> 🚀 Push & Open PR ──> 🔍 Code Review ──> 🔀 Merge
