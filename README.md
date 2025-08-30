**CNN for MNIST Dataset with PyTorch**

Proyek ini merupakan implementasi **Convolutional Neural Network (CNN)** menggunakan **PyTorch** untuk klasifikasi dataset **MNIST**, yaitu dataset angka tulisan tangan (handwritten digits). Model dilatih untuk mengidentifikasi angka dari gambar 0 hingga 9.

**Tentang Proyek**

Tujuan utama dari proyek ini adalah membangun dan melatih model CNN yang efisien dan akurat. Prosesnya mencakup:

- Preprocessing Data: Menggunakan dataset biner IDX dan melakukan normalisasi, serta augmentasi data untuk meningkatkan performa model.

- Arsitektur Model: Membuat arsitektur CNN yang terdiri dari beberapa layer konvolusi, pooling, dan fully connected.

- Training dan Evaluasi: Melatih model dengan data training dan mengukur akurasinya menggunakan data testing.

- Visualisasi: Menampilkan contoh gambar setelah augmentasi, serta plot akurasi dan loss untuk memantau proses pelatihan.

**Persyaratan (Prerequisites)**

Pastikan kamu telah menginstal library Python berikut:

- torch

- torchvision

- numpy

- matplotlib

- tqdm

Kamu bisa menginstalnya menggunakan pip:
Bash
```
pip install torch torchvision numpy matplotlib tqdm
```

**Dataset**

Dataset yang digunakan adalah MNIST dalam format biner (.idx). Pastikan kamu memiliki file-file berikut di direktori yang sama dengan notebook ini:

- train-images.idx3-ubyte

- train-labels.idx1-ubyte

- t10k-images.idx3-ubyte

- t10k-labels.idx1-ubyte

**Cara Menjalankan**

1. **Clone repositori ini:**

Bash
```
git clone https://github.com/username/nama-repositori-kamu.git
cd nama-repositori-kamu
```

2. **Siapkan Dataset** : Tempatkan file dataset MNIST di direktori proyek.

3. **Jalankan Jupyter Notebook**:

Bash
```
jupyter notebook cnn-mnist.ipynb
```

Jalankan setiap sel kode di dalam notebook untuk melihat proses pelatihan dan hasil klasifikasi model.

**Hasil** 

Notebook ini akan menghasilkan plot yang menunjukkan akurasi dan loss model selama proses pelatihan, serta menampilkan contoh gambar dengan prediksi yang benar dan salah.
