# Landing Page Analytics Platform

Ini adalah landing page sederhana menggunakan Tailwind CSS untuk platform analytics. Berikut penjelasan komponen dan kelas Tailwind yang digunakan:

## Struktur Halaman

### Hero Section

- `min-h-screen`: Mengatur tinggi minimal seukuran layar
- `bg-gradient-to-r from-blue-600 to-indigo-700`: Membuat gradient dari kiri ke kanan
- `opacity-90`: Mengatur transparansi background
- `mix-blend-overlay`: Efek blend mode untuk background image

### Social Proof

- `bg-gray-50`: Background abu-abu muda
- `grid md:grid-cols-3`: Grid 3 kolom pada layar medium ke atas
- `rounded-lg shadow-md`: Membuat card dengan sudut bulat dan bayangan
- `object-cover`: Memastikan gambar menutupi area dengan proporsi yang tepat

### Features Section

- `py-24`: Padding atas dan bawah 6rem
- `grid md:grid-cols-3 gap-8`: Grid 3 kolom dengan gap 2rem
- `bg-gray-50 rounded-xl`: Background abu-abu dengan sudut lebih bulat
- `transition-all`: Animasi smooth untuk hover effects

### CTA Section

- `bg-blue-600`: Background biru
- `max-w-md`: Maksimum lebar form
- `flex flex-col sm:flex-row`: Tata letak fleksibel, kolom di mobile dan baris di desktop

### Footer

- `bg-gray-900`: Background gelap
- `grid md:grid-cols-4`: Grid 4 kolom
- `space-y-2`: Spacing vertikal antar item
- `hover:text-white transition-colors`: Efek hover pada link

## Responsive Design

- Prefix `sm:`: Breakpoint untuk layar ≥640px
- Prefix `md:`: Breakpoint untuk layar ≥768px
- Prefix `lg:`: Breakpoint untuk layar ≥1024px

## Komponen Interaktif

- Button primary: `bg-yellow-400 hover:bg-yellow-500`
- Button secondary: `border-2 border-white hover:bg-white`
- Input form: `focus:outline-none focus:ring-2`

## Typography

- Heading utama: `text-4xl md:text-6xl font-bold`
- Subheading: `text-xl text-gray-600`
- Body text: `text-gray-600`
- Link: `hover:text-white transition-colors`

## Warna

- Primary: Blue (`blue-600`)
- Secondary: Yellow (`yellow-400`)
- Text: Gray (`gray-600`, `gray-900`)
- Background: White, Gray-50, Gray-900

## Instalasi

1. Tambahkan Tailwind CSS melalui CDN:

```html
<script src="https://cdn.tailwindcss.com"></script>
```

2. Copy file index.html ke project Anda
3. Sesuaikan konten sesuai kebutuhan

## Best Practices

- Gunakan semantic HTML (`<header>`, `<main>`, `<footer>`)
- Manfaatkan sistem grid Tailwind untuk layout responsif
- Terapkan prinsip mobile-first design
- Optimasi gambar untuk performa yang lebih baik
