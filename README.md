# Spinning

PWA acak kartu nama (raffle) dengan Firebase.

- Halaman awal di `/` (aturan, tombol "Masukkan nama peserta", link kecil "Admin"); form daftar di `/#daftar`, admin di `/#admin`
- Teks halaman awal, aturan, link form kuesioner, dan keterangan angkatan diatur di Admin → Atur → Halaman awal
- Isi config Firebase di `index.html` (`const FB = {...}`)
- Pasang `firestore.rules` di Firebase Console
- Deploy otomatis ke GitHub Pages lewat `.github/workflows/pages.yml`
