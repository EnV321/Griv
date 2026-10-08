# Grivindo — Portfolio

Portfolio monokrom dengan animasi halus, tiga proyek demo, modal detail, menu mobile, dan tombol salin email. Dibangun dengan React, Vite, TypeScript, dan Tailwind CSS. Situs ini dibangun sebagai halaman statis untuk GitHub Pages pada `https://env321.github.io/Griv/`.

## Menjalankan di komputer

Gunakan Node.js 20.19 atau lebih baru (disarankan 22.23.3).

```sh
npm install
npm run dev
```

Buka alamat lokal yang muncul di terminal. `npm run check` memeriksa TypeScript; `npm run build` membuat keluaran statis di `dist`.

## Mengubah isi

Edit `app/portfolio.config.ts` untuk nama, profesi, bio, keahlian, email, GitHub, dan proyek. Bio, keahlian, dan tiga proyek masih bertanda contoh; ganti dengan data asli sebelum membagikan portfolio sebagai karya pribadi. Mengubah file pada `main` akan memicu workflow GitHub Pages.

## Mengaktifkan GitHub Pages

Pada repository GitHub, buka **Settings → Pages → Build and deployment → Source: GitHub Actions**. Workflow `.github/workflows/deploy.yml` akan membangun dan mengunggah `dist`. Jika Pages belum diaktifkan, pilih sumber tersebut sekali lalu jalankan ulang workflow dari tab Actions.
