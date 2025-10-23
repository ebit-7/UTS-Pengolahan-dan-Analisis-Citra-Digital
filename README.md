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
