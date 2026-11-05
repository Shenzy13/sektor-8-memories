SEKTOR 8 — AI ENGINEER MEMORIES 2026
Website cinematic aesthetic, responsif untuk HP dan laptop.

ISI:
- Halaman pembuka animasi
- Musik latar dengan tombol play/pause
- Galeri foto kenangan
- 10 kartu anggota dengan pesan kenangan
- Mentor: Aldilah Rihadatul'ais
- Timeline dan penutup

CARA MENAMBAHKAN FOTO:
1. Buka folder assets.
2. Tambahkan foto sampul dengan nama cover.jpg.
3. Foto anggota: beri nama member-01.jpg sampai member-10.jpg.
4. Foto galeri: beri nama gallery-01.jpg sampai gallery-05.jpg.
5. Buka index.html dan lihat bagian "The gallery" serta "The people".
6. Untuk galeri, ganti elemen button class="shot placeholder" menjadi:
   <button class="shot" data-caption="Caption foto"><img src="assets/gallery-01.jpg" alt="Kenangan Sektor 8"></button>
7. Untuk foto anggota, di dalam setiap .member-photo tambahkan:
   <img src="assets/member-01.jpg" alt="Nama Anggota">
   Hapus span class="initial" jika sudah memasang foto.
8. Foto portrait dan landscape otomatis dipotong rapi mengikuti frame (object-fit: cover).
   Jika ingin seluruh foto terlihat, ubah object-fit: cover menjadi contain pada CSS .member-photo img / .shot img.

MUSIK:
- Tambahkan file musik milik sendiri atau musik bebas lisensi ke assets/music.mp3.
- Tombol musik ada di kanan bawah. Musik baru berjalan setelah pengunjung menekan tombol (aturan browser).
- Jangan unggah musik berhak cipta tanpa izin.

CARA PUBLISH GRATIS DENGAN GITHUB PAGES:
1. Login di https://github.com
2. Buat repository baru bernama sektor-8-memories (Public).
3. Upload index.html dan folder assets.
4. Buka Settings > Pages.
5. Pada Build and deployment pilih Deploy from a branch.
6. Pilih branch main dan folder /(root), lalu Save.
7. Tunggu proses selesai. Link website muncul di bagian GitHub Pages.

CATATAN:
- Foto belum disertakan karena belum ada foto asli yang diunggah. Bagian galeri memakai placeholder cinematic sampai foto kalian ditambahkan.
- Pesan setiap anggota adalah pesan kenangan awal dan bisa diedit langsung di index.html.
