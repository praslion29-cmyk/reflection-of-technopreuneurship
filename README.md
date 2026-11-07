# Refleksi Mata Kuliah Technopreneurship

Website refleksi mata kuliah **Technopreneurship** dengan sudut pandang dunia penerbangan, khususnya aircraft maintenance dan industri aerospace.

## Fitur
- Hero dengan latar foto aktivitas aircraft maintenance di hangar.
- Visual berbeda pada setiap tab refleksi, termasuk foto Elon Musk pada tab **Character**; foto ditampilkan utuh tanpa pemotongan.
- Navigasi tab dengan indikator progres berbentuk rute penerbangan.
- Mode terang/gelap, mode baca otomatis, pencarian naskah, pengaturan ukuran huruf, dan fitur salin naskah.
- Tampilan responsif untuk desktop dan perangkat mobile.
- Musik latar bawaan dari file HTML sumber.

## Daftar tab
1. Technopreneurship
2. Character
3. Leadership
4. Komunikasi & Motivasi
5. Literasi Keuangan
6. Model Bisnis
7. Pola Pikir Eksponensial
8. Benang Merah
9. Naskah Lengkap

## Menjalankan secara lokal
Tidak memerlukan proses build atau instalasi package.

1. Download atau clone repository.
2. Buka `index.html` menggunakan browser.

## Deploy ke GitHub Pages
1. Buat repository baru di GitHub.
2. Upload `index.html` dan `README.md` ke root repository.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/ (root)`, lalu klik **Save**.
6. Setelah deployment selesai, buka URL GitHub Pages yang ditampilkan GitHub.

## Sumber dan atribusi gambar
Gambar ditampilkan melalui URL eksternal (hotlink), sehingga koneksi internet diperlukan. Hak penggunaan dan ketentuan atribusi mengikuti pemilik masing-masing gambar.

| Penggunaan | Sumber |
|---|---|
| Hero / aerospace team | [GAL Aerospace](https://galaerospace.com/) |
| Aircraft engine inspection | [Northern Professional Transitions](https://northernprofessionaltransitions.com/assets/aircraft-maintenance-engineers-guide-IfP3hVaU.jpg) |
| Aerospace engineering team | [GAL Aerospace](https://galaerospace.com/images/aerostaff-team.webp) |
| Aircraft design collaboration | [Research.com](https://s.research.com/uploads/98be608623c8e26826360efb56d104f6_0fbe04d5d2.webp) |
| Aviation maintenance planning | [Airtech Consulting](https://airtechconsulting.com/2026/08/05/forecasting-aircraft-maintenance-costs-a-practical-b2b-guide/) |
| Rocket launch | [Space.com](https://www.space.com/space-exploration/launches-spacecraft/spacex-aiming-for-record-breaking-170-orbital-launches-in-2025) |
| Aircraft taxiway at sunset | [Aerospace Manufacturing and Design](https://www.aerospacemanufacturinganddesign.com/news/number-1-most-read-article-2025-2025-forecast/) |
| Aircraft maintenance hangar | [Aviation Week](https://aviationweek.com/mro/mros-pursue-flexibility-through-bespoke-maintenance-offerings) |

**Catatan:** Jika penyedia mengubah alamat gambar atau membatasi hotlink, gambar terkait mungkin tidak tampil. Untuk pemakaian jangka panjang, unduh gambar sesuai izin/lisensi masing-masing sumber, simpan di folder `assets/`, lalu ubah URL gambar pada array `TAB_VISUALS` dan CSS `.hero` menjadi path lokal. Foto Elon Musk sudah disimpan lokal agar tampil konsisten dan tidak terpotong.

## Teknologi
- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts

## Kredit konten
Materi refleksi dan naskah disusun berdasarkan dokumen tugas mata kuliah Technopreneurship yang diberikan oleh pemilik repository. Website ini dikembangkan sebagai media presentasi refleksi digital.


**Foto Elon Musk:** sudah disematkan langsung di dalam `index.html` (data URI), sehingga tidak memerlukan file gambar terpisah dan tidak akan gagal karena path aset di GitHub Pages.
