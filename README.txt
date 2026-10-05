KEUANGANKU - PWA

Isi paket:
- index.html   -> aplikasi utama
- manifest.json -> identitas PWA
- sw.js         -> service worker / offline cache
- icon-192.png  -> ikon PWA
- icon-512.png  -> ikon PWA ukuran besar

PENTING:
Agar Chrome dapat menampilkan opsi Install App/Pasang aplikasi, buka aplikasi melalui HTTPS (misalnya GitHub Pages) atau localhost.
Jangan membuka index.html langsung dengan file:// karena Service Worker/PWA install tidak berjalan penuh dari file lokal.

Untuk GitHub Pages:
1. Upload semua file ke satu repository.
2. Aktifkan Settings > Pages > Deploy from branch.
3. Buka URL HTTPS GitHub Pages tersebut memakai Chrome.
4. Chrome akan menyediakan opsi Install App bila kriteria PWA terpenuhi.
