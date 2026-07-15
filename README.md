# Royyan-Website

yo, ini project layout web yang udah jadi. basically sebuah website portfolio atau blog modern dengan dark theme yang agak sophisticated.

## Apa Aja Fitur-Fiturnya

- **Header Fixed** yang tetap di atas pas lo scroll, ada search bar dan login button
- **Navigation Bar** di bawah header yang bisa collapse di mobile
- **Sidebar Dinamis** yang bisa dibuka tutup di mobile, berisi kategori dan social media links
- **Responsive Design** yang jalan bagus di semua ukuran layar
- **Scroll Animation** yang smooth, element muncul pas lo scroll ke bawah
- **Article Grid** yang bisa nunjukin artikel dalam layout grid yang rapi
- **Pagination** buat navigate ke page lain
- **Dark Theme** yang enak dipandang
- **Grain Overlay** effect yang subtle buat aesthetic

## Tech Stack yang Dipake

- **HTML5** - struktur dasar
- **Tailwind CSS** - styling yang super cepat
- **JavaScript Vanilla** - interaktif tanpa framework berat
- **Iconify** - icon library yang kaya pilihan

## Gimana Cara Kerja Sidebar di Mobile

Sidebar di mobile bisa dibuka dengan klik icon sidebar di header. Terus bisa ditutup dengan beberapa cara:

1. Klik tombol X yang ada di dalam sidebar
2. Klik area gelap di belakangnya
3. Klik salah satu link di sidebar

Basically UX yang user-friendly dan responsive.

## File Structure

```
.
├── index.html      # HTML utama
├── style.css       # CSS custom yang nggak tercakup Tailwind
└── README.md       # File ini
```

## Cara Pake

1. Buka `index.html` di browser
2. Itu aja, langsung bisa dipake
3. Kalo mau edit, tinggal buka file dengan text editor favorit

## Notes

- CSS file dipanggil `styles.css` di HTML, tapi file actualnya `style.css`. Kalo error, rename atau update link-nya
- Semua icon pake Iconify, jadi perlu internet untuk nampilin icon
- Layout responsif sampe mobile, tested di berbagai ukuran
- Code udah dibersihin dari semua komentar

## Feature yang Bisa Ditambah Nanti

- Filter artikel berdasarkan kategori
- Search functionality yang beneran jalan
- Dark/Light mode toggle
- Load more artikel (infinite scroll)
- Comments section
- Share button untuk artikel

basically ini udah production-ready, tinggal di-customize sesuai kebutuhan. enjoy!

