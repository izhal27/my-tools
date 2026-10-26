<div align="center">

# 🧰 Toolbox Izhal

**Portal kecil berisi kumpulan tools praktis untuk kerjaan sehari-hari.**
Tema hand drawn / retro · satu file · tanpa build · siap di-hosting di GitHub Pages.

![HTML5](https://img.shields.io/badge/HTML5-780000?style=for-the-badge&logo=html5&logoColor=fdf0d5)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-003049?style=for-the-badge&logo=tailwindcss&logoColor=fdf0d5)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-c1121f?style=for-the-badge&logo=github&logoColor=fdf0d5)
![No Build](https://img.shields.io/badge/No_Build-669bbc?style=for-the-badge&logoColor=003049)

[🌐 Lihat Demo](https://izhal27.github.io/my-tools/) · [➕ Tambah Tool](#-menambah-tool-baru) · [🚀 Deploy](#-deploy-ke-github-pages)

</div>

---

## ✨ Fitur

- 🎨 **Tema hand drawn / retro**: border bergelombang, bayangan solid, kartu sedikit miring, dan latar kertas bertitik.
- 🃏 **Kartu dengan ikon**: setiap tool tampil sebagai kartu yang bisa diklik.
- ➕ **Mudah ditambah**: cukup tambahkan satu objek ke array `TOOLS`, tanpa menyentuh HTML.
- 📱 **Responsif**: 1 kolom di HP, 2 di tablet, 3 di desktop.
- ♿ **Ramah aksesibilitas**: bisa dinavigasi dengan keyboard, dan animasi mati otomatis bila pengguna memilih *reduced motion*.
- ⚡ **Ringan**: satu file `index.html`, tidak perlu Node, npm, atau proses build.

## 🛠️ Tools di Portal Ini

| Ikon | Tool | Deskripsi | Link |
| :-: | --- | --- | --- |
| 📐 | **Rasio Cetak** | Hitung rasio & ukuran cetak | [Buka](https://izhal27.github.io/rasio-cetak/) |
| 🧾 | **Form Order** | Form pemesanan pelanggan | [Buka](https://form-order-inky.vercel.app) |
| ✂️ | **Roll Cut** | Atur pemotongan roll bahan | [Buka](https://izhal27.github.io/roll-cut/) |

## ➕ Menambah Tool Baru

Buka `index.html`, cari array `TOOLS` di bagian `<script>`, lalu tambahkan objek baru:

```js
{
  icon: "🚀",                      // emoji apa saja
  title: "Nama Tool",
  desc: "Deskripsi singkat tool.",
  url: "https://contoh.com",
  tag: "Baru",                     // opsional, label kecil di pojok kartu
  color: "maroon",                 // opsional: red | sky | maroon | navy
}
```

Simpan, commit, push. Kartu baru langsung muncul. Kalau `color` tidak diisi, warna kartu bergantian otomatis.

Judul, tagline, dan footer bisa diubah lewat objek `SITE` di bagian yang sama.

## 🎨 Palet Warna

| Warna | Hex | Dipakai untuk |
| --- | --- | --- |
| ![#780000](https://img.shields.io/badge/-%20%20%20-780000) Maroon | `#780000` | Judul, aksen gelap |
| ![#c1121f](https://img.shields.io/badge/-%20%20%20-c1121f) Merah | `#c1121f` | Aksen utama, tombol "Buka" |
| ![#fdf0d5](https://img.shields.io/badge/-%20%20%20-fdf0d5) Krem | `#fdf0d5` | Latar & kartu |
| ![#003049](https://img.shields.io/badge/-%20%20%20-003049) Navy | `#003049` | Teks, border, bayangan |
| ![#669bbc](https://img.shields.io/badge/-%20%20%20-669bbc) Biru | `#669bbc` | Aksen sekunder, titik latar |

Ingin ganti warna? Ubah di `tailwind.config` dan objek `COLORS` pada `index.html`.

## 🚀 Deploy ke GitHub Pages

1. Buat repo baru, misalnya `tools` atau `username.github.io`.
2. Upload `index.html` (dan `README.md`) ke root repo.
3. Buka **Settings → Pages**.
4. Pada *Build and deployment*, pilih **Deploy from a branch**, lalu branch `main` dan folder `/ (root)`.
5. Tunggu sebentar. Situs aktif di `https://<username>.github.io/<nama-repo>/`.

## 🧪 Jalankan Secara Lokal

Tidak perlu instalasi apa pun. Cukup buka `index.html` di browser, atau pakai server statis:

```bash
# Python
python3 -m http.server 8000

# atau Node
npx serve .
```

Lalu buka `http://localhost:8000`.

## 📁 Struktur Proyek

```
.
├── index.html   # seluruh halaman (HTML + CSS + JS)
├── LICENSE
└── README.md
```

## 🧱 Teknologi

- **HTML5**, **CSS3**, dan sedikit **JavaScript** vanilla
- [**Tailwind CSS**](https://tailwindcss.com/) via CDN
- Font [Caveat Brush](https://fonts.google.com/specimen/Caveat+Brush) & [Patrick Hand](https://fonts.google.com/specimen/Patrick+Hand) dari Google Fonts

## 📝 Lisensi

MIT License

---

<div align="center">

Coded with ☕ & 🩷 by [**IzHaL**](https://github.com/izhal27)

⭐ Kalau portal ini berguna, jangan lupa kasih bintang!

</div>
