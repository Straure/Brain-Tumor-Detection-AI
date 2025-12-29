# 🧠 Derin Öğrenme ile Beyin Tümörü Tespiti / Brain Tumor Detection with Deep Learning

![Python](https://img.shields.io/badge/Python-3.9-blue?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?style=for-the-badge&logo=tensorflow&logoColor=white)
![Başarı](https://img.shields.io/badge/Doğruluk-%98.5-green?style=for-the-badge)

---

## 🇹🇷 Türkçe Proje Özeti
Bu çalışma, Manyetik Rezonans (MR) görüntüleri üzerinden beyin tümörlerini yüksek doğrulukla tespit etmek amacıyla geliştirilmiş bir tıbbi görüntü analiz projesidir. **Transfer Öğrenme (Transfer Learning)** stratejisi kullanılarak, önceden eğitilmiş **MobileNetV2** mimarisi yaklaşık 3.000 adet MR görüntüsü içeren veri seti üzerinde optimize edilmiştir.

### 🖼️ Analiz Sonucu (Demo)
![Demo Sonucu](demo_result.png)
*(Yapay zeka modeli, tümörlü bölgeyi standart eşik değerleri kullanarak başarıyla sınıflandırmaktadır.)*

---

## 🚀 Kurulum ve Çalıştırma / Installation

Projeyi bilgisayarınızda çalıştırmak için terminali açın ve aşağıdaki komut bloğunu sırasıyla uygulayın:

⚠️ ÖNEMLİ ADIM / IMPORTANT STEP: Model dosyasının boyutu büyük olduğu için GitHub ana dosya listesinde yer almamaktadır. Lütfen sağ taraftaki "Releases" kısmından .keras uzantılı model dosyasını indirin ve proje klasörünün içine atın.
```bash
# 1. Projeyi Klonlayın (Clone the repository)
git clone [https://github.com/Straure/Brain-Tumor-Detection-AI.git](https://github.com/Straure/Brain-Tumor-Detection-AI.git)

# 2. Proje Klasörüne Girin (Navigate to the project directory)
cd Brain-Tumor-Detection-AI

# 3. Gerekli Kütüphaneleri Yükleyin (Install dependencies)
pip install -r requirements.txt

# 4. Projeyi Başlatın (Run the Jupyter Notebook)
jupyter notebook
```
## 🇺🇸 English Project Overview
This project is a medical image analysis application designed to detect brain tumors from MRI scans with high accuracy. By utilizing a **Transfer Learning** strategy, a pre-trained **MobileNetV2** architecture was optimized on a dataset containing approximately 3,000 MRI images.

### 🚀 Key Features
- **Model Architecture:** MobileNetV2 (Fine-tuned for medical imaging).
- **Dataset:** ~3,000 MRI scans (Br35H & Public Datasets).
- **Accuracy:** Reached **98.5% validation accuracy**.
- **Hardware:** Optimized for **Apple Silicon (M1)** using TensorFlow-Metal.

---

## 📂 Teknik Detaylar / Technical Details
* **Veri Seti:** Br35H Dataset (~3000 MR görüntüsü).
* **Donanım:** Apple Silicon (M1) üzerinde GPU hızlandırmalı eğitim.
* **Performans:** Test verisi üzerinde **%98.5 doğruluk (accuracy)** skoru.

## 🛠️ Kullanılan Araçlar / Tech Stack
* TensorFlow / Keras
* OpenCV & PIL
* Matplotlib & NumPy
* IPyWidgets (Interactive Interface)

---
**Geliştirici / Developer:** Samet Yardımcı (Straure)
<br>
*Mehmet Akif Ersoy Üniversitesi - Bilişim Sistemleri ve Teknolojileri Bölümü*


