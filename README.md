# 🖼️ SIFT Panorama Stitching

Proyek ini merupakan implementasi **Image Stitching (Panorama Generation)** menggunakan algoritma **Scale-Invariant Feature Transform (SIFT)** untuk mendeteksi serta mencocokkan fitur antar gambar, kemudian menggabungkannya menjadi satu gambar panorama utuh.

Proyek dikembangkan menggunakan **Python** dalam bentuk **Jupyter Notebook** sebagai bagian dari pembelajaran Computer Vision dan pengolahan citra digital.

---

## 📌 Deskripsi Singkat

Image stitching adalah teknik dalam Computer Vision yang digunakan untuk menggabungkan beberapa gambar yang memiliki area overlap menjadi satu gambar panorama.

Pada proyek ini, proses stitching dilakukan melalui tahapan berikut:

### 1️⃣ Deteksi Keypoints dan Deskriptor
Menggunakan algoritma SIFT untuk mendeteksi fitur unik yang tahan terhadap perubahan skala dan rotasi.

### 2️⃣ Feature Matching
Mencocokkan fitur antar gambar menggunakan metode pencocokan seperti Brute Force Matcher atau FLANN.

### 3️⃣ Homography Estimation (RANSAC)
Menghitung matriks homografi untuk transformasi perspektif sekaligus menghilangkan outlier menggunakan algoritma RANSAC.

### 4️⃣ Warping dan Stitching
Melakukan transformasi perspektif dan menggabungkan gambar menjadi panorama.

### 5️⃣ Visualisasi Hasil
Menampilkan hasil akhir panorama.

---

## 🛠️ Teknologi yang Digunakan

- Python 3.x  
- OpenCV  
- NumPy  
- Matplotlib  
- Jupyter Notebook  

---

## 📂 Struktur Repository

## 📂 Struktur Repository

```text
SIFT-panorama/
│
├── sift-panorama.ipynb      # Notebook utama berisi seluruh implementasi
│
├── images/                  # Folder berisi gambar input
│   ├── img1.jpg
│   ├── img2.jpg
│   └── ...
│
├── result/                  # Folder berisi hasil panorama
│   ├── panorama.jpg
│   └── ...
│
└── README.md                # Dokumentasi proyek
```
---

## ▶️ Cara Menjalankan

### 1. Clone repository
```bash
git clone https://github.com/NEROCAESAR76/SIFT-panorama.git


