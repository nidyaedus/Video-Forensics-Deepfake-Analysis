# Deepfake Video Detection System using ResNeXt & LSTM
### Introduction to Image Computer Forensics Final Project

[English](#english) | [Türkçe](#türkçe)

---

<a name="english"></a>
## English

### Project Overview
This project was developed to distinguish between real and fake videos using a hybrid deep learning architecture. ResNeXt and LSTM models are integrated to analyze both spatial (visual) and temporal (consistency) features of the videos.

### Tech Stack & Environment
* **Google Colab:** Used for high-performance GPU support during the 20-epoch training process.
* **Libraries:** Developed in Python using `PyTorch`, `OpenCV`, `NumPy`, and `Scikit-learn`.

### References
* **Original Project:** Based on [Deepfake detection using deep learning](https://github.com/abhijithjadhav/Deepfake_detection_using_deep_learning).
* **Dataset:** Custom subset derived from the **Celeb-DF-v2** dataset.

### Dataset Information
* **Full Dataset:** Consists of **667 videos** (325 Real, 342 Fake).
* **Sample Data:** A small sample (10 Real, 10 Fake) is provided as `sample_dataset.zip` for testing.
* **Preprocessing:** Videos were decomposed into frames; faces were detected, cropped, and normalized.

### Performance
* **Training Accuracy:** 85%.
* **Test Accuracy:** 56.7%.
* **Confusion Matrix:** 45 True Positives, 31 True Negatives.

---

<a name="türkçe"></a>
## Türkçe

### Proje Özeti
Bu proje, hibrit bir derin öğrenme mimarisi kullanarak gerçek ve sahte videoları ayırt etmek amacıyla geliştirilmiştir. Proje kapsamında ResNeXt ve LSTM modelleri bir araya getirilerek videoların hem görsel hem de zamansal tutarlılıkları analiz edilmiştir.

### Geliştirme Ortamı ve Teknoloji Yığını
* **Google Colab:** 20 epoch süren eğitim sürecinde GPU desteği sağlaması nedeniyle tercih edilmiştir.
* **Kütüphaneler:** Python diliyle; `PyTorch`, `OpenCV` ve `Scikit-learn` kullanılarak kodlanmıştır.

### Referanslar
* **Orijinal Repo:** abhijithjadhav/Deepfake_detection_using_deep_learning
* **Veri Kümesi:** Kaggle üzerindeki **Celeb-DF-v2** veri setinden türetilmiştir.

### Veri Seti Bilgileri
* **Tam Veri Seti:** Toplam **667 videodan** (325 Gerçek, 342 Sahte) oluşmaktadır.
* **Örnek Veri:** 10 Gerçek ve 10 Sahte videodan oluşan örneklem `sample_dataset.zip` adıyla sunulmuştur.
* **Ön İşleme:** Videolar karelere ayrılmış, yüz tespiti yapılmış ve normalize edilmiştir.

### Performans ve Sonuçlar
* **Eğitim Başarısı:** %85.
* **Test Doğruluğu:** %56.7.
* **Karmaşıklık Matrisi:** 45 Doğru Sahte Tespiti, 31 Doğru Gerçek Tespiti.

---

### Installation (Kurulum)

```text
torch>=1.7.0
torchvision>=0.8.0
numpy>=1.19.2
opencv-python>=4.4.0
scikit-learn>=0.23.2
