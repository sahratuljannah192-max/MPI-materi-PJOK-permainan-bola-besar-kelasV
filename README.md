# MPI PJOK Kelas V — Petualangan Seru Mengenal Sepak Bola

Paket ini adalah website statis (HTML, CSS, JavaScript) untuk media pembelajaran interaktif PJOK kelas V SD Negeri 8 Kodeoha.

## Isi paket
- `index.html` — halaman utama dan seluruh layar MPI
- `style.css` — desain responsif dan visual
- `app.js` — navigasi, simulasi mencocokkan, kuis otomatis, dan penyimpanan nilai lokal
- `assets/ball.svg` — ikon tab browser

## Cara uji di komputer
1. Ekstrak ZIP.
2. Buka folder `MPI_Sepak_Bola_Online`.
3. Klik dua kali `index.html` atau buka dengan Chrome/Edge.
4. Uji semua menu, simulasi, kuis, dan hasil.

## Cara publikasi online gratis

### Pilihan A — Netlify Drop (paling mudah)
1. Buka https://app.netlify.com/drop
2. Login atau buat akun Netlify.
3. Ekstrak ZIP ini terlebih dahulu.
4. Seret folder `MPI_Sepak_Bola_Online` (atau seluruh isi folder tersebut) ke area upload Netlify Drop.
5. Tunggu proses selesai. Netlify akan memberikan alamat website berakhiran `netlify.app`.
6. Buka alamat tersebut untuk memastikan MPI tampil dan semua tombol berfungsi.
7. Untuk alamat yang lebih mudah diingat, ubah nama situs melalui pengaturan Site configuration / Site details jika tersedia.

### Pilihan B — GitHub Pages
1. Login ke https://github.com atau buat akun.
2. Buat repository baru, misalnya `mpi-pjok-sepakbola`.
3. Unggah `index.html`, `style.css`, `app.js`, dan folder `assets` ke bagian utama (root) repository.
4. Buka Settings → Pages.
5. Pada Build and deployment, pilih Deploy from a branch.
6. Pilih branch `main` dan folder `/ (root)`, lalu Save.
7. Tunggu publikasi. Alamat biasanya berbentuk `https://NAMA-AKUN.github.io/mpi-pjok-sepakbola/`.

## Catatan penting
- Website dapat dibuka online melalui tautan publik setelah berhasil dipublikasikan.
- File inti tidak memakai framework atau server/database; hosting statis sudah cukup.
- Google Fonts dipakai untuk tampilan jika internet tersedia. Jika tidak, font pengganti sistem akan digunakan.
- Nilai kuis disimpan di `localStorage` browser/perangkat yang digunakan. Nilai tidak otomatis terkirim ke guru dan tidak tersinkron ke perangkat lain.
- Tombol suara pada versi ini adalah kontrol visual; belum ada narasi audio.
- Ilustrasi karakter menggunakan emoji agar paket ringan dan tidak bergantung pada gambar berlisensi.
- Sesuaikan identitas sekolah, nama guru, logo, atau konten sebelum dipublikasikan bila diperlukan.

## Pemeriksaan sebelum dibagikan
- [ ] Buka di ponsel dan laptop.
- [ ] Coba seluruh tombol navigasi.
- [ ] Cocokkan keempat pasangan simulasi.
- [ ] Coba jawaban benar dan salah pada tantangan berpikir kritis.
- [ ] Selesaikan kuis dan periksa nilai.
- [ ] Salin tautan publik dan kirim kepada siswa/orang tua.
