# ALGEBRALAB

**Kumpul. Kembang. Seimbang!** — Ungkapan Algebra · Kembangan · Persamaan Linear

Aplikasi web pembelajaran algebra untuk murid: nota, simulasi interaktif, latihan dan kuiz. Boleh dipasang di telefon dan digunakan tanpa internet.

## Kandungan
- **Nota** – Sebutan Sejenis, Kembangan, Persamaan Linear
- **Simulasi** – Variable Explorer, Balance Equation
- **Latihan** – 5 soalan rawak setiap topik, petunjuk & penyelesaian
- **Kuiz Pantas** – 10 soalan, 1 minit setiap soalan

## Tambah simulasi baharu
1. Letak fail `.html` dalam folder `simulasi/`.
2. Dalam `index.html`, cari `Simulasi 01` dalam senarai `SIMS`, tukar `file:null` kepada `file:'simulasi/nama-fail.html'` dan buang `soon:true`.
3. Dalam `sw.js`, tambah fail itu ke senarai `FILES` dan naikkan nombor `CACHE` (contoh `algebralab-v2`).
