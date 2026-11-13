# heart

Halaman hati dari tulisan **i love u dea**, tampil di https://heart.kadaferhidup.my.id

- `index.html` : versi statis (tanpa build), ini yang dipublikasikan.
- `CNAME` : domain kustom GitHub Pages.
- `react/` : versi React/Vite asli (opsional, `npm install && npm run dev` di dalam folder itu).
- `.github/workflows/deploy.yml` : mempublikasikan `index.html` dan `CNAME` ke GitHub Pages setiap push ke `main`.
