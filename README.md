## 🌿 UTS Pengolahan dan Analisis Citra Digital  
**Klasifikasi Daun Herbal Menggunakan CNN dan MobileNetV2 (Transfer Learning)**  

📍 **Repository:** [https://github.com/ebit-7/UTS-Pengolahan-dan-Analisis-Citra-Digital](https://github.com/ebit-7/UTS-Pengolahan-dan-Analisis-Citra-Digital)

---

### 📘 Deskripsi Singkat  
Proyek ini merupakan tugas **Ujian Tengah Semester (UTS)** mata kuliah *Pengolahan dan Analisis Citra Digital*.  
Tujuan utama proyek adalah membangun sistem **klasifikasi daun herbal** menggunakan citra digital dengan dua pendekatan:  

1. **CNN (Convolutional Neural Network)** — model dasar buatan sendiri.  
2. **MobileNetV2 (Transfer Learning)** — algoritma baru yang ditambahkan untuk meningkatkan akurasi dan efisiensi.  

---

### 🧠 Algoritma Baru yang Ditambahkan — *MobileNetV2 (Transfer Learning)*  
Algoritma ini merupakan pengembangan dari model awal (CNN) dengan memanfaatkan arsitektur **MobileNetV2**, yaitu model ringan yang telah dilatih pada dataset besar (*ImageNet*).  

Langkah yang dilakukan:  
- Mengimpor bobot pralatih (`imagenet`) tanpa lapisan akhir.  
- Menambahkan lapisan klasifikasi sesuai jumlah kelas dataset (3 kelas).  
- Melatih ulang hanya lapisan atas agar efisien dan cepat konvergen.  

📊 **Hasil Training (MobileNetV2):**
Found 123 images belonging to 3 classes.
Found 30 images belonging to 3 classes.

Epoch 10/10
Val Accuracy: 73.33%
Test Accuracy: 73.33%


💾 **Model disimpan:**  
`/content/drives/MyDrive/mobilenetv2_daun_herbal_fixed.h5`

⚙️ **Kelebihan:**
- Lebih cepat dilatih dibanding CNN dasar.  
- Memiliki akurasi validasi lebih tinggi (73.33%).  
- Ukuran model lebih kecil dan efisien untuk deployment.

---

### 📊 Perbandingan Hasil  

| Model | Akurasi Validasi | Waktu Latih | Kelebihan |
|:------|:----------------:|:------------:|:-----------|
| CNN Dasar | ±65% | Lebih lama | Cocok untuk pemahaman dasar CNN |
| MobileNetV2 | **73.33%** | Lebih cepat | Efisien & performa lebih baik |

---

### 🧩 Tools dan Library  
- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- OpenCV  

---

### 🧑‍💻 Kontributor  
**Muhammad Ebit Pangestu**  
NIM: 220201035  
Program Studi: Teknik Informatika  
Mata Kuliah: *Pengolahan dan Analisis Citra Digital*  

---

### 🚀 Kesimpulan  
Penambahan algoritma **MobileNetV2** berhasil meningkatkan performa klasifikasi daun herbal dibandingkan model CNN dasar.  
Transfer learning terbukti mampu memberikan akurasi lebih tinggi dengan waktu pelatihan yang lebih efisien.  

Proyek ini diharapkan dapat menjadi dasar untuk pengembangan sistem **identifikasi tanaman herbal berbasis AI** di masa depan. 🌱

