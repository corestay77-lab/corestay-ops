# CoreStay Ops — Housekeeping & Engineering

Aplikasi operasional hotel: papan kamar (Housekeeping), work order, preventive maintenance, inventori, dan energi (Engineering).

Aplikasi berupa satu file statis (`index.html`) tanpa build step dan tanpa backend. Data tersimpan di browser (localStorage).

## Menjalankan lokal
Buka `index.html` di browser.

## Deploy ke GitHub Pages
1. Buat repository baru di GitHub (mis. `corestay-ops`).
2. Upload semua file di folder ini (`index.html`, `README.md`, `.nojekyll`).
3. Buka **Settings → Pages**.
4. Pada *Build and deployment*, pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu **Save**.
5. Tunggu 1–2 menit; aplikasi tersedia di `https://USERNAME.github.io/corestay-ops/`.

## Catatan
- Font Inter & Playfair Display dimuat dari Google Fonts (perlu internet; ada fallback bawaan).
- Data hanya tersimpan di browser masing-masing pengguna.
