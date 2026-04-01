# 🚀 Dasar Pengolahan & Augmentasi Citra Digital
[![Python Version](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green.svg)](https://opencv.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> Repositori ini berisi implementasi komprehensif dari teknik dasar pengolahan citra digital (Image Processing) dan otomatisasi augmentasi data menggunakan Python. Proyek ini dikembangkan sebagai bagian dari praktikum Sistem Multimedia.

---

## ✨ Fitur Utama
Proyek ini mencakup beberapa teknik fundamental dalam visi komputer (*Computer Vision*), di antaranya:
- **🎛️ Manipulasi Ruang Warna:** Konversi citra dari format BGR (bawaan OpenCV) ke RGB dan *Grayscale*.
- **📐 Transformasi Geometris:** Implementasi *Cropping*, *Resizing*, *Flipping* (Horizontal/Vertikal), dan Rotasi matriks dinamis.
- **📊 Analisis Visual:** Ekstraksi dan visualisasi distribusi intensitas piksel melalui Histogram Warna dan *Grayscale*.
- **🤖 Pemrosesan Batch Otomatis:** Skrip perulangan (*looping*) untuk menerapkan augmentasi pada banyak citra secara bersamaan dan menyimpannya secara massal ke dalam format terstandarisasi (`.jpg`).

---

## 🛠️ Teknologi yang Digunakan
* **Python 3.x** - Bahasa pemrograman utama.
* **OpenCV (`cv2`)** - Pustaka *open-source* standar industri untuk visi komputer.
* **Matplotlib** - Digunakan untuk memvisualisasikan matriks citra dan me-render grafik histogram.
* **NumPy** - Operasi komputasi matriks numerik di balik layar.
