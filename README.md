# Kalkulus 1: Website Pembelajaran Interaktif & Simulasi UTS (Week 1–4)

Portal pembelajaran interaktif dan bank latihan soal persiapan Ujian Tengah Semester (UTS) untuk mata kuliah Kalkulus 1, Universitas Muhammadiyah Surakarta (UMS).

Dibangun dengan standar **Cursor Design System** yang clean, elegan, dan rigor akademis tinggi.

---

## 📚 Struktur Modul Pembelajaran

1. **[Week 1: Bilangan & Representasi Bilangan](week1-bilangan.html)**
   - Hierarki Himpunan ($\mathbb{N} \subset \mathbb{W} \subset \mathbb{Z} \subset \mathbb{Q} \subset \mathbb{R} \subset \mathbb{C}$)
   - Konsep Bilangan vs Angka
   - Representasi 1D Garis Bilangan, Bidang Kartesius 2D, dan Daerah Pertidaksamaan
   - Merasionalkan Penyebut Akar & Urutan Aljabar PEMDAS
   - *Simulator Interaktif:* Number Set Classifier & 2D Inequality Region Canvas
   - *Latihan Soal:* 10 Soal Medium to High + Pembahasan KaTeX

2. **[Week 2: Trigonometri & Lingkaran Satuan](week2-trigonometri.html)**
   - Rasio Segitiga Siku-Siku Pythagoras & Derajat $\leftrightarrow$ Radian
   - Lingkaran Satuan ($r=1$) dengan Koordinat $P(x,y) = (\cos\theta, \sin\theta)$
   - Kaidah Tanda 4 Kuadran ASTC (*All Students Take Calculus*)
   - 8 Keluarga Identitas Trigonometri & Persamaan Analitis
   - *Simulator Interaktif:* Real-time Unit Circle Explorer ($0^\circ - 360^\circ$)
   - *Latihan Soal:* 10 Soal Medium to High + Pembahasan KaTeX

3. **[Week 3: Fungsi Bilangan & Pemetaan Khusus](week3-fungsi.html)**
   - Domain, Kodomain, dan Range Pemetaan
   - Sifat Injektif (*one-to-one*), Surjektif (*onto*), dan Bijektif
   - Aljabar Komposisi & Rumus Invers Fungsi Pecahan
   - Fungsi Tangga Floor ($\lfloor x \rfloor$) & Ceiling ($\lceil x \rceil$)
   - Algoritma Pembagian Euclid Dividen Negatif ($-25 \bmod 7 = 3, -38 \bmod 7 = 4$)
   - *Simulator Interaktif:* Euclidean Negative Modulo Lab & Step Function Canvas
   - *Latihan Soal:* 10 Soal Medium to High + Pembahasan KaTeX

4. **[Week 4: Limit & Kontinuitas](week4-limit.html)**
   - Konsep Pendekatan Nilai Limit vs Nilai Fungsi (Titik Lubang / *Removable Discontinuity*)
   - Limit Sepihak & Teorema Eksistensi
   - Resolusi Bentuk Tak Tentu $\frac{0}{0}$ & Perkalian Sekawan
   - Limit Khusus Trigonometri $\lim_{x\to 0} \frac{\sin x}{x} = 1$
   - 3 Syarat Cauchy Kontinuitas Fungsi di Suatu Titik
   - *Simulator Interaktif:* Secant-to-Limit Simulator & Piecewise Parameter Tuner
   - *Latihan Soal:* 10 Soal Medium to High + Pembahasan KaTeX

5. **[Hub Utama & Simulasi UTS (Index)](index.html)**
   - Bank Latihan Soal Terpadu (20 Soal Pilihan Ganda Medium to High, 5 per modul)
   - Simulasi Timer Ujian UTS 90 Menit Digital
   - Prediksi Indeks Nilai Akademik UTS (A, B, C, D/E)
   - Analisis Persentase Ketuntasan per Materi Pokok
   - Lembar Rangkuman Rumus Cepat UTS (*Cheatsheet Accordion*)
   - Fitur Cetak / Simpan PDF Lembar Latihan Fisik

---

## 🛠️ Teknologi & Desain

- **Desain:** Cursor Light Design System (`#f7f7f4` parchment, `#26251e` espresso text, `#f54e00` electric orange, pill CTAs, macOS window cards)
- **Matematika:** KaTeX CDN (`renderMathInElement`) untuk typeset formula LaTeX presisi
- **Grafik:** HTML5 Canvas API untuk visualisasi interaktif bidang Kartesius, unit circle, step function, dan kurva limit
- **Responsif:** Mobile & desktop friendly tanpa dependensi backend (Static HTML/CSS/JS)

---

## 🚀 Akses Online
Website ini dapat diakses secara daring melalui GitHub Pages:
[https://faridmarufprabowo2021.github.io/kalkulus-interaktif-ums/](https://faridmarufprabowo2021.github.io/kalkulus-interaktif-ums/)
