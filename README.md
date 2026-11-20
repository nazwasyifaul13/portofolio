# Portofolio Digital: Nazwa Syifaul Aulia

Situs statis (HTML, CSS, JS dalam satu file), tanpa build step. Siap unggah ke GitHub dan Vercel.

## Struktur
```text
├── index.html
├── vercel.json
└── assets/images/
    ├── profile.jpg                 # foto asli berlatar biru (dipakai untuk pratinjau tautan)
    ├── profile-cutout.png          # foto hero, latar transparan di atas lengkung pastel
    ├── cv-nazwa-syifaul-aulia.jpg  # dicetak saat tombol "Cetak CV" diklik
    ├── project-smartrt.jpg
    ├── project-web-sekolah.jpg
    ├── project-si-laundry.jpg
    └── project-batiknesia.jpg
```

## Ganti data kontak
Buka `index.html`, cari `window.PORTFOLIO_CONFIG` di bagian atas. GitHub masih dummy (`githubUrl`, `githubLabel`).

## Deploy
1. Unggah isi folder ini ke root repository GitHub.
2. Vercel > Add New > Project > pilih repo > Framework Preset **Other** > Deploy.
