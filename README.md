
---

## 🧭 Flowchart Sistem  

Berikut gambaran alur sistem mulai dari login hingga cetak nilai:  

![Flowchart Aplikasi Nilai Siswa](flowchart/Flowchart.png)  

---

## 🧭 Use Case Diagram  

Menunjukkan interaksi antara **aktor (Guru/Admin)** dengan sistem:  

![Use Case Aplikasi Nilai Siswa](flowchart/usecase.drawio.png)  

---

## 🧭 Activity Diagram  

Proses aktivitas dari login, input data, hingga cetak laporan:  

![Activity Aplikasi Nilai Siswa](flowchart/Activity.png)  

---

## 🧭 Database Diagram  

Struktur database aplikasi:  

![DB Diagram Aplikasi Nilai Siswa](flowchart/dbdiagram.svg)  

**Tabel Utama:**  
- `users` → menyimpan data admin/guru  
- `siswa` → data siswa  
- `mapel` → daftar mata pelajaran  
- `nilai` → nilai per siswa per mapel  
- `laporan` → rekap hasil belajar  

---

## 🛠️ Teknologi yang Digunakan  

- **Frontend:** HTML5, CSS3, JavaScript (Bootstrap / Tailwind)  
- **Backend:** PHP Native  
- **Database:** MySQL  
- **Tools Tambahan:** Draw.io (diagram), phpMyAdmin (DB Management), FPDF/Dompdf (export PDF)  

---

## 🌟 Keunggulan Aplikasi  

✅ Mudah digunakan (User-Friendly)  
✅ Cepat & responsif (Optimized Performance)  
✅ Aman dengan sistem login  
✅ Laporan siap cetak (PDF)  
✅ Dapat dikembangkan sesuai kebutuhan sekolah  

---

## 📸 Preview Tampilan  

### 🔑 Login Page  
Halaman login dengan role **Guru/Admin**.  

### 📊 Dashboard  
Menampilkan ringkasan jumlah siswa, nilai, dan laporan.  

### 📝 Input Nilai  
Form untuk menambahkan nilai per mata pelajaran.  

### 🖨️ Cetak Raport  
Export nilai siswa menjadi laporan siap cetak.  

---

## 📌 Rencana Pengembangan  

- [ ] Tambah fitur **import nilai dari Excel**  
- [ ] Tambah fitur **grafik nilai siswa**  
- [ ] Tambah **notifikasi otomatis** untuk siswa  
- [ ] Buat versi **mobile-friendly (responsive design)**  

---

## 🤝 Kontribusi  

Jika ingin berkontribusi dalam pengembangan aplikasi:  

1. Fork repository ini  
2. Buat branch baru (`feature-nama-fitur`)  
3. Commit perubahan (`git commit -m "Tambah fitur baru"`)  
4. Push branch (`git push origin feature-nama-fitur`)  
5. Buat Pull Request  

---

## 📄 Lisensi  

Proyek ini dibuat untuk tujuan pembelajaran dan pengembangan sistem informasi sekolah.  
Lisensi: **MIT License**  
