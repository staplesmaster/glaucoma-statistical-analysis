# Tugas-Besar-IF2120-2025-2026---AyamAsapRempah

# Glaucoma EDA and Statistical Testing

Repository ini berisi analisis statistik terhadap dataset pasien glaukoma menggunakan Python. Analisis dilakukan untuk memahami karakteristik data, distribusi variabel, keberadaan outlier, serta menguji beberapa hipotesis statistik terkait tekanan intraokular, cup-to-disc ratio, riwayat keluarga, dan diagnosis glaukoma.

## Deskripsi Project

Project ini menggunakan dataset `glaucoma.csv` yang berisi 10.000 data pasien dengan 17 kolom, mencakup informasi demografis, parameter klinis mata, riwayat medis, hasil pemeriksaan, dan diagnosis glaukoma.

Analisis utama yang dilakukan meliputi:

1. Statistik deskriptif untuk data numerik dan kategorikal
2. Implementasi statistik menggunakan fungsi manual
3. Implementasi statistik menggunakan library Python
4. Perbandingan hasil fungsi manual dan library
5. Deteksi dan penanganan outlier
6. Visualisasi distribusi data
7. Identifikasi bentuk distribusi variabel numerik
8. Uji hipotesis satu sampel
9. Uji hipotesis dua sampel

## Dataset

Dataset yang digunakan memiliki beberapa kolom penting, antara lain:

- `Patient ID`
- `Age`
- `Gender`
- `Visual Acuity Measurements`
- `Intraocular Pressure (IOP)`
- `Cup-to-Disc Ratio (CDR)`
- `Family History`
- `Medical History`
- `Medication Usage`
- `Visual Field Test Results`
- `Optical Coherence Tomography (OCT) Results`
- `Pachymetry`
- `Cataract Status`
- `Angle Closure Status`
- `Visual Symptoms`
- `Diagnosis`
- `Glaucoma Type`

Dataset diambil menggunakan `gdown` dari Google Drive, kemudian dibaca menggunakan `pandas`.

## Teknologi yang Digunakan

Project ini menggunakan beberapa library Python berikut:

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import math
import gdown
