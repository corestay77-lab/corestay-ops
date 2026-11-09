# CoreStay Ops

**Versi 1.0.0** (build 2026-11-09)

Aplikasi web statis untuk Housekeeping dan Engineering hotel (HTML, CSS, JavaScript tanpa build). Buka `index.html` atau unggah folder ini ke hosting statis. Data tersimpan di browser (localStorage).

## Isi
- **Beranda:** kesiapan kamar, work order aktif, SLA, PM terlambat, kesiapan per hotel, aktivitas terbaru.
- **Status kamar (Housekeeping):** papan kamar dengan kode standar VD, CL, VC, VI, OD, OC, OOO. Alur: bersihkan, inspeksi, siap dijual, check-in, check-out. Petugas, Do Not Disturb, catatan, dan laporan kerusakan.
- **Work order (Engineering):** prioritas Emergency sampai Low dengan target SLA, alur Baru, Ditugaskan, Dikerjakan, Menunggu suku cadang, Selesai, Ditutup. Blokir kamar (OOO) otomatis dibuka dan kamar kembali kotor saat pekerjaan selesai.
- **Preventive maintenance:** jadwal berkala, status terlambat atau segera, tandai selesai, dan buat work order dari jadwal.
- **Pengaturan:** versi, target SLA, cadangan data, kembalikan data contoh, jejak aktivitas.

## Standar antarmuka
Landmark dan skip link, fokus keyboard terlihat, target sentuh minimal 44 px (36 px pada tombol tabel), status selalu memakai kode dan teks selain warna, notifikasi `aria-live`, mode gelap dan terang, responsif, dan menghormati `prefers-reduced-motion`.

## Belum ada
Inspeksi dengan checklist, penugasan otomatis, Lost and Found, linen dan suku cadang, register aset, meter utilitas, serta impor cadangan.

## Versi
Ubah konstanta `VER` dan `BUILD` di `index.html` setiap rilis.
