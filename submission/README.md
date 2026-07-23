# Klasifikasi Gambar: Shoe vs Sandal vs Boot

## Deskripsi
Proyek klasifikasi gambar untuk membedakan tiga kelas alas kaki: Boot, Sandal, dan Shoe, menggunakan Convolutional Neural Network (CNN).

## Dataset
- Sumber: Kaggle (Shoe vs Sandal vs Boot Image Dataset)
- Jumlah: 15.000 gambar, 5.000 per kelas
- Resolusi: 136x102 piksel
- Pembagian: 80% train (12.000), 10% validation (1.500), 10% test (1.500)

## Arsitektur
Sequential CNN dengan 4 blok konvolusi (Conv2D + BatchNormalization + MaxPooling2D), diikuti Flatten, Dense, dan Dropout. Output layer softmax 3 kelas.

## Hasil
- Akurasi training: 96,18%
- Akurasi testing: 95,67%

## Format Model
Model disimpan dalam tiga format: SavedModel, TF-Lite, dan TFJS.

## Cara Menjalankan
1. Install dependencies: (pip install -r requirements.txt)
2. Jalankan notebook.ipynb dari atas ke bawah.