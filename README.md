# Computer Vision & 3D Deep Learning Projects 🚀

Bu depo, otonom sistemler ve nesne tanıma üzerine geliştirdiğim Derin Öğrenme (Deep Learning) projelerini içermektedir. Projelerde hazır kütüphanelerin ötesine geçilerek, **PointNet** mimarisi ve **Evrişimli Sinir Ağları (CNN)** katmanları manuel olarak implemente edilmiştir.

## 📂 Proje İçerikleri

### 1. 3D Point Cloud Segmentation & Classification (PointNet)
**Dosya:** `3D_PointCloud_Segmentation_PointNet.ipynb`
* **Amaç:** LIDAR ve 3D tarayıcılardan gelen nokta bulutu (Point Cloud) verilerini işleyerek nesne tanıma ve segmentasyon yapmak.
* **Teknolojiler:** PyTorch, PointNet Architecture, ModelNet10 Dataset.
* **Detaylar:** - 3 boyutlu geometrik verilerin işlenmesi için PointNet mimarisi kuruldu.
  - ModelNet10 veri seti kullanılarak nesne sınıflandırma ve parça segmentasyonu yapıldı.

### 2. CNN Image Segmentation from Scratch
**Dosya:** `CNN_Image_Segmentation_From_Scratch.ipynb`
* **Amaç:** Görüntü segmentasyonu süreçlerini matematiksel temelden (from scratch) öğrenmek.
* **Teknolojiler:** Python, NumPy, Albumentations, PyTorch.
* **Detaylar:**
  - `nn.Conv2d` gibi hazır katmanların mantığını kavramak için **Convolution**, **Pooling** ve **Padding** işlemleri manuel matematiksel fonksiyonlarla yazıldı.
  - Veri çeşitliliğini artırmak için **Albumentations** kütüphanesi ile Data Augmentation teknikleri uygulandı.

### 3. Neural Network Fundamentals
**Dosya:** `Neural_Network_Fundamentals.ipynb`
* **Amaç:** Yapay sinir ağlarının (ANN) temel yapı taşlarını ve geri yayılım (backpropagation) algoritmalarını optimize etmek.

---

## 🛠 Teknik Yetkinlikler
* **Frameworks:** PyTorch, NumPy, Pandas, Scikit-Image
* **Algorithms:** PointNet, CNN, MLP, Gradient Descent
* **Concepts:** 3D Vision, Image Segmentation, Data Normalization, Feature Extraction

---
*Bu projeler TU Wien Bilgisayar Mühendisliği lisans eğitimi kapsamında geliştirilmiştir.*
