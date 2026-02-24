# Deepfake Video Detection System using ResNeXt & LSTM
### 🎓 Introduction to Image Computer Forensics Final Project

[English](#english) | [Türkçe](#türkçe)

---

<a name="english"></a>
## 🇺🇸 English

### 📌 Project Overview
[cite_start]This project was developed to distinguish between real and fake videos using a hybrid deep learning architecture[cite: 5]. [cite_start]ResNeXt and LSTM models are integrated to analyze both spatial (visual) and temporal (consistency) features of the videos[cite: 19, 20].

### 🛠️ Tech Stack & Environment
* [cite_start]**Google Colab:** Used for high-performance GPU support during the 20-epoch training process[cite: 17].
* [cite_start]**Libraries:** Developed in Python using `PyTorch`, `OpenCV`, `NumPy`, and `Scikit-learn`[cite: 17].

### 🔗 References
* **Original Project:** Based on [Deepfake detection using deep learning](https://github.com/abhijithjadhav/Deepfake_detection_using_deep_learning).
* [cite_start]**Dataset:** Custom subset derived from the **Celeb-DF-v2** dataset[cite: 8].

### 📊 Dataset Information
* [cite_start]**Full Dataset:** Consists of **667 videos** (325 Real, 342 Fake)[cite: 12].
* **Sample Data:** A small sample (10 Real, 10 Fake) is provided as `sample_dataset.zip` for testing.
* [cite_start]**Preprocessing:** Videos were decomposed into frames; faces were detected, cropped, and normalized[cite: 14, 15].

### 📈 Performance
* [cite_start]**Training Accuracy:** 85%[cite: 25].
* [cite_start]**Test Accuracy:** 56.7%[cite: 25].
* [cite_start]**Confusion Matrix:** 45 True Positives, 31 True Negatives[cite: 27, 28, 32, 33].

---

<a name="türkçe"></a>
## 🇹🇷 Türkçe

### 📌 Proje Özeti
[cite_start]Bu proje, hibrit bir derin öğrenme mimarisi kullanarak gerçek ve sahte videoları ayırt etmek amacıyla geliştirilmiştir[cite: 5]. [cite_start]ResNeXt ve LSTM modelleri bir araya getirilerek videoların hem görsel hem de zamansal tutarlılıkları analiz edilmiştir[cite: 19, 20].

### 🛠️ Geliştirme Ortamı ve Teknoloji Yığını
* [cite_start]**Google Colab:** 20 epoch süren eğitim sürecinde GPU desteği sağlaması nedeniyle tercih edilmiştir[cite: 17].
* **Kütüphaneler:** Python diliyle; [cite_start]`PyTorch`, `OpenCV` ve `Scikit-learn` kullanılarak kodlanmıştır[cite: 17].

### 🔗 Referanslar
* **Orijinal Repo:** abhijithjadhav/Deepfake_detection_using_deep_learning
* [cite_start]**Veri Kümesi:** Kaggle üzerindeki **Celeb-DF-v2** veri setinden türetilmiştir[cite: 8].

### 📊 Veri Seti Bilgileri
* [cite_start]**Tam Veri Seti:** Toplam **667 videodan** (325 Gerçek, 342 Sahte) oluşmaktadır[cite: 12].
* **Örnek Veri:** 10 Gerçek ve 10 Sahte videodan oluşan örneklem `sample_dataset.zip` adıyla sunulmuştur.
* [cite_start]**Ön İşleme:** Videolar karelere ayrılmış, yüz tespiti yapılmış ve normalize edilmiştir[cite: 14, 15].

### 📈 Performans ve Sonuçlar
* [cite_start]**Eğitim Başarısı:** %85[cite: 25].
* [cite_start]**Test Doğruluğu:** %56.7[cite: 25].
* [cite_start]**Karmaşıklık Matrisi:** 45 Doğru Sahte Tespiti, 31 Doğru Gerçek Tespiti[cite: 27, 28, 32, 33].

---

### 📦 Installation (Kurulum)

```text
torch>=1.7.0
torchvision>=0.8.0
numpy>=1.19.2
opencv-python>=4.4.0
scikit-learn>=0.23.2
