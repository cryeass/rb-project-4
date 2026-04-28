# Alumni Tracer Study - rb-project-4

Sistem Pelacakan Alumni Terpadu dengan fitur Dark Mode, Manajemen Data Alumni, dan Statistik Laporan.

## Hasil Pengujian Aplikasi (Daily Project 2 Quality Aspects)

Berikut adalah tabel hasil pengujian aplikasi berdasarkan Use Case Diagram dan aspek kualitas yang telah ditentukan:

| ID | Aspek Kualitas | Skenario Pengujian | Hasil yang Diharapkan | Status |
|:---|:---|:---|:---|:---|
| **1** | **Functionality** | Login dengan field username/password kosong | Sistem menampilkan pesan error "Username dan Password wajib diisi!" | ✅ Passed |
| **2** | **Functionality** | Login Admin menggunakan credentials 'admin' / 'admin' | Berhasil masuk ke Dashboard Admin dan menampilkan menu Laporan & Kelola Alumni | ✅ Passed |
| **3** | **Functionality** | Login Alumni menggunakan nama yang terdaftar di database | Berhasil masuk ke Dashboard Alumni dan menampilkan nama user di pojok kanan atas | ✅ Passed |
| **4** | **Functionality** | Akses menu 'Update Profil' oleh Alumni | Form profil muncul dengan data nama otomatis terisi sesuai user login | ✅ Passed |
| **5** | **Functionality** | Akses menu 'Laporan & Statistik' oleh Admin | Grafik batang dan lingkaran (Chart.js) muncul menampilkan data statistik alumni | ✅ Passed |
| **6** | **Usability** | Mengaktifkan Dark Mode menggunakan tombol toggle | Tema aplikasi berubah menjadi gelap (Dark) dan warna teks menyesuaikan secara otomatis | ✅ Passed |
| **7** | **Usability** | Refresh halaman setelah memilih tema tertentu | Tema pilihan terakhir (Light/Dark) tetap bertahan karena tersimpan di LocalStorage | ✅ Passed |
| **8** | **Security** | Login Admin dengan password yang salah | Sistem menampilkan pesan error generik tanpa membocorkan data kredensial | ✅ Passed |
| **9** | **Reliability** | Navigasi antar menu samping (Sidebar) | Konten halaman berganti secara dinamis (SPA) tanpa melakukan reload seluruh halaman | ✅ Passed |
| **10** | **Portability** | Responsivitas tampilan pada berbagai ukuran layar | Sidebar otomatis tersembunyi pada layar mobile dan layout menyesuaikan (Responsive Design) | ✅ Passed |

---

*Catatan: Pengujian dilakukan pada tanggal 29 April 2026 menggunakan browser berbasis Chromium.*
