# ⚡ HLN 81 Motion Logo

Motion logo 5 detik untuk **Hari Listrik Nasional ke-81** (27 Oktober 2026), bertema
**"Energi untuk Semua, Kemandirian bagi Indonesia"**.

**▶ Demo:** https://goodranger.github.io/hln81-motion-logo/

> Desain orisinal, bukan logo resmi PT PLN (Persero) atau Kementerian ESDM.

## Alur animasi

| Waktu | Adegan |
|---|---|
| 0,0 – 0,7 s | Arus listrik mengalir di kabel menuju tengah layar |
| 0,7 – 1,4 s | Arus menggambar angka **8** |
| 1,4 – 1,6 s | Angka **1** menyambar sebagai petir, disertai kilatan |
| 1,6 – 2,6 s | Gelombang energi, percikan, dan angka 8 berubah biru elektrik |
| 2,2 – 3,2 s | Judul **HARI LISTRIK NASIONAL** dan garis merah-putih |
| 3,0 – 4,0 s | Kalimat tema dan tanggal 27 Oktober 1945 · 2026 |
| 4,1 – 5,0 s | Kilau melintas, lalu berhenti di frame akhir |

## Cara pakai

- Buka `index.html` di browser. Ada tombol putar/jeda, penggeser waktu, dan opsi ulangi terus.
- **Mode capture:** `index.html?t=2.4` menampilkan satu frame diam di detik ke-2,4 dalam ukuran
  layar penuh, berguna untuk merender frame demi frame menjadi video (misalnya 30 fps × 5 s = 150 frame).

## Teknis

- Satu SVG 1920×1080 (16:9) yang digerakkan fungsi `render(t)`, jadi setiap frame deterministik.
- Tanpa library, cukup HTML, CSS, dan JavaScript murni.
- Font: Plus Jakarta Sans dan JetBrains Mono (Google Fonts).
- Menghormati `prefers-reduced-motion`.
