# SIFT-panorama

# 🖼️ SIFT Panorama Stitcher

[![Python Version](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-SIFT-green.svg)](https://opencv.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Repositori ini mengimplementasikan algoritma **Scale-Invariant Feature Transform (SIFT)** untuk menggabungkan dua gambar atau lebih menjadi satu gambar panorama yang mulus (*image stitching*). 

Proses ini menggunakan deteksi *keypoint*, pencocokan fitur, dan perhitungan matriks homografi untuk menyelaraskan gambar secara presisi.

---

## 🚀 Fitur Utama

* **Deteksi Keypoint Tahan Skala:** Menggunakan SIFT untuk menemukan titik-titik fitur yang konsisten meskipun gambar mengalami perubahan skala atau rotasi.
* **Pencocokan Fitur (Feature Matching):** Menggunakan algoritma pencocokan (*matcher*) untuk mencari pasangan *keypoint* terbaik antar gambar.
* **RANSAC Homography:** Mengeliminasi kecocokan yang salah (*outliers*) dan menghitung matriks transformasi perspektif dengan akurasi tinggi.
* **Image Blending:** Menggabungkan gambar yang sudah diselaraskan menjadi satu kesatuan panorama.

---

## 🛠️ Prasyarat (Requirements)

Pastikan Anda telah menginstal pustaka berikut sebelum menjalankan kode:

```bash
pip install opencv-contrib-python numpy matplotlib
