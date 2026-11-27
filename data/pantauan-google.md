# Pantauan Google Harian

Diisi oleh tugas harian pemantauan Google (berjalan di cloud, tanpa Search Console). Maintenance pagi bisa memakai catatan ini untuk memilih topik.
Catatan: peringkat diambil dari alat WebSearch (bukan Google Indonesia langsung), jadi hanya perkiraan.

## 2026-11-26

**Kesehatan website (dicek dari repo):**
- Sitemap berisi 4 URL: beranda, artikel/beda-sondir-dan-boring-spt.html, wilayah/jakarta.html, portofolio.html. Semua halaman HTML di repo sudah masuk sitemap (kecuali file verifikasi Google, memang tidak perlu).
- Judul dan meta description: terisi dan unik di keempat halaman; canonical benar.
- Link internal: tidak ada link/gambar rusak ditemukan.
- Cek live (diulang siang hari setelah izin akses domain dijawab): keempat halaman di sitemap terbuka HTTP 200, konten lengkap, judul sesuai. Deploy GitHub Pages terakhir sukses.
- Catatan: sitemap.xml dan meta description beranda yang terbaca di live masih versi lama (sitemap 2 URL). Kemungkinan cache; deploy sudah sukses, cek ulang besok.
- Perbaikan: tidak ada yang perlu diperbaiki.

**Status indeks:**
- `site:ahligeotechgeolistrik.co.id`: belum ada hasil dari domain ini.
- Pencarian judul artikel "Beda Sondir dan Boring SPT" dan nama "GeoSurvey Nusantara": belum muncul.
- Kesimpulan: belum ada halaman yang terlihat terindeks (situs masih baru).

**Kata kunci (perkiraan):**

| Kata kunci | Website muncul? | 3 hasil teratas |
|---|---|---|
| jasa geolistrik | Tidak | pse.ugm.ac.id (jasa survei geofisika air tanah), detik.com (artikel sumur bor), e-journal.unipma.ac.id |
| jasa geolistrik jakarta | Tidak | detik.com, pse.ugm.ac.id, detik.com |
| jasa sondir jakarta | Tidak | disway.id (artikel jasa sondir Jakarta), clutch.co, olx.co.id |
| jasa boring SPT | Tidak | id.scribd.com (prosedur boring & SPT), ejournal2.undip.ac.id, repository.ubb.ac.id |
| jasa survei LiDAR | Tidak | elsa.brin.go.id (layanan drone LiDAR), linkedin, sites.google.com (lm-instruments) |
| jual alat geolistrik | Tidak | tokopedia.com, blog-distributoralatgeofisika.blogspot.com, tokopedia.com/alatgeo |

Pengamatan: hasil WebSearch didominasi jurnal/PDF kampus dan marketplace; sedikit situs jasa khusus. Peluang topik: halaman jasa geolistrik air tanah (bersaing dengan pse.ugm), panduan sondir Jakarta (disway.id punya artikel serupa).

## 2026-11-27

**Kesehatan website (dicek dari repo):**
- Sitemap berisi 5 URL: beranda, artikel/beda-sondir-dan-boring-spt.html, artikel/geolistrik-untuk-mencari-air-tanah.html (baru), wilayah/jakarta.html, portofolio.html. Semua halaman HTML di repo sudah masuk sitemap (kecuali file verifikasi Google).
- Judul dan meta description: terisi dan unik di kelima halaman.
- Link internal dan gambar: tidak ada yang rusak.
- Perbaikan: tidak ada yang perlu diperbaiki.

**Cek live (diulang setelah pemilik memilih "selalu izinkan"):** berhasil. Kelima halaman dan sitemap.xml terbuka HTTP 200, konten lengkap, judul sesuai repo.
- sitemap.xml live sudah versi baru: 5 URL dengan lastmod sama dengan repo (masalah cache kemarin sudah beres).
- Meta description beranda yang terbaca di live masih teks lama ("...cari titik air tanah... Tim lapangan berpengalaman..."), berbeda dari repo ("...georadar (GPR) dan pipe locator, LiDAR, topografi drone... Melayani seluruh Indonesia..."). Halaman lain cocok. Kemungkinan cache alat pengambil halaman; deploy sudah sukses. Cek ulang besok.
- Percobaan pertama pagi ini sempat gagal (PROVENANCE_REQUIRED); saat itu dipakai cadangan: deploy GitHub Pages #13 (commit e818a6c) sukses.

**Status indeks:**
- `site:ahligeotechgeolistrik.co.id`: belum ada hasil dari domain ini.
- Pencarian judul "Geolistrik untuk Mencari Air Tanah: Cara Kerja dan Tahapannya", "Beda Sondir dan Boring SPT: Mana yang Dibutuhkan Proyek Anda", dan nama "GeoSurvey Nusantara": belum muncul. (Nama mirip "Geo Survey Nusantara" muncul di resource.geospatialworld.net, itu entri perusahaan lain/direktori, bukan situs ini.)
- Kesimpulan: belum ada halaman yang terlihat terindeks.

**Kata kunci (perkiraan):**

| Kata kunci | Website muncul? | 3 hasil teratas |
|---|---|---|
| jasa geolistrik | Tidak | pse.ugm.ac.id (jasa survei geofisika air tanah), detik.com (sumur bor), e-journal.unipma.ac.id |
| jasa geolistrik jakarta | Tidak | detik.com, pse.ugm.ac.id, detik.com |
| jasa sondir jakarta | Tidak | disway.id (artikel jasa sondir Jakarta), clutch.co, olx.co.id |
| jasa boring SPT | Tidak | id.scribd.com (prosedur boring & SPT), ejournal2.undip.ac.id, repository.ubb.ac.id |
| jasa survei LiDAR | Tidak | id.linkedin.com, elsa.brin.go.id (drone LiDAR), au.linkedin.com (Geoconsol) |
| jual alat geolistrik | Tidak | tokopedia.com, blog-distributoralatgeofisika.blogspot.com, tokopedia.com/alatgeo |

Pengamatan: hampir sama dengan kemarin. Baru terlihat: disway.id juga punya artikel "Memahami Metode Geolistrik" (peringkat 4 untuk "jasa geolistrik"); halorobotics.com punya artikel "LiDAR vs Photogrammetry, apa bedanya" dan ukdn.geo.ugm.ac.id menawarkan survei topografi UAV + LiDAR. Peluang topik: artikel LiDAR (misalnya perbandingan LiDAR vs fotogrametri untuk proyek) karena pesaing jasa LiDAR berbahasa Indonesia masih sedikit; halaman "jual alat geolistrik" yang informatif (pesaing kebanyakan marketplace).
