## 🌿 UTS Pengolahan dan Analisis Citra Digital  
**Klasifikasi Daun Herbal Menggunakan CNN & MobileNetV2 (Transfer Learning)**  

📎 **Repo:** [github.com/ebit-7/UTS-Pengolahan-dan-Analisis-Citra-Digital](https://github.com/ebit-7/UTS-Pengolahan-dan-Analisis-Citra-Digital)

---

### 📘 Deskripsi  
Proyek ini dibuat untuk memenuhi tugas **UTS Pengolahan dan Analisis Citra Digital** dengan tujuan mengklasifikasikan **jenis daun herbal** berdasarkan citra digital.  
Model yang digunakan:  
- **CNN (Convolutional Neural Network)** — model dasar.  
- **MobileNetV2 (Transfer Learning)** — algoritma baru untuk peningkatan akurasi & efisiensi.  

---

### ⚙️ Algoritma Baru — *MobileNetV2*  
MobileNetV2 digunakan sebagai pengembangan dari CNN dengan memanfaatkan bobot pralatih dari *ImageNet*.  
Langkah utama:
- Memuat bobot dasar (`imagenet`) tanpa lapisan akhir.  
- Menyesuaikan jumlah kelas (3 kelas).  
- Melatih hanya lapisan atas untuk efisiensi.  

**Hasil Training:**
Dataset: 123 gambar train, 30 gambar validasi
Epoch: 10
Val Accuracy: 73.33%
Test Accuracy: 73.33%


**Model:** `/content/drives/MyDrive/mobilenetv2_daun_herbal_fixed.h5`

---

### 📊 Perbandingan Model  

| Model | Akurasi Val | Waktu Latih | Kelebihan |
|:------|:-------------:|:-------------:|:------------|
| CNN | ±65% | Lebih lama | Mudah dipahami |
| **MobileNetV2** | **73.33%** | Lebih cepat | Efisien & akurat |

---

### 🧩 Teknologi  
Python • TensorFlow/Keras • NumPy • Matplotlib • OpenCV  

---

### 👨‍💻 Kontributor  
**Muhammad Ebit Pangestu**  
NIM: 220201035 — Teknik Informatika  

---

### 🚀 Kesimpulan  
Penambahan **MobileNetV2** meningkatkan akurasi dan efisiensi dibanding CNN dasar.  
Metode ini menunjukkan potensi besar untuk pengembangan sistem **identifikasi daun herbal berbasis AI**. 🌱
